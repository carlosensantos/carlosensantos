<h2 align="left">Techs</h2>

###

<div align="left">
  <img src="https://skillicons.dev/icons?i=js" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=ts" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=nodejs" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=express" height="40" alt="express logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=nestjs" height="40" alt="nestjs logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=jest" height="40" alt="jest logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=prisma" height="40" alt="prisma logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=docker" height="40" alt="docker logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=git" height="40" alt="git logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=html" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=css" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=react" height="40" alt="react logo"  />
</div>

###

<h2 align="left">Stats</h2>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=carlosensantos&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=github_dark&locale=en&hide_border=false&order=1" height="130" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=carlosensantos&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=github_dark&hide_border=false&order=2" height="130" alt="languages graph"  />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=carlosensantos&radius=16&theme=github-dark&area=true&order=5" height="240" alt="activity-graph graph"  />
</div>

###

<h2 align="left">Social Media</h2>

###

<div align="left">
  <a href="https://www.linkedin.com/in/carlosensantos/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  </a>
  <a href="https://discord.com/channels/@carlosensantos" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="discord logo"  />
  </a>
  <a href="https://www.instagram.com/carlosensantos" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="52" height="40" alt="instagram logo"  />
  </a>
</div>

###

<img src="https://raw.githubusercontent.com/carlosensantos/carlosensantos/output/snake.svg" alt="Snake animation" />

###

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
