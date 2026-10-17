## Clayton: building security tools with agents

My teams don't need to wait for vendors to ship the tooling they need. With agents, one practitioner can build in days what used to take a team a quarter. I use agents to build security tools and automate security work, then publish what works, what breaks, and how to do it safely.

The harder part is people, not code. I lead my teams through this shift: building the skills, habits, and guardrails that let a whole team work this way, so it scales beyond one person with a good prompt.

### What I'm exploring

- **Agents as security engineers:** building detection, triage, hardening, and reporting tooling with Claude Code and the Agent SDK
- **Automating the boring stuff with agents, not scripts:** the repetitive work that eats a security team's week (updates, reporting, routine checks) handed to agents that can adapt when things change, so people spend their time on judgment
- **Security operations run by agents:** briefings, evidence gathering, and routine checks handled automatically, with humans on the judgment calls
- **Verification over vibes:** validators and evals so claims about a tool or control can be checked
- **Leading my teams into it:** playbooks, working patterns, and training that move a security team from "AI-curious" to shipping with agents
- **Governance that enables:** permission models, sandboxing, and baselines so agents get adopted safely and quickly, so the answer is "yes, here's how" instead of "not yet"

### Work in the open

**[Claude Enterprise Control Baseline](https://github.com/ClaySecAI/claude-enterprise-control-baseline)**
Setting-level controls for Claude across web, desktop, and CLI. Built to show the approach end to end: CI that validates its own claims against primary sources, and a weekly watcher that flags upstream drift. It exists because no vendor or standards body had published one yet.

**[WinLogs](https://github.com/ClaySecAI/WinLogs)**
A one-command logging setup for malware, DFIR, and detection-engineering labs. It began as a Windows 7-era PowerShell script. One task to Claude, "modernize," took it to current Windows, dropped the legacy LocalGPO dependency, added CI that needs no live lab, and extended it to Linux and macOS. The lesson for my teams: give an agent a clear outcome, and make automated tests the thing you trust.

**Coming next: automating the boring stuff.** A collection of agent-driven automations for the repetitive work, built to be adapted by other teams. Published here once it's ready to share.

More tools and write-ups coming here as they're ready to share.

### Talk to me

Building security tooling with agents, or trying to roll AI out without losing control of it? Open an issue on the baseline or find me on [LinkedIn](https://www.linkedin.com/in/clayton-darnell).

---

*Views and projects here are my own. They do not represent my employer, past or present, and contain no employer data.*
