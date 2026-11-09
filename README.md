<p align="center">
  <img src="./hero.svg" alt="Vineet Sahoo. I build the interface, and the pipeline under it." width="100%"/>
</p>

<p align="center">
  <a href="https://vineet-sahoo.netlify.app/"><b>PORTFOLIO</b></a> &nbsp;/&nbsp;
  <a href="#work"><b>WORK</b></a> &nbsp;/&nbsp;
  <a href="#stack"><b>STACK</b></a> &nbsp;/&nbsp;
  <a href="#activity"><b>ACTIVITY</b></a> &nbsp;/&nbsp;
  <a href="#contact"><b>CONTACT</b></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-0A0A0A?style=for-the-badge&labelColor=0A0A0A&color=C6FF3D&logoColor=white" alt="Frontend"/>
  &nbsp;
  <img src="https://img.shields.io/badge/AI%20Systems-0A0A0A?style=for-the-badge&labelColor=0A0A0A&color=ECE6D6&logoColor=white" alt="AI Systems"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Cloud%20%26%20DevOps-0A0A0A?style=for-the-badge&labelColor=0A0A0A&color=6B6B60&logoColor=white" alt="Cloud and DevOps"/>
</p>

<p align="center"><img src="./divider.svg" alt="" width="100%"/></p>

```typescript
const vineet = {
  role     : "Full-stack & DevOps engineer",
  base     : "Chennai, IST",
  domains  : [
    "Scalable Frontend Engineering",
    "AI-Powered Full-Stack Systems",
    "Cloud Infrastructure & DevOps",
  ],
  openTo   : ["Engineering Internships", "Technical Collaborations", "Open Source"],
};
```

> I build software that is technically sound, visually precise, and architecturally intentional.

I work across three layers that usually belong to different people: the interface, the AI behind it, and the infrastructure it ships on. Mora AI is the clearest example. A React dashboard on top, a Bedrock → Ollama → local model fallback chain in the middle, Terraform and EKS underneath.

<p align="center"><img src="./divider-ruler.svg" alt="" width="100%"/></p>

<a id="work"></a>
<img src="./section-work.svg" alt="01 Work" width="100%"/>

<br/>

<!-- ═══════════════ PROJECT 01 ═══════════════ -->

<table>
<tr>
<td width="53%" valign="top">

