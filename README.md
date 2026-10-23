<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=26&duration=2800&pause=900&color=7DD3FC&center=true&vCenter=true&width=700&lines=Agents+that+reason.;Systems+that+authorize.;Evidence+that+survives+scrutiny.;Boundaries+that+hold+under+failure." alt="Typing SVG" />

### Building systems where reasoning, authorization, and evidence stay separate

**I design and implement research and security infrastructure that treats models as proposers — not as authorities.**

</div>

---

## What I actually build

Most of the work is about the same problem from different angles:

how to let autonomous systems explore, form hypotheses, and propose actions  
**without** letting them authorize those actions, invent evidence, or declare success.

The recurring pattern in the code is deliberate separation of concerns:

- **Reasoning** — agents generate questions, plans, and candidate actions.
- **Authorization** — a separate plane decides what is actually allowed, under what policy, and with what budget.
- **Execution** — happens in controlled environments, with explicit artifacts.
- **Evidence** — recorded independently. Claims are verified against real outputs, not against the model’s report.
- **Verification** — fail-closed. Missing evidence, ambiguous provenance, or policy violation blocks progress rather than being smoothed over.

This shows up in authorized security research systems, controlled laboratories for evaluating agents, research-reconstruction engines, and experiments that touch physical platforms. The common thread is not the domain — it is the refusal to collapse the boundary between “the model said so” and “we can prove it happened.”

## Selected public work

| Project | What it is trying to do |
|---------|--------------------------|
| **[Research Discovery Lab](https://github.com/YuvalSigura/Research-Discovery-Lab)** | Reconstruct the questions and decision points that produced discoveries, with explicit uncertainty and provenance. |
| **[HELIOS](https://github.com/YuvalSigura/HELIOS)** | A local multi-tenant lab where an independent oracle checks real artifacts and audit trails instead of trusting an agent’s summary. |
| **[SpectraRover](https://github.com/YuvalSigura/autonomous_robot)** | Edge robotics with fail-safe low-level control separated from higher-level planning. |
| **[Exam Recall](https://github.com/YuvalSigura/yuvalsigura.github.io)** | Small public tool for active-recall practice. |

## How the code tends to look

- Agents do not own the scheduler, the policy engine, or the proof store.
- Actions that can affect a target go through an explicit authorization check.
- Evidence records are distinct from model outputs.
- Failures, negative results, and “not tried” are preserved rather than rewritten into success stories.
- Experiments are designed so that verification can happen without trusting the component under test.

## Current focus

Extending the same separation of concerns into longer-running research loops, better evaluation of autonomous investigators, and tighter coupling between controlled digital labs and physical sensing platforms — always with the constraint that the system must be able to say “we do not yet have evidence for that.”

---

<div align="center">

**Models propose. Systems authorize. Evidence decides.**

</div>
