<div align="center">

<img src="https://img.shields.io/badge/AMIT_HASAN_SIMANTO-ASPIRING_AI_ENGINEER-211638?style=for-the-badge&labelColor=0D1117&color=211638" alt="Amit Hasan Simanto — Aspiring AI Engineer">

<br><br>

<a href="https://github.com/amiiiiiitz"><img src="https://img.shields.io/badge/GitHub-amiiiiiitz-17102B?style=for-the-badge&logo=github&logoColor=F5F3FF" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/amit-hasan-simanto-301694346/"><img src="https://img.shields.io/badge/LinkedIn-Connect-12323D?style=for-the-badge&logo=linkedin&logoColor=67E8F9" alt="LinkedIn"></a>
<a href="mailto:amit.hasan2730@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-211638?style=for-the-badge&logo=gmail&logoColor=A78BFA" alt="Email"></a>
<a href="https://amit-hasan-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-12323D?style=for-the-badge&logo=vercel&logoColor=67E8F9" alt="Portfolio"></a>

<br><br>

<img src="https://img.shields.io/badge/EDUCATION-CSE_·_3rd_Year_·_IUBAT-211638?style=flat-square&labelColor=0D1117" alt="CSE, third year, IUBAT">
<img src="https://img.shields.io/badge/FOCUS-AI_Engineering-12323D?style=flat-square&labelColor=0D1117" alt="Focus: AI engineering">
<img src="https://img.shields.io/badge/APPROACH-Learn_by_building-211638?style=flat-square&labelColor=0D1117" alt="Approach: learn by building">

<br><br>

