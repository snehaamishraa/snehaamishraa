<h1 align="center">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35">
  Hi, I'm Sneha Mishra
</h1>

<h3 align="center">
AI Engineer • Full Stack Web Developer • DSA Enthusiast
</h3>

<p align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=24&duration=3500&pause=1000&color=8A2BE2&center=true&vCenter=true&width=750&lines=AI+Engineer+in+Progress;Full+Stack+Web+Developer;Python+%7C+React+%7C+Node.js;Building+AI+Applications;Learning+Agentic+AI;Open+Source+Learner"/>

</p>

<p align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=7F5AF0&height=180&section=header&text=Welcome%20to%20My%20GitHub&fontSize=42&fontColor=ffffff&animation=fadeIn"/>

</p>

<p align="center">

<img src="https://komarev.com/ghpvc/?username=snehaamishraa&label=Profile%20Views&color=blueviolet&style=for-the-badge"/>

<img src="https://img.shields.io/github/followers/snehaamishraa?style=for-the-badge"/>

<img src="https://img.shields.io/github/stars/snehaamishraa?style=for-the-badge"/>

</p>

# <img src="https://media.giphy.com/media/ObNTw8Uzwy6KQ/giphy.gif" width="35"> About Me

<img align="right" alt="Coding" width="350" src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif">

🎓 Final Year **B.Tech Computer Science** Student from India 🇮🇳

🤖 Aspiring **AI Engineer** passionate about building intelligent applications.

💻 Full Stack Web Developer with hands-on experience in modern web technologies.

🧠 Consistently solving **Data Structures & Algorithms** to strengthen problem-solving skills.

🚀 Currently building **AI-powered applications**, automation tools, and full-stack projects.

🌱 Exploring **Agentic AI, Next.js, Backend Development, and System Design**.

🤝 Open to **Internships, Open Source Contributions, and Collaboration**.

⚡ I enjoy transforming ideas into real-world products that create impact.

🎯 **2026 Goals**

- 🧩 Solve 500+ DSA Problems
- 🤖 Build Production-Ready AI Projects
- 🌍 Contribute to Open Source
- 💼 Crack an SDE / AI Engineer Internship
- 🚀 Keep Learning Every Single Day

<br clear="both">
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *" # Runs every day at midnight UTC
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}

          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
            dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#0d1117

      - name: Push Snake Animation
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

# 🐍 Contribution Snake

<p align="center">

<img src="https://raw.githubusercontent.com/snehaamishraa/snehaamishraa/output/github-snake-dark.svg" alt="Snake animation"/>

</p>

## 🚀 Languages

<p align="left">
<img src="https://skillicons.dev/icons?i=python,js,html,css,c" />
</p>

---

## 🎨 Frontend Development

<p align="left">
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind" />
</p>

---

## ⚙️ Backend Development

<p align="left">
<img src="https://skillicons.dev/icons?i=nodejs,express" />
</p>

---

## 🗄️ Database

<p align="left">
<img src="https://skillicons.dev/icons?i=postgres,mysql" />
</p>

---

## 🤖 AI & Machine Learning

<p align="left">

<img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white"/>

<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>

<img src="https://img.shields.io/badge/Prompt_Engineering-7F52FF?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Agentic_AI-8A2BE2?style=for-the-badge"/>

</p>

---

## 🛠️ Tools & Platforms

<p align="left">
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,vercel,npm" />
</p>

---

## 📚 Currently Learning

<p align="left">
<img src="https://skillicons.dev/icons?i=nextjs,nodejs,postgres,docker" />
</p>

<p>

🔹 Agentic AI

🔹 MCP (Model Context Protocol)

🔹 LangChain

🔹 Advanced Backend Development

🔹 System Design

</p>
# 📊 GitHub Analytics

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=snehaamishraa&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=snehaamishraa&layout=compact&theme=tokyonight&hide_border=true"/>

</p>

<p align="center">

<img width="700" src="https://github-readme-streak-stats.herokuapp.com/?user=snehaamishraa&theme=tokyonight&hide_border=true"/>

</p>
# 📈 Contribution Graph

<p align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=snehaamishraa&theme=tokyo-night&hide_border=true"/>

</p>
# 🏆 GitHub Trophies

<p align="center">

<img src="https://github-profile-trophy.vercel.app/?username=snehaamishraa&theme=tokyonight&no-frame=true&margin-w=15&row=1"/>

</p>

