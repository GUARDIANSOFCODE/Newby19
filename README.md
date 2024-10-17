Hi, I'm Newby19<img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px">
<table>
  <tr>
    <td valign="center">
      🎓 I am currently pursuing my Bachelor's in Computer Science Engineering.
      🌱 I am currently learning **Java** and also interested in Web Development.
      🎯 My Goal is to Contribute to as many open source project as possible.
      ✨ I love to create different types of contents.
<td >

    
    
  </tr>
  </table>
![GitHub Activity Graph](https://activity-graph.herokuapp.com/graph?username=Newby19&theme=react-dark

## Stats📈
<p align="center">
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=#Newby19&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&layout=compact&hide_border=true" alt="#Newby19" /> 
<img width="48%" src="https://github-readme-stats.vercel.app/api?username=#Newby19&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&hide_border=true" alt="#Newby19" />
<img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=#Newby19&theme=highcontrast&hide_border=true" alt="#Newby19" />
</p>

name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}