| [About](#about-me) | [Tech Stack](#tech-stack) | [Interests](#areas-of-interest) | [AI Architecture](#ai-app-architecture) | [Repositories](#featured-repositories) | [Roadmap](#learning-roadmap) | [Connect](#connect-with-me) |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|

</div>

---

## About Me

I'm a third-year Computer Science and Engineering student at IUBAT, developing my programming and application-building skills while exploring practical AI engineering.

I'm interested in how AI systems can be integrated into useful applications, particularly through large language models, retrieval-augmented generation, AI agents, and workflow automation.

My goal is to strengthen my engineering foundations, build meaningful projects, and grow into an AI engineering role.

```python
amit = {
    "name": "Amit Hasan Simanto",
    "education": "CSE Student at IUBAT (3rd year)",
    "career_goal": "Aspiring AI Engineer",
    "languages": ["C", "C++", "Python", "JavaScript"],
    "interests": [
        "AI and Machine Learning",
        "LLM Applications",
        "RAG",
        "AI Agents",
        "Workflow Automation",
    ],
    "approach": "Learn by building and solving problems",
}
```

---

## Tech Stack

<div align="center">

<sub><b>PROGRAMMING LANGUAGES</b></sub><br><br>
<img src="https://skillicons.dev/icons?i=c,cpp,python,js&theme=dark" height="44" alt="C, C++, Python, and JavaScript">

<br><br>

<sub><b>FRONTEND DEVELOPMENT</b></sub><br><br>
<img src="https://skillicons.dev/icons?i=react,vite,tailwind,html,css&theme=dark" height="44" alt="React, Vite, Tailwind CSS, HTML, and CSS">

<br><br>

<sub><b>DEVELOPER TOOLS</b></sub><br><br>
<img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark" height="44" alt="Git, GitHub, and Visual Studio Code">

<br><br>

<sub><b>CURRENTLY EXPLORING</b></sub><br><br>
<img src="https://img.shields.io/badge/AI%20%26%20Machine%20Learning-211638?style=for-the-badge&logo=googlecolab&logoColor=A78BFA" alt="AI and machine learning">
<img src="https://img.shields.io/badge/LLM%20Applications-12323D?style=for-the-badge&logo=openai&logoColor=67E8F9" alt="LLM applications">
<img src="https://img.shields.io/badge/RAG-211638?style=for-the-badge&logo=databricks&logoColor=A78BFA" alt="Retrieval-augmented generation">
<img src="https://img.shields.io/badge/AI%20Agents-12323D?style=for-the-badge&logo=probot&logoColor=67E8F9" alt="AI agents">
<img src="https://img.shields.io/badge/Workflow%20Automation-211638?style=for-the-badge&logo=n8n&logoColor=A78BFA" alt="Workflow automation">

</div>

---

## Areas of Interest

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 AI Engineering</h3>
      <p>Practical AI applications, LLM integration, RAG pipelines, and AI agents.</p>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ Application Development</h3>
      <p>Python, React, APIs, and connecting software components into useful products.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📚 Continuous Learning</h3>
      <p>Programming fundamentals, data structures, algorithms, and AI knowledge.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🧩 Problem Solving</h3>
      <p>Practising coding problems and improving logical thinking through implementation.</p>
    </td>
  </tr>
</table>

### AI focus map

```mermaid
mindmap
  root((AI Engineer))
    LLM Applications
      Prompting
      API integration
    RAG
      Retrieval
      Knowledge bases
    AI Agents
      Tools
      Workflows
    Foundations
      Python
      DSA
      Machine Learning
```

---

## AI App Architecture

The kind of AI application I'm learning to build:

```mermaid
flowchart LR
    U([User])

    subgraph FE[Frontend]
        UI[React UI]
    end

    subgraph BE[Backend]
        API[Python API]
    end

    subgraph AI[AI layer]
        RAG[RAG Retriever]
        KB[(Knowledge Base)]
        LLM[[LLM]]
    end

    U -- "1 asks" --> UI
    UI -- "2 request" --> API
    API -- "3 query" --> RAG
    RAG <-- "facts" --> KB
    RAG -- "4 context" --> LLM
    API <-- "prompt / answer" --> LLM
    API -- "5 answer" --> UI

    classDef front fill:#12323D,stroke:#67E8F9,stroke-width:2px,color:#F5F3FF;
    classDef core fill:#211638,stroke:#A78BFA,stroke-width:2px,color:#F5F3FF;
    class U,UI front;
    class API,RAG,KB,LLM core;
    style FE fill:#0D1117,stroke:#67E8F9,stroke-dasharray:5 5;
    style BE fill:#0D1117,stroke:#A78BFA,stroke-dasharray:5 5;
    style AI fill:#0D1117,stroke:#A78BFA,stroke-dasharray:5 5;
    linkStyle default stroke:#67E8F9,stroke-width:2px;
```

1. The user types a question in the **React** interface.
2. The interface sends it to the **Python API**.
3. The API asks the **RAG retriever** to find useful facts in the knowledge base.
4. The **LLM** (large language model) writes the answer using those facts.
5. The answer travels back through the API to the screen.

---

## Featured Repositories

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 Portfolio Website</h3>
      <p>My personal portfolio presenting my background, projects, and achievements.</p>
      <a href="https://amit-hasan-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-12323D?style=flat-square&logo=vercel&logoColor=67E8F9" alt="Live portfolio"></a>
      <a href="https://github.com/amiiiiiitz/development/tree/main/builtWithAI/amit-portfolio"><img src="https://img.shields.io/badge/Source_Code-211638?style=flat-square&logo=github&logoColor=A78BFA" alt="Portfolio source code"></a>
    </td>
    <td width="50%" valign="top">
      <h3>🧩 Problem Solving</h3>
      <p>A collection of programming solutions from platforms including Codeforces and LeetCode.</p>
      <a href="https://github.com/amiiiiiitz/problem-solving"><img src="https://img.shields.io/badge/View_Repository-211638?style=flat-square&logo=github&logoColor=A78BFA" alt="Problem-solving repository"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛠️ Development</h3>
      <p>Software development projects, practical experiments, and technical learning.</p>
      <a href="https://github.com/amiiiiiitz/development"><img src="https://img.shields.io/badge/View_Repository-211638?style=flat-square&logo=github&logoColor=A78BFA" alt="Development repository"></a>
    </td>
    <td width="50%" valign="top">
      <h3>📂 More Repositories</h3>
      <p>Explore my public repositories to follow my coding practice and development journey.</p>
      <a href="https://github.com/amiiiiiitz?tab=repositories"><img src="https://img.shields.io/badge/Explore_All-12323D?style=flat-square&logo=github&logoColor=67E8F9" alt="All public repositories"></a>
    </td>
  </tr>
</table>

---

## Learning Roadmap

```mermaid
timeline
    title My learning direction
    Foundations : Programming : DSA : Problem Solving
    Applications : Python : React : APIs
    AI Foundations : Machine Learning : AI Concepts
    AI Engineering : LLMs : RAG : AI Agents
```

<p align="center"><sub>A learning direction, not a claim that every stage is complete.</sub></p>

---

## GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=amiiiiiitz&hide_border=true&background=0D1117&ring=A78BFA&fire=67E8F9&currStreakLabel=67E8F9&sideLabels=E5E7EB&currStreakNum=F5F3FF&sideNums=F5F3FF&dates=9CA3AF&border_radius=12" height="170" alt="GitHub contribution streak">

</div>

---

## Achievements

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🎓 Scholar's List</h3>
      <p>Academic achievement certificate.</p>
    </td>
    <td width="50%" valign="top">
      <h3>💻 Programming Contests</h3>
      <p>Programming contest participation.</p>
    </td>
  </tr>
</table>

---

## Connect With Me

<div align="center">

<a href="https://github.com/amiiiiiitz"><img src="https://img.shields.io/badge/GitHub-211638?style=for-the-badge&logo=github&logoColor=F5F3FF" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/amit-hasan-simanto-301694346/"><img src="https://img.shields.io/badge/LinkedIn-12323D?style=for-the-badge&logo=linkedin&logoColor=67E8F9" alt="LinkedIn"></a>
<a href="mailto:amit.hasan2730@gmail.com"><img src="https://img.shields.io/badge/Email-211638?style=for-the-badge&logo=gmail&logoColor=A78BFA" alt="Email"></a>

<br><br>

### Thanks for visiting my profile.

**If you find a repository useful, consider giving it a ⭐**

<sub>Learning consistently · Building thoughtfully · Growing one project at a time</sub>

</div>