**[Mora AI: AI-Driven CI/CD RCA Platform](https://github.com/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard)**

<img src="https://img.shields.io/github/stars/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard?style=flat-square&color=C6FF3D&labelColor=0A0A0A&label=STARS" alt="Stars"/>&ensp;<img src="https://img.shields.io/github/languages/top/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard?style=flat-square&color=ECE6D6&labelColor=0A0A0A" alt="Top language"/>&ensp;<img src="https://img.shields.io/github/last-commit/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard?style=flat-square&color=6B6B60&labelColor=0A0A0A&label=UPDATED" alt="Last commit"/>

`DEVOPS` `AI / ML` `SAAS` `CLOUD`

Finds CI/CD pipeline failures, writes the root-cause analysis, and offers one-click remediation.

- **No single point of failure.** The AI layer falls back from AWS Bedrock Nova to Ollama to a local model.
- **Everything is code.** Terraform defines the VPC, EKS, ECR, Lambda, CloudWatch, and Bedrock IAM.
- **One command to ship.** Ansible, Terraform, and kubectl roll it out to EKS.
- **Observable by default.** Grafana dashboards are provisioned from the backend's live `/metrics`.
- **Gated CI.** `backend-check → frontend-build → api-smoke → sonar-scan → docker-build`

<img src="https://skillicons.dev/icons?i=react,ts,tailwind,nodejs,aws,docker,kubernetes,terraform&theme=dark" height="30" alt="Mora AI stack"/>

**[Read the repo →](https://github.com/Vineetsahoo/AI-Driven-CI-CD-RCA-Dashboard)**

</td>
<td width="47%" valign="middle" align="center">

<img width="1408" height="768" alt="Mora AI dashboard" src="https://github.com/user-attachments/assets/51a21597-e418-4b4b-9610-a331b031ff13" />

<br/><br/>

<img src="https://img.shields.io/badge/CI%2FCD-GitHub_Actions_%2B_Jenkins-0A0A0A?style=flat-square&logo=githubactions&logoColor=C6FF3D" alt="GitHub Actions and Jenkins"/>
<img src="https://img.shields.io/badge/IaC-Terraform-0A0A0A?style=flat-square&logo=terraform&logoColor=C6FF3D" alt="Terraform"/>
<img src="https://img.shields.io/badge/Platform-AWS_EKS-0A0A0A?style=flat-square&logo=amazonwebservices&logoColor=C6FF3D" alt="AWS EKS"/>

</td>
</tr>
</table>

<p align="center"><img src="./divider-commit.svg" alt="" width="100%"/></p>

<!-- ═══════════════ PROJECT 02 ═══════════════ -->

<table>
<tr>
<td width="47%" valign="middle" align="center">

<img width="1536" height="955" alt="GhostCred" src="https://github.com/user-attachments/assets/f6897982-0d74-46b1-b337-f3db187a8f4e" />

<br/><br/>

<img src="https://img.shields.io/badge/Security-Secret_Scanning-0A0A0A?style=flat-square&logo=shieldcheck&logoColor=C6FF3D" alt="Secret scanning"/>
<img src="https://img.shields.io/badge/CI%2FCD-GitHub_Actions-0A0A0A?style=flat-square&logo=githubactions&logoColor=C6FF3D" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/Observability-Prometheus_%2B_Grafana-0A0A0A?style=flat-square&logo=prometheus&logoColor=C6FF3D" alt="Prometheus and Grafana"/>

</td>
<td width="53%" valign="top">

**[GhostCred: Secret Leak Detector + Auto-Revoker for AI Dev Toolchains](https://github.com/Vineetsahoo/GhostCred)**

<img src="https://img.shields.io/github/stars/Vineetsahoo/GhostCred?style=flat-square&color=C6FF3D&labelColor=0A0A0A&label=STARS" alt="Stars"/>&ensp;<img src="https://img.shields.io/github/languages/top/Vineetsahoo/GhostCred?style=flat-square&color=ECE6D6&labelColor=0A0A0A" alt="Top language"/>&ensp;<img src="https://img.shields.io/github/last-commit/Vineetsahoo/GhostCred?style=flat-square&color=6B6B60&labelColor=0A0A0A&label=UPDATED" alt="Last commit"/>

`SECURITY` `DEVOPS` `AI TOOLCHAIN` `PYTHON`

Finds leaked secrets where AI coding agents leave them, then revokes them at the provider.

- **Scans the blind spots.** `claude_desktop_config.json`, `.cursor/mcp.json`, `.vscode/settings.json`, and shell history, which Gitleaks, TruffleHog, and detect-secrets don't cover.
- **Maps the blast radius.** A lineage graph follows a secret from origin file to Docker build log, CI log, test artifact, and git history.
- **Acts, not just alerts.** Once a secret is confirmed live, webhooks call the revocation API at GitHub, OpenAI, or Anthropic.
- **Guards every gate.** Pre-commit hook, GitHub Actions PR blocker, Docker pre-build guard, and a Prometheus and Grafana stack.
- **Tested.** 144 tests across 5 modules.

<img src="https://skillicons.dev/icons?i=python,docker,githubactions,prometheus,grafana&theme=dark" height="30" alt="GhostCred stack"/>

**[Read the repo →](https://github.com/Vineetsahoo/GhostCred)**

</td>
</tr>
</table>

<p align="center"><img src="./divider-dots.svg" alt="" width="100%"/></p>

<!-- ═══════════════ PROJECT 03 ═══════════════ -->

<table>
<tr>
<td width="53%" valign="top">

**[CardioVision AI: Healthcare ML System](https://github.com/Vineetsahoo/CardioVision-AI)**

<img src="https://img.shields.io/github/stars/Vineetsahoo/CardioVision-AI?style=flat-square&color=C6FF3D&labelColor=0A0A0A&label=STARS" alt="Stars"/>&ensp;<img src="https://img.shields.io/github/languages/top/Vineetsahoo/CardioVision-AI?style=flat-square&color=ECE6D6&labelColor=0A0A0A" alt="Top language"/>&ensp;<img src="https://img.shields.io/github/last-commit/Vineetsahoo/CardioVision-AI?style=flat-square&color=6B6B60&labelColor=0A0A0A&label=UPDATED" alt="Last commit"/>

`MACHINE LEARNING` `HEALTHCARE` `DATA SCIENCE` `PYTHON`

Turns patient diagnostic data into cardiovascular risk predictions.

- **Full pipeline.** Ingestion, EDA, feature engineering, training, and evaluation.
- **Compared, not assumed.** Several classifiers with cross-validation and hyperparameter tuning.
- **Readable results.** Visualizations of feature correlations and risk distributions.

<img src="https://skillicons.dev/icons?i=python,jupyter&theme=dark" height="30" alt="CardioVision stack"/>

**[Read the repo →](https://github.com/Vineetsahoo/CardioVision-AI)**

</td>
<td width="47%" valign="middle" align="center">

<img width="1408" height="768" alt="CardioVision AI" src="https://github.com/user-attachments/assets/77afce11-15a6-4192-aa57-cc03bbd6f040" />

<br/><br/>

<img src="https://img.shields.io/badge/Python-0A0A0A?style=flat-square&logo=python&logoColor=C6FF3D" alt="Python"/>
<img src="https://img.shields.io/badge/scikit--learn-0A0A0A?style=flat-square&logo=scikit-learn&logoColor=C6FF3D" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Jupyter-0A0A0A?style=flat-square&logo=jupyter&logoColor=C6FF3D" alt="Jupyter"/>

</td>
</tr>
</table>

<p align="center"><img src="./divider-pipeline.svg" alt="" width="100%"/></p>

<a id="stack"></a>
<img src="./section-stack.svg" alt="02 Stack" width="100%"/>

<br/>

<div align="center">

<table width="100%">
<tr>
<th align="center" width="37%">Frontend</th>
<th align="center" width="30%">Backend</th>
<th align="center" width="33%">Databases</th>
</tr>
<tr>
<td align="center">
<img src="https://skillicons.dev/icons?i=react" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=nextjs" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=ts" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=tailwind" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=js" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=html" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=css" width="44" height="44" style="margin:2px;"/>
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=nodejs" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=express" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=python" width="44" height="44" style="margin:2px;"/>
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=mongodb" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=mysql" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=postgres" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=supabase" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=firebase" width="44" height="44" style="margin:2px;"/>
</td>
</tr>
<tr>
<th align="center">Cloud & DevOps</th>
<th align="center">Languages</th>
<th align="center">Security & Observability</th>
</tr>
<tr>
<td align="center">
<img src="https://skillicons.dev/icons?i=aws" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=docker" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=kubernetes" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=openshift" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=terraform" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=ansible" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=jenkins" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=githubactions" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=linux" width="44" height="44" style="margin:2px;"/>
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=python" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=cpp" width="44" height="44" style="margin:2px;"/>
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=prometheus" width="44" height="44" style="margin:2px;"/>
<img src="https://skillicons.dev/icons?i=grafana" width="44" height="44" style="margin:2px;"/>
<img src="https://checkmarx.com/wp-content/uploads/2024/06/cropped-cx_favicon.webp" width="44" height="44" style="border-radius:9px; background:#0d1117; padding:8px; border:1px solid #30363d; object-fit:contain; vertical-align:middle; margin:2px;"/>
<img src="https://icon.icepanel.io/Technology/svg/SonarQube.svg" width="44" height="44" style="border-radius:9px; background:#0d1117; padding:8px; border:1px solid #30363d; object-fit:contain; vertical-align:middle; margin:2px;"/>
<img src="https://res.cloudinary.com/canonical/image/fetch/f_auto,q_auto,fl_sanitize,w_240/https%3A%2F%2Fdashboard.snapcraft.io%2Fsite_media%2Fappmedia%2F2024%2F02%2Ftrivy400x400.jpg.png" width="44" height="44" style="border-radius:9px; background:#0d1117; padding:6px; border:1px solid #30363d; object-fit:contain; vertical-align:middle; margin:2px;"/>
<img src="https://avatars.githubusercontent.com/u/29760937?s=280&v=4" width="44" height="44" style="border-radius:9px; background:#0d1117; padding:8px; border:1px solid #30363d; object-fit:contain; vertical-align:middle; margin:2px;"/>
<img alt="Bandit icon" src="https://github.com/user-attachments/assets/2476ee0d-dfb5-4296-a7b0-747d8e387e72" width="44" height="44" style="border-radius:9px; background:#0d1117; padding:8px; border:1px solid #30363d; object-fit:contain; vertical-align:middle; margin:2px;"/>
</td>
</tr>
</table>

</div>

<p align="center"><img src="./divider-signal.svg" alt="" width="100%"/></p>

<a id="activity"></a>
<img src="./section-activity.svg" alt="03 Activity" width="100%"/>

<br/>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Vineetsahoo&theme=dark&hide_border=true&background=0A0A0A&stroke=30363D&ring=C6FF3D&fire=C6FF3D&currStreakLabel=C6FF3D&sideNums=ECE6D6&currStreakNum=FFFFFF&sideLabels=8B949E&dates=8B949E&border_radius=8" alt="Vineet's GitHub Streak" />
</p>

<p align="center"><img src="./divider-segments.svg" alt="" width="100%"/></p>

<a id="contact"></a>
<img src="./section-contact.svg" alt="04 Contact" width="100%"/>

<br/>

<div align="center">

Open to **engineering internships**, **technical collaborations**, and **impactful open source work**.
Building something serious in AI, cloud infrastructure, or modern web engineering? Reach out.

<br/>

<p align="center">
<a href="https://www.linkedin.com/in/vineet-sahoo-81b022311/"><img src="https://img.shields.io/badge/LinkedIn-0A0A0A?style=flat-square&logo=linkedin&logoColor=C6FF3D" alt="LinkedIn"/></a>&ensp;
<a href="https://vineet-sahoo.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=flat-square&logo=vercel&logoColor=C6FF3D" alt="Portfolio"/></a>&ensp;
<a href="mailto:vineetsahoo3@gmail.com"><img src="https://img.shields.io/badge/Email-0A0A0A?style=flat-square&logo=gmail&logoColor=C6FF3D" alt="Email"/></a>&ensp;
<a href="https://x.com/VineetSaho63046"><img src="https://img.shields.io/badge/X%20%2F%20Twitter-0A0A0A?style=flat-square&logo=x&logoColor=C6FF3D" alt="X / Twitter"/></a>
</p>

<br/>

<img src="./divider-brackets.svg" alt="" width="100%"/>

</div>

<p align="center">
  <img src="./footer.svg" alt="Animated Kubernetes cluster where pods are killed and replaced while the service heartbeat stays alive. Pods die. The service doesn't." width="100%"/>
</p>
