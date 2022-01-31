<h1 align="center">Hi 👋, I'm Sumit</h1>
<h3 align="center">A passionate software programmer who has taken his first few steps in the world of programming</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=phoenixheron1&label=Profile%20views&color=0e75b6&style=flat" alt="phoenixheron1" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=phoenixheron1" alt="phoenixheron1" /></a> </p>

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

- 🔭 I’m currently working on **improving my Java skills and GUI designing**

- 🌱 I’m currently learning **Java**

- 👯 I’m looking to collaborate on **making a minecraft server of my own. But due to busy schedule and exams approaching I am not getting enough time.**

- 📫 How to reach me **sumitkumar1507@outlook.in**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://instagram.com/sumit_1507_" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="sumit_1507_" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=phoenixheron1&show_icons=true&locale=en&layout=compact" alt="phoenixheron1" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=phoenixheron1&show_icons=true&locale=en" alt="phoenixheron1" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=phoenixheron1&" alt="phoenixheron1" /></p>

# Visit https://github.com/lowlighter/metrics/blob/master/action.yml for full reference
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
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          # The following additional scopes may be required:
          #  - read:org  (for organization related metrics)
          #  - read:user (for user related data)
          #  - repo      (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          user: PhoenixHeron1
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Calcutta
          plugin_introduction: yes
          plugin_introduction_title: yes
          plugin_languages: yes
          plugin_languages_analysis_timeout: 15
          plugin_languages_categories: markup, programming
          plugin_languages_colors: github
          plugin_languages_limit: 8
          plugin_languages_recent_categories: markup, programming
          plugin_languages_recent_days: 14
          plugin_languages_recent_load: 300
          plugin_languages_sections: most-used
          plugin_languages_threshold: 0%
          plugin_repositories: 100
          plugin_repositories: yes
          plugin_repositories_affiliations: owner
          plugin_repositories_batch: 100
          plugin_stars: yes
          plugin_stars_limit: 4
