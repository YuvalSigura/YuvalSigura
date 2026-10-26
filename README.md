<div align="center">

<img src="assets/profile-hero-wave.svg" alt="Yuval Sigura — research, build, verify. AI systems, security, robotics and software engineering." width="100%" />

### Building intelligent systems. Breaking assumptions. Connecting code to the real world.

**Cybersecurity Research · AI & Agent Systems · Robotics & Embedded Engineering**  
**Software Development · Automation · Creative Hardware**

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3200&pause=1200&color=16E8F0&center=true&vCenter=true&width=680&height=64&lines=Agents+cannot+authorize+themselves.;Evidence+%E2%89%A0+model+opinion.;Fail-closed.+Always." width="100%" alt="Animated engineering principles: Agents cannot authorize themselves; Evidence is not model opinion; Fail-closed, always." />

<p>
  <a href="https://profile.hackthebox.com/profile/019f54a9-17f3-71dd-b2d1-e8a20d17b4b7"><img src="https://img.shields.io/badge/Hack%20The%20Box-Achievements-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=111927" alt="Hack The Box achievements"/></a>
  <a href="https://github.com/YuvalSigura/Research-Discovery-Lab"><img src="https://img.shields.io/badge/Explore-Research%20Code-0D91AC?style=for-the-badge&logo=github&logoColor=white" alt="Explore research code"/></a>
  <a href="https://yuvalsigura.github.io/"><img src="https://img.shields.io/badge/Try-Live%20App-5569DC?style=for-the-badge&logo=githubpages&logoColor=white" alt="Try the live Exam Recall app"/></a>
</p>

<img src="https://skillicons.dev/icons?i=python,javascript,cs,c,html,css,docker,linux,git,github,vscode&perline=6" alt="Programming languages and tools: Python, JavaScript, C sharp, C, HTML, CSS, Docker, Linux, Git, GitHub, VS Code" />

<p>
<a href="#featured-work"><strong>Projects</strong></a> ·
<a href="#hack-the-box-achievements"><strong>HTB</strong></a> ·
<a href="#audio-meets-hardware"><strong>DIY guitar effects</strong></a> ·
<a href="#technical-toolbox"><strong>Toolbox</strong></a> ·
<a href="#lets-connect"><strong>Connect</strong></a>
</p>

</div>

---

## The short version

I'm **Yuval Sigura** — a computer science student, developer, and independent technology researcher working at the intersection of **cybersecurity, AI systems, software engineering, and hands-on hardware**. I build research infrastructure, controlled security environments, robotics software, useful web applications, and even Python guitar effects controlled by a physical pedal.

I don't just explore how a system *could* work. I like building the prototype, defining the failure modes, writing the tests, and finding out **what the evidence actually supports**.

My public work ranges from a research archive for understanding vulnerability discoveries to a controlled SaaS security laboratory, an autonomous Jetson/ESP32 rover, local multi-agent coordination software, and an interactive study application.

**What connects these projects:** turning ambitious ideas into inspectable engineering — with clear authorization, observable behavior, and honest limits on what has been proven.

## More than one discipline

My interests aren't separate boxes. They reinforce each other:

| Side of me | How it shows up |
|:--|:--|
| **🔬 The researcher** | I turn open questions into experiments, evaluation methods, and evidence-backed explanations. |
| **🛡️ The security thinker** | I look for broken assumptions, trust-boundary failures, and ways to prove whether a system behaves as intended. |
| **🧠 The AI / systems builder** | I design tools, APIs, autonomous workflows, and infrastructure where reliability matters as much as functionality. |
| **🤖 The hands-on maker** | I connect software with motors, cameras, sensors, embedded devices, and the unpredictable physical world. |
| **🕹️ The interactive builder** | I enjoy building educational applications and programming projects that turn abstract concepts into something people can use and explore. |
| **🌐 The web product builder** | I build browser-based applications with interactive workflows, user interfaces, and local progress tracking. |
| **🎸 The audio tinkerer** | I build and use Python-based virtual guitar effects, including a setup controlled by an existing physical pedal. |

The goal isn't to be an expert in everything. It's to **connect disciplines intelligently**, learn fast, and carry a problem from curiosity through implementation to something demonstrable.

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

## Hack The Box achievements

