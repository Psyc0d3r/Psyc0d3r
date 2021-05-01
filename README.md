### Hi there 👋

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=psyc0d3r&show_owner&hide=contribs,prs&theme=cobalt)
<a href="https://github.com/Psyc0d3r">
  
  
  <img align="center" src="https://img.shields.io/github/followers/psyc0d3r?color=Red&logoColor=heavy%20blue&style=social" />
</a>

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'MEA Mobile',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
