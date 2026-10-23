<div align="center">

<img src="assets/profile-hero.svg" alt="Yuval Sigura — research-led engineering across AI, cybersecurity, robotics and software" width="100%" />

### I turn hard questions into systems you can build, test, and verify.

**Computer Science · AI Systems · Security Research · Robotics · Software Engineering**

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3200&pause=1200&color=00E5FF&center=true&vCenter=true&width=560&height=65&lines=Agents+cannot+authorize+themselves.;Evidence+%E2%89%A0+model+opinion.;Fail-closed.+Always." alt="Animated engineering principles: Agents cannot authorize themselves; Evidence is not model opinion; Fail-closed, always." width="560" />

[**Explore my work ↓**](#featured-work) · [**Engineering approach**](#how-i-engineer) · [**Tech stack**](#technical-toolbox) · [**Connect**](#lets-connect)

</div>

---

## The short version

I'm **Yuval Sigura** — a computer science student, software developer, and independent technology researcher who enjoys working where **AI, cybersecurity, infrastructure, and physical systems meet**.

I don't just explore how a system *could* work. I like building the prototype, defining the failure modes, writing the tests, and finding out **what the evidence actually supports**.

My public work ranges from a research archive for understanding vulnerability discoveries to a controlled SaaS security laboratory, an autonomous Jetson/ESP32 rover, local multi-agent coordination software, and an interactive study application.

**What connects these projects:** turning ambitious ideas into inspectable engineering — with clear authorization, observable behavior, and honest limits on what has been proven.

## Featured work

<sub>SELECTED PUBLIC PROJECTS · REAL CODE, DOCUMENTATION, AND TESTABLE ARTIFACTS</sub>

### 🔬 [Research Discovery Lab](https://github.com/YuvalSigura/Research-Discovery-Lab) — Reconstructing how discoveries happen

**The question:** Can we learn from the *investigative decisions* behind a security finding, not just its final exploit?

**The engineering:** A Python research archive with typed records, source provenance, validation, deterministic retrieval, chronology, and question-first analysis. It distinguishes observed evidence from reconstructed or inferred reasoning.

**What to inspect:** [Research methodology and verified status](https://github.com/YuvalSigura/Research-Discovery-Lab#verified-project-status) · [Archive validation CI](https://github.com/YuvalSigura/Research-Discovery-Lab/actions)

`Python` · `Research infrastructure` · `Evidence modeling` · `Validation`

### 🛡️ [HELIOS](https://github.com/YuvalSigura/HELIOS) — A security lab where an agent cannot grade itself

**The question:** How do you know whether an autonomous Web/API security investigation actually succeeded?

**The engineering:** A deliberately vulnerable, **local-only**, multi-tenant SaaS testbed. FastAPI, PostgreSQL, Redis, a background export worker, object storage, and an **independent operator oracle** provide a realistic workflow and a way to check actual outcomes.

**What to inspect:** [Architecture, boundaries and validation status](https://github.com/YuvalSigura/HELIOS)

`FastAPI` · `PostgreSQL` · `Redis` · `Docker` · `Security testing`

### 🤖 [SpectraRover](https://github.com/YuvalSigura/autonomous_robot) — Taking software into the physical world

**The question:** How can autonomous navigation remain predictable when software controls real motors?

**The engineering:** A Jetson Orin Nano / ESP32 rover stack with mecanum kinematics, bounded serial motor commands, arming and watchdog behavior, camera calibration, ArUco perception, route control, and deterministic tests.

**Reality check:** The pre-RF software is implemented and CI-tested; some chassis-specific electrical and physical integration checks remain.

`Jetson Orin Nano` · `ESP32` · `Python` · `OpenCV` · `Embedded control`

### 🔗 [ONE](https://github.com/YuvalSigura/one) — Coordinating AI tools without surrendering control

**The question:** How can multiple developer agents collaborate while keeping tasks, approvals, and execution accountable?

**The engineering:** A local MCP coordination layer using persistent SQLite state, task/event records, approved CLI workers, Git worktrees, and offline tests. Its documented boundaries explicitly distinguish coordination from an operating-system security boundary.

**What to inspect:** [Implemented features and integration limits](https://github.com/YuvalSigura/one)

`Python` · `MCP` · `SQLite` · `Agent tooling` · `Workflow engineering`

---

## Also worth exploring

**🔍 [Train Ticket — Security Assessment](https://github.com/YuvalSigura/train-ticket-Analysis-Report)**  
A public, sanitized penetration-testing report covering Web/API analysis, validated findings, risk, evidence, and remediation guidance. A look at how I document security work, not just how I test.

**📚 [Exam Recall — Live web app](https://yuvalsigura.github.io/)** · [Source](https://github.com/YuvalSigura/yuvalsigura.github.io)  
A Hebrew study application with active recall, weak-topic practice, and local progress tracking. A working user-facing product alongside the research and infrastructure projects.

**Other public explorations:** [C#/.NET binary analysis tooling](https://github.com/YuvalSigura/PuaSuiteClean) · [Wi-Fi CSI sensing resources](https://github.com/YuvalSigura/esp-csi). Check individual repositories for original upstream attribution, scope, and maturity.

## What I bring to an engineering team

| Strength | What that looks like in practice |
|:--|:--|
| **Research discipline** | Turning uncertainty into explicit questions, source-backed records, and testable hypotheses |
| **Security-minded design** | Authorization boundaries, negative controls, fail-safe behavior, and independent outcome checks |
| **Cross-layer engineering** | Moving between Python services, APIs, local infrastructure, microcontrollers, and physical platforms |
| **Ownership of the whole loop** | Architecture, implementation, test cases, documentation, and evaluation — not just a demo |

I'm particularly interested in **AI systems engineering, security R&D, backend/platform engineering, and autonomous systems**.

## How I engineer

<div align="center">

### Models propose. Systems authorize. Evidence decides.

*“How do you know that happened?”*

</div>

A useful result has to survive contact with reality. In my projects, that means separating what a model says from what a test, artifact, or physical observation can establish.

<details>
<summary><strong>▶ See the evidence-first development loop</strong></summary>

```mermaid
flowchart LR
    Q["Question"] --> M["Model assumptions"]
    M --> B["Build / experiment"]
    B --> O["Observe"]
    O --> V{"Evidence supports it?"}
    V -->|"Yes"| D["Document & validate"]
    V -->|"Not yet"| U["Preserve uncertainty"]
    U --> M
```

**My rule:** implemented ≠ tested ≠ validated in the intended environment. A roadmap item isn't an achieved result.

</details>

## Technical toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cs,c,javascript,html,css,docker,linux,git,github,vscode&perline=11" alt="Selected tools and programming languages" />

</div>

<details>
<summary><strong>▶ Open the full technology and research map</strong></summary>

| Domain | Tools and areas |
|:--|:--|
| **Software / backend** | Python, C, C#, .NET, JavaScript, Web APIs, local services, SQLite, PostgreSQL |
| **Infrastructure** | Linux, Windows, Docker, Git, GitHub Actions, CI/CD, automation |
| **Security** | Web/API assessment, penetration-testing methodology, OWASP, Burp Suite, Nmap, SAST/DAST concepts |
| **AI / research** | AI agents, model evaluation, machine learning, OpenCV, experiment design, benchmarks |
| **Robotics / embedded** | Jetson Orin Nano, ESP32, computer vision, sensor integration, motor control |
| **Signals / low-level** | Wi-Fi CSI sensing, signal analysis, OS internals, binary inspection, reverse-engineering research |

This is an overview of technologies used or explored across public work and broader engineering interests, not a claim that every area is equally mature.

</details>

## Beyond a single discipline

I like projects that connect ideas normally kept in separate boxes: **security research with scientific evidence, AI tooling with reliable infrastructure, and autonomy with low-level hardware control**.

The common theme isn't a particular framework. It's the habit of asking difficult questions, implementing useful systems, and verifying the results.

<details>
<summary><strong>▶ GitHub activity and language overview</strong></summary>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YuvalSigura&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E5FF&icon_color=00E5FF&text_color=c9d1d9" alt="GitHub activity statistics" width="100%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YuvalSigura&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E5FF&icon_color=00E5FF&text_color=c9d1d9" alt="GitHub language breakdown" width="100%" />

</div>

</details>

---

## Let's connect

Interested in **research-driven engineering, reliable AI, security systems, or robotics**? I'm open to engineering opportunities, technical discussions, and collaboration.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yuvalsigura)
[![GitHub](https://img.shields.io/badge/GitHub-Explore_my_code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YuvalSigura)

**Build with curiosity. Test with discipline. Publish what the evidence supports.**

</div>
