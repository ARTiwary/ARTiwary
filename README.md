<div align="center">

<img src="assets/header.svg" alt="Ayush Raj Tiwary: full stack developer, AI/ML builder, cricketer" width="100%" />

<br />

**[Portfolio](https://artiwary.vercel.app/)** &nbsp;·&nbsp; **[LinkedIn](https://www.linkedin.com/in/ayush-raj-tiwary/)** &nbsp;·&nbsp; **[HackerRank](https://www.hackerrank.com/profile/ayushrajtiwary07)** &nbsp;·&nbsp; **[ORCID](https://orcid.org/0009-0009-3038-5216)** &nbsp;·&nbsp; **[Email](mailto:ayushratiwary07@gmail.com)**

</div>

<br />

<img src="assets/sec-about.svg" alt="About" width="100%" />

<br />

<img src="assets/player-card.svg" alt="Player card: Ayush Raj Tiwary, B.Tech CSE, full stack and multi-agent AI, open for internships" width="100%" />

<br />

I build full stack products and teach machines to do useful things, mostly in Next.js, Node and Python. I like systems that work without supervision: a restaurant that runs on a chat, a scanner that reads MRIs, a viewer you steer with your hand. Off the keyboard I bowl, and I try to keep the same line and length in my code.

<br />

<img src="assets/sec-projects.svg" alt="Projects" width="100%" />

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://smart-dinning-assistent.vercel.app">
        <img src="assets/spice-garden.svg" alt="Spice Garden: AI dining assistant with eight agents orbiting an orchestrator named Zara" width="100%" />
      </a>
      <p align="center">
        <a href="https://smart-dinning-assistent.vercel.app"><b>Live</b></a> &nbsp;·&nbsp;
        <a href="https://smart-dinning-assistent.vercel.app/admin"><b>Admin panel</b></a> &nbsp;·&nbsp;
        <a href="https://github.com/ARTiwary/smart-dinning-assistent"><b>Source</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <a href="https://brain-tumor-with-gesture.netlify.app/">
        <img src="assets/neuro-core.svg" alt="NEURO-CORE: brain tumour MRI detection with 94.81 percent accuracy, controlled by hand gestures" width="100%" />
      </a>
      <p align="center">
        <a href="https://brain-tumor-with-gesture.netlify.app/"><b>Live</b></a> &nbsp;·&nbsp;
        <a href="https://github.com/ARTiwary/MRI-brain-tumour-detection-with-gesture-control-"><b>Source</b></a>
      </p>
    </td>
  </tr>
</table>

<details>
<summary><b>How they are wired</b> &nbsp;<sub>(architecture diagrams, click to open)</sub></summary>

<br />

**Spice Garden**

```mermaid
flowchart LR
    A[QR Scan] --> B[Next.js Client]
    B <-->|Socket.io| C[Node.js API]
    C --> D{{Zara · Orchestrator}}
    D --> E[8 Specialized Agents]
    E <--> F[(ChromaDB)]
    E <--> G[Groq LLM]
    C <--> H[(PostgreSQL)]
    C <--> I[(Redis)]
```

**NEURO-CORE**

```mermaid
flowchart LR
    A[MRI Scan] --> B[Preprocess]
    B --> C[Custom CNN]
    B --> D[ResNet18]
    C --> E{Ensemble}
    D --> E
    E --> F[4-class Prediction]
    E --> G[Grad-CAM]
    H[Webcam] --> I[MediaPipe] --> J[Gesture Control]
    F --> K[Three.js Viewer]
    G --> K
    J --> K
```

</details>

**Also in the pavilion:** &nbsp;
[portfolio](https://github.com/ARTiwary/portfolio) (my site, AI/ML and full stack work) &nbsp;·&nbsp;
[Air-gesture-recognition](https://github.com/ARTiwary/Air-gesture-recognition) (hand gestures in JavaScript)

<br />

<img src="assets/sec-stack.svg" alt="Stack" width="100%" />

<br />

<img src="assets/scorecard.svg" alt="Tech stack scorecard" width="100%" />

<br />

<img src="assets/sec-stats.svg" alt="Stats" width="100%" />

<br />

<div align="center">

<img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=ARTiwary&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=0E1B2C&title_color=F2A93B&icon_color=E2432F&text_color=EAF2FB" />
<img height="170" alt="Streak stats" src="https://streak-stats.demolab.com?user=ARTiwary&hide_border=true&background=0E1B2C&ring=E2432F&fire=F2A93B&currStreakLabel=F2A93B&currStreakNum=EAF2FB&sideNums=EAF2FB&sideLabels=7FB3E6&dates=7FB3E6" />

<br />

<img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ARTiwary&layout=compact&hide_border=true&bg_color=0E1B2C&title_color=F2A93B&text_color=EAF2FB&langs_count=8" />

<br />

<img width="100%" alt="Contribution graph" src="https://github-readme-activity-graph.vercel.app/graph?username=ARTiwary&bg_color=0E1B2C&color=7FB3E6&line=E2432F&point=EAF2FB&area=true&area_color=E2432F&hide_border=true" />

<br />

<img width="100%" alt="Snake eating my contributions" src="https://raw.githubusercontent.com/ARTiwary/ARTiwary/output/github-snake-dark.svg" />

</div>

<br />

<img src="assets/sec-offpitch.svg" alt="Off the pitch" width="100%" />

<br />

<table>
  <tr>
    <td width="50%" valign="top">

**Between overs**

- 🏏 **Cricket**: bowling all-rounder, clean action, good line
- ✏️ **Sketching**: stress reset and creative outlet
- 🤝 **Brainstorming** with teams until 2am

</td>
    <td width="50%" valign="top">

**House rules**

- Systems thinking over firefighting
- Build it. Ship it. Improve it.
- Every bug is a feature not yet understood
- A $0 infra bill is an engineering achievement

</td>
  </tr>
</table>

<br />

<img src="assets/sec-connect.svg" alt="Connect" width="100%" />

<br />

<div align="center">

Open to internships and collaborations, especially full stack and applied AI. If something here caught your eye, my inbox is open.

<br />

<a href="https://www.linkedin.com/in/ayush-raj-tiwary/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-ayush--raj--tiwary-0E1B2C?style=for-the-badge&logo=linkedin&logoColor=7FB3E6&labelColor=E2432F" /></a>
<a href="mailto:ayushratiwary07@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-ayushratiwary07-0E1B2C?style=for-the-badge&logo=gmail&logoColor=F2A93B&labelColor=E2432F" /></a>
<a href="https://artiwary.vercel.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-artiwary.vercel.app-0E1B2C?style=for-the-badge&logo=vercel&logoColor=EAF2FB&labelColor=E2432F" /></a>
<a href="https://www.instagram.com/the_tiwaryrajayush"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-the__tiwaryrajayush-0E1B2C?style=for-the-badge&logo=instagram&logoColor=EAF2FB&labelColor=E2432F" /></a>

<br /><br />

<img src="assets/footer.svg" alt="Learn every day. Build with passion. Grow without limits." width="100%" />

<br />

<sub><img alt="Profile views" src="https://komarev.com/ghpvc/?username=ARTiwary&label=views&color=E2432F&style=flat-square&labelColor=0E1B2C" /></sub>

</div>
