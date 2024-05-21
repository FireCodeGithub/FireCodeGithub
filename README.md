<h1 align="center">Bonjour, je m'appelle FireBall</h1>
<h3 align="center">Un fan passionné d'informatique originaire de Belgique</h3>

<p align="left"> <img src="https ://komarev.com/ghpvc/?username=fireballgithub&label=Profile%20views&color=000000&style=plastic" alt="fireballgithub" /> </p>

<p align="left"> <a href="https:// github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=fireballgithub" alt="fireballgithub" /></a> </p>

- Je travaille actuellement sur **All of me**

- 🌱 J'apprends actuellement **Code better**

- Je cherche à collaborer sur **Nothing**

- Je recherche aide avec **De tous**

- 👨‍💻 Tous mes projets sont disponibles sur [github.com/FireBallGithub](github.com/FireBallGithub)

- 💬 Posez-moi des questions sur **Rien**

- 📫 Comment me joindre * *Rien maintenant**

- ⚡ Fait amusant **Je suis nouveau**

<h3 align="left">Connectez-vous avec moi :</h3>
<p align="left">
</p>

<h3 align="left" ">Langues et outils :</h3>
<p align="left"> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src ="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a > <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/ icônes/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank " rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height= "40"/> </a> <a href="https://zapier.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/ zapier/zapier-icon.svg" alt="zapier" width="40" height="40"/> </a> </p>

<p><img align="left" src="https:// github-readme-stats.vercel.app/api/top-langs?username=fireballgithub&show_icons=true&theme=dark&locale=en&layout=compact" alt="fireballgithub" /></p>

<p> <img align="center" src="https:// github-readme-stats.vercel.app/api?username=fireballgithub&show_icons=true&theme=dark&locale=en" alt="fireballgithub" /></p>

<p><img align="center" src="https:// github-readme-streak-stats.herokuapp.com/?user=fireballgithub&theme=dark" alt="fireballgithub" /></p>

# Visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          #  - public_repo
          #  - read:project
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          user: FireBallGithub
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Europe/Brussels
          config_twemoji: yes
          plugin_introduction: yes
          plugin_introduction_title: yes
          plugin_lines: yes
          plugin_lines_history_limit: 1
          plugin_lines_repositories_limit: 4
          plugin_lines_sections: base
          plugin_projects: yes
          plugin_projects_limit: 4
          plugin_repositories: yes
          plugin_repositories_order: featured, pinned, starred, random
          plugin_topics: yes
          plugin_topics_limit: 15
          plugin_topics_mode: starred
          plugin_topics_sort: stars


<!---
FireCodeGithub/FireCodeGithub is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
