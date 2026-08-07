<h1 align="center">Hi 👋, I'm Dev Kachhadiya</h1>
<h3 align="center">A passionate frontend developer from India</h3>

- 📫 How to reach me **dev.kachhadiya.cg@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/dev-kachhadiya-739260427" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="www.linkedin.com/in/dev-kachhadiya-739260427" height="30" width="40" /></a>
<a href="https://instagram.com/dev_kachhadiya11" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="dev_kachhadiya11" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

# 📊 GitHub Stats:



![](https://github-readme-stats.shion.dev/api?username=Dev-kachhadiya&theme=dark&hide_border=false&include_all_commits=true&count_private=true)





![](https://streak-stats.demolab.com/?user=Dev-kachhadiya&theme=dark&hide_border=false)




## 📈 Contribution Graph:



![](https://github-readme-activity-graph.vercel.app/graph?username=Dev-kachhadiya&theme=react-dark)

.github/workflows/snake.yml

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"   # runs every 12 hours
  workflow_dispatch: {}      # lets you trigger it manually too
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake animation
        uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: Dev-kachhadiya
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake output to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

          ## 🐍 Contribution Snake:



![snake gif](https://raw.githubusercontent.com/Dev-kachhadiya/Dev-kachhadiya/output/github-contribution-grid-snake-dark.svg)