[![Hack The Box profile](https://img.shields.io/badge/Hack%20The%20Box-View%20my%20profile-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=111927)](https://profile.hackthebox.com/profile/019f54a9-17f3-71dd-b2d1-e8a20d17b4b7)

I practice cybersecurity through Hack The Box Labs and Academy. Selected historical achievements:

- **Season 9:** Bronze, Silver, and Ruby achievement tiers (2025).
- **Grandmaster of Stealth:** machine-specific achievement for Infiltrator, not a global rank.
- **Just Another Brick in the Wall:** ten-machine ownership milestone.
- **Took The Spotlight:** machine achievement badge.
- **Starting Point:** completed the introductory tiers.

**Academy learning:** Footprinting, Nmap Deep Dive, Introduction to Vulnerability Assessment, Cross-Site Scripting (XSS), and Using the Metasploit Framework.

*These are previously documented milestones, not current rank or certification claims. For the latest visible activity, badges, and progress, visit [my HTB profile](https://profile.hackthebox.com/profile/019f54a9-17f3-71dd-b2d1-e8a20d17b4b7).*

---
## Audio meets hardware

**🎸 DIY virtual guitar effects and pedals — Python + physical control**

I built **my own virtual guitar effects/pedals in Python**, and I actually use them when playing. I also connected an **existing physical pedal to control the virtual effects**, bringing hands-on hardware interaction into a software-based guitar rig.

What I enjoy about this project is the crossover: **audio programming, real-world controls, and the same hardware-to-software thinking that draws me to robotics and embedded systems**.

The DIY effects and physical-pedal integration are working personal projects. I'd like to deepen the audio side over time, experimenting further when I have the opportunity. I haven't published a dedicated repository or technical breakdown for this build here.

This is distinct from the [open-source Neural Amp Modeler Plug-in](https://github.com/YuvalSigura/NeuralAmpModelerPlugin), which is another audio project I'd like to explore further; I do not claim authorship of that upstream plug-in.

## Interactive software and learning

My software interests extend beyond research infrastructure. I also enjoy building **useful interfaces, learning tools, and interactive programming projects**.

**📚 [Exam Recall](https://yuvalsigura.github.io/)** — A live, Hebrew-language browser application for active recall and exam preparation, with topic-focused exercises and local progress tracking. [Source code](https://github.com/YuvalSigura/yuvalsigura.github.io).

**🕹️ [Hacking Zone](https://github.com/YuvalSigura/hack2war)** — A C-based terminal codebreaking game that combines programming fundamentals, game logic, difficulty levels, and an interactive story.

**🌐 Application development** — These projects reflect my interest in front-end behavior, practical user experience, and taking software beyond a command line or research prototype.

**📖 Technical communication** — I also value clear engineering documentation: explaining what a system does, how to test it, and where its limitations begin.

## What I bring to an engineering team

| Strength | What that looks like in practice |
|:--|:--|
| **Research discipline** | Turning uncertainty into explicit questions, source-backed records, and testable hypotheses |
| **Security-minded design** | Authorization boundaries, negative controls, fail-safe behavior, and independent outcome checks |
| **Cross-layer engineering** | Moving between Python services, APIs, local infrastructure, microcontrollers, and physical platforms |
| **Ownership of the whole loop** | Architecture, implementation, test cases, documentation, and evaluation — not just a demo |
| **User-facing software** | Interactive educational projects, UI behavior, and designing for the person using the system |
| **Multidisciplinary curiosity** | Combining ideas from security, mathematics, AI, software, and robotics without confusing exploration with expertise |

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
| **Web & interactive applications** | HTML/CSS, JavaScript, browser state, interactive study tools, UI behavior, educational software |
| **DIY audio & physical controls** | Python guitar effects, virtual pedals, physical-pedal input integration; deeper audio/DSP work remains an area to explore |

This is an overview of technologies used or explored across public work and broader engineering interests, not a claim that every area is equally mature.

</details>

## The common thread

I like projects that connect ideas normally kept in separate boxes: **security research with scientific evidence, AI tooling with reliable infrastructure, autonomy with embedded hardware, music with physical-to-digital controls, and complex engineering with practical user-facing software**.

A research archive, security lab, robot, and interactive learning application solve different problems. What connects them is curiosity, careful experimentation, and the willingness to revise an implementation when the evidence calls for it.

<details>
<summary><strong>▶ GitHub activity and language overview</strong></summary>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YuvalSigura&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E5FF&icon_color=00E5FF&text_color=c9d1d9" alt="GitHub activity statistics" width="100%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YuvalSigura&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E5FF&icon_color=00E5FF&text_color=c9d1d9" alt="GitHub language breakdown" width="100%" />

</div>

</details>

---

## Let's connect

Interested in **AI systems, security research, software engineering, robotics, interactive applications, or an unusual intersection between them**? I'm open to engineering opportunities, technical discussions, and collaboration.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yuvalsigura)
[![GitHub](https://img.shields.io/badge/GitHub-Explore_my_code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YuvalSigura)
[![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-Security%20profile-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=111927)](https://profile.hackthebox.com/profile/019f54a9-17f3-71dd-b2d1-e8a20d17b4b7)

**Build with curiosity. Test with discipline. Publish what the evidence supports.**

</div>
