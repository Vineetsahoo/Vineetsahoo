<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=6,11,20&height=160&section=header&text=Vineet%20Sahoo&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=58&desc=Frontend%20Engineer%20%C2%B7%20AI%20Systems%20%C2%B7%20Cloud%20%26%20DevOps&descAlignY=80&descSize=15&descColor=a5b4fc" width="100%"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=400&size=13&duration=5000&pause=2500&color=818CF8&center=true&vCenter=true&width=740&lines=B.Tech+Computer+Science+%E2%80%94+SRM+Institute+of+Science+%26+Technology%2C+Tamil+Nadu;Building+at+the+intersection+of+engineering+rigor+and+product+craft;Open+to+engineering+internships+%26+technical+collaborations" alt="Subtitle" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vineet-sahoo-81b022311/)&ensp;
[![Portfolio](https://img.shields.io/badge/Portfolio-4F46E5?style=flat-square&logo=vercel&logoColor=white)](https://vineetsahoo.vercel.app/)&ensp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vineetsahoo3@gmail.com)&ensp;
[![X](https://img.shields.io/badge/X%20%2F%20Twitter-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/VineetSaho63046)

<br/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2" width="100%"/>

<br/>

## `$ whoami`

```typescript
const vineet = {
  university  : "SRM Institute of Science & Technology, Tamil Nadu",
  degree      : "B.Tech — Computer Science Engineering",
  domains     : [
    "Scalable Frontend Engineering",
    "AI-Powered Full-Stack Systems",
    "Cloud Infrastructure & DevOps",
  ],
  openTo      : ["Engineering Internships", "Technical Collaborations", "Open Source"],
};
```

> I build software that is technically sound, visually precise, and architecturally intentional.  
> From production CI/CD observability platforms to ML-powered healthcare systems — I bring the same  
> engineering discipline to every layer of the stack.

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2" width="100%"/>

<br/>

## Technical Expertise

<div align="center">

<table>
<tr><td align="center" width="120"><sub><b>Frontend</b></sub></td><td>
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind,js,html,css" />
</td></tr>
<tr><td align="center"><sub><b>Backend</b></sub></td><td>
<img src="https://skillicons.dev/icons?i=nodejs,express,python" />
</td></tr>
<tr><td align="center"><sub><b>Databases</b></sub></td><td>
<img src="https://skillicons.dev/icons?i=mongodb,mysql" />
</td></tr>
<tr><td align="center"><sub><b>Cloud & DevOps</b></sub></td><td>
<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,ansible,jenkins,githubactions,linux" />
</td></tr>
<tr><td align="center"><sub><b>Observability</b></sub></td><td>
<img src="https://skillicons.dev/icons?i=prometheus,grafana" />
</td></tr>
<tr><td align="center"><sub><b>Languages</b></sub></td><td>
<img src="https://skillicons.dev/icons?i=python,java,cpp,c" />
</td></tr>
</table>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2" width="100%"/>

<br/>

## Featured Projects

> Four flagship systems — built with production-grade architecture and engineering discipline.

<br/>

<!-- ════════════════════════════  PROJECT 01  ════════════════════════════ -->

<table>
<tr>
<td width="53%" valign="top">

**[MoraAI — AI-Driven CI/CD RCA Platform](https://github.com/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard)**

![Stars](https://img.shields.io/github/stars/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard?style=flat-square&color=6366f1&label=Stars)&ensp;![Language](https://img.shields.io/github/languages/top/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard?style=flat-square&color=818cf8)&ensp;![Updated](https://img.shields.io/github/last-commit/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard?style=flat-square&color=6366f1&label=Updated)

`DevOps` &nbsp; `AI / ML` &nbsp; `SaaS` &nbsp; `Cloud Infrastructure`

A production-grade SaaS platform that applies AI to detect CI/CD pipeline failures, synthesize root-cause analysis, and deliver one-click remediation workflows. The AI layer operates as a resilient fallback chain — **AWS Bedrock Nova → Ollama → local model** — eliminating any single point of failure.

**Stack**
<img src="https://skillicons.dev/icons?i=react,ts,tailwind,nodejs,aws,docker,kubernetes,terraform" height="28"/>

**Engineering highlights**
- Multi-stage GH Actions CI: `backend-check → frontend-build → api-smoke → sonar-scan → docker-build`
- Full IaC via Terraform — VPC, EKS, ECR, Lambda, CloudWatch, Bedrock IAM all codified
- One-command EKS rollout via Ansible + Terraform + kubectl orchestration
- Auto-provisioned Grafana dashboards consuming live `/metrics` from the Express backend

</td>
<td width="47%" valign="top" align="center">

```
  Browser
  React + TypeScript + Tailwind
         │
  Express API  ←──→  /metrics
         │
  AI Fallback Chain
  ├── AWS Bedrock Nova  (primary)
  ├── Ollama            (fallback)
  └── Local model       (offline)
         │
  AWS Infrastructure (Terraform)
  ┌──────┬──────┬───────────┐
  EKS   ECR   Lambda   CloudWatch
         │
  Prometheus ──→ Grafana
  (auto-provisioned dashboards)
```

<br/>

![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions_%2B_Jenkins-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![IaC](https://img.shields.io/badge/IaC-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-AWS_EKS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)

</td>
</tr>
</table>

<br/>

<!-- ════════════════════════════  PROJECT 02  ════════════════════════════ -->

<table>
<tr>
<td width="47%" valign="top" align="center">

```
  Patient Diagnostic Data (CSV)
         │
  EDA & Data Preprocessing
  Pandas · NumPy
         │
  Feature Engineering
  (correlation · normalization)
         │
  Model Training & Comparison
  ├── Logistic Regression
  ├── Random Forest
  └── SVM / Gradient Boosting
         │
  Cross-Validation & Scoring
         │
  Risk Assessment Output
  Matplotlib · Seaborn viz
```

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ML](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
<td width="53%" valign="top">

**[CardioVision AI — Healthcare ML System](https://github.com/Vineetsahoo/CardioVision-AI)**

![Stars](https://img.shields.io/github/stars/Vineetsahoo/CardioVision-AI?style=flat-square&color=6366f1&label=Stars)&ensp;![Language](https://img.shields.io/github/languages/top/Vineetsahoo/CardioVision-AI?style=flat-square&color=818cf8)&ensp;![Updated](https://img.shields.io/github/last-commit/Vineetsahoo/CardioVision-AI?style=flat-square&color=6366f1&label=Updated)

`Machine Learning` &nbsp; `Healthcare` &nbsp; `Data Science` &nbsp; `Python`

An ML-powered cardiovascular risk assessment system that processes patient diagnostic data to surface predictive insights about heart health. Bridges the gap between raw medical datasets and actionable clinical intelligence.

**Stack**
<img src="https://skillicons.dev/icons?i=python,jupyter" height="28"/>

**Engineering highlights**
- End-to-end ML pipeline: data ingestion → EDA → feature engineering → model training → evaluation
- Comparative analysis across multiple classifiers with cross-validation and hyperparameter tuning
- Publication-quality visualizations surfacing feature correlations and cardiovascular risk distributions
- Reproducible research structure — every analysis step documented, version-controlled, and executable

</td>
</tr>
</table>

<br/>

<!-- ════════════════════════════  PROJECT 03  ════════════════════════════ -->

<table>
<tr>
<td width="53%" valign="top">

**[Next.js AI Chatbot — NVIDIA](https://github.com/Vineetsahoo/Next-Ai-Chatbot---NVIDIA)**

![Stars](https://img.shields.io/github/stars/Vineetsahoo/Next-Ai-Chatbot---NVIDIA?style=flat-square&color=6366f1&label=Stars)&ensp;![Language](https://img.shields.io/github/languages/top/Vineetsahoo/Next-Ai-Chatbot---NVIDIA?style=flat-square&color=818cf8)&ensp;![Updated](https://img.shields.io/github/last-commit/Vineetsahoo/Next-Ai-Chatbot---NVIDIA?style=flat-square&color=6366f1&label=Updated)

`Next.js` &nbsp; `AI / LLM` &nbsp; `Real-Time UI` &nbsp; `NVIDIA`

A real-time conversational AI interface built with Next.js and NVIDIA's inference APIs. Engineered for low-latency response streaming and a production-quality chat UX — built as part of a Prismic Community developer challenge.

**Stack**
<img src="https://skillicons.dev/icons?i=nextjs,react,js,vercel" height="28"/>

**Engineering highlights**
- Real-time message streaming with low-latency NVIDIA inference pipeline
- Stateful conversation management across multi-turn sessions
- Clean separation of concerns: UI layer, API client, and CMS-driven content
- Responsive, accessible chat interface built without component library dependencies

</td>
<td width="47%" valign="top" align="center">

```
  User Chat Interface
  Next.js + CSS Modules
         │
  Next.js API Route Handler
         │
  NVIDIA Inference API
  (server-sent event stream)
         │
  Prismic CMS
  (content & configuration layer)
         │
  Token stream → State update
  → React UI re-render
  (multi-turn session state)
```

<br/>

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Prismic](https://img.shields.io/badge/Prismic_CMS-5163BA?style=flat-square&logo=prismic&logoColor=white)

</td>
</tr>
</table>

<br/>

<!-- ════════════════════════════  PROJECT 04  ════════════════════════════ -->

<table>
<tr>
<td width="47%" valign="top" align="center">

```
  .qmd Source Files
  Python + Markdown (unified source)
         │
  Quarto Render Engine
         │
  ┌──────┼────────┐
  │      │        │
HTML    PDF   Reveal.js
              (interactive)
         │
  Live Python Code Execution
  embedded in document body
         │
  Charts · Tables · Code output
  (literate programming model)
```

<br/>

![Quarto](https://img.shields.io/badge/Quarto-447099?style=flat-square&logo=quarto&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
<td width="53%" valign="top">

**[Quarto Learning Journey — Technical Publishing](https://github.com/Vineetsahoo/Quarto-Learning-Journey-)**

![Stars](https://img.shields.io/github/stars/Vineetsahoo/Quarto-Learning-Journey-?style=flat-square&color=6366f1&label=Stars)&ensp;![Language](https://img.shields.io/github/languages/top/Vineetsahoo/Quarto-Learning-Journey-?style=flat-square&color=818cf8)&ensp;![Updated](https://img.shields.io/github/last-commit/Vineetsahoo/Quarto-Learning-Journey-?style=flat-square&color=6366f1&label=Updated)

`Technical Writing` &nbsp; `Data Science` &nbsp; `Python` &nbsp; `Reproducible Research`

A structured exploration of Quarto's full publishing stack — dynamic documents, interactive presentations, and data-driven reports generated from a unified source. Demonstrates reproducible research practices and multi-format scientific communication.

**Stack**
<img src="https://skillicons.dev/icons?i=python,html,jupyter" height="28"/>

**Engineering highlights**
- Single-source authoring compiled to HTML, PDF, and interactive Reveal.js slide decks
- Embedded live Python execution inside literate programming documents
- Structured as a progressive learning curriculum — beginner through advanced patterns
- Community-recognized resource with 2 GitHub stars

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2" width="100%"/>

<br/>

## GitHub Analytics

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=vineetsahoo&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" width="100%" alt="GitHub Trophies"/>

</div>

<div align="center">

<img height="172" src="https://github-readme-stats.vercel.app/api?username=vineetsahoo&show_icons=true&count_private=true&hide_border=true&title_color=6366f1&icon_color=818cf8&text_color=9ca3af&bg_color=0d1117" alt="GitHub Stats"/>
<img height="172" src="https://github-readme-streak-stats.herokuapp.com?user=vineetsahoo&theme=tokyonight&hide_border=true&background=0D1117&stroke=6366f1&ring=6366f1&fire=818cf8&currStreakNum=e2e8f0&sideNums=9ca3af&currStreakLabel=6366f1&sideLabels=9ca3af&dates=6b7280" alt="GitHub Streak"/>

</div>

<div align="center">

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=vineetsahoo&bg_color=0d1117&color=6366f1&line=818cf8&point=6366f1&area=true&area_color=6366f120&hide_border=true&custom_title=Contribution+Activity" alt="Contribution Activity"/>

</div>

<div align="center">

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vineetsahoo&layout=compact&hide_border=true&title_color=6366f1&text_color=9ca3af&bg_color=0d1117&langs_count=7" alt="Top Languages"/>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2" width="100%"/>

<br/>

## Open Source

```
GitHub Achievements

  Pull Shark x2        Merged meaningful pull requests across public repositories
  Pair Extraordinaire   Co-authored commits in collaborative development workflows
  Quickdraw            First issue or PR response within five minutes of opening
  YOLO                 Shipped and merged without hesitation
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2" width="100%"/>

<br/>

## Engineering Philosophy

```
What I optimize for — in order of priority:

  1. Correctness    Does it actually solve the right problem?
  2. Clarity        Can a new engineer understand it within ten minutes?
  3. Resilience     Does it degrade gracefully under failure?
  4. Performance    Does it hold under real-world load?
  5. Elegance       Is the architecture something worth being proud of?
```

> *The best engineers are also strong product thinkers. They understand why they are building, not just how.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2" width="100%"/>

<br/>

## Connect

<div align="center">

Open to **engineering internships**, **technical collaborations**, and **impactful open source work**.  
Building something serious in AI, cloud infrastructure, or modern web engineering — reach out.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vineet-sahoo-81b022311/)&ensp;
[![Portfolio](https://img.shields.io/badge/Portfolio-4F46E5?style=for-the-badge&logo=vercel&logoColor=white)](https://vineetsahoo.vercel.app/)&ensp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vineetsahoo3@gmail.com)&ensp;
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/VineetSaho63046)

<br/>

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=6,11,20&height=80&section=footer" width="100%"/>

<sub>Built with intention. Shipped with precision.</sub>

</div>
