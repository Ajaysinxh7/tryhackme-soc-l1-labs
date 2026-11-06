# TryHackMe SOC Level 1: Lab Write-ups

> Documenting my hands-on journey to becoming a **SOC (Security Operations Center) Analyst**, one lab at a time.

---

## 👋 About Me

I'm **Ajay Singh**, a B.Tech Computer Science (AI/ML) student at LNCT Group of Institutions, Bhopal (graduating 2027), with a diploma in Computer Science and Engineering. I'm aiming for an **entry-level SOC Analyst (L1)** role, working on security monitoring, alert triage, and incident response.

Alongside my degree I've completed:

- Cisco AICTE Virtual Internship (2025)
- Deloitte Cyber Job Simulation (2025)
- Google Foundations of Cybersecurity (2024)

I'm also building practical skills with **SIEM tools such as Splunk and Wazuh**. This repo is where I show the practical side of that work.

---

## 🎯 What Is This Repository?

This repo is a **public lab journal** for TryHackMe's **SOC Level 1** learning path. For every room I complete, I publish a write-up with:

- A summary of what the room teaches
- Screenshots of my work in the simulated SOC environment
- The analyst reports and verdicts I wrote
- Key takeaways and what I'd do better next time

Flags and answer keys are **redacted on purpose**. The goal is to document *how I think and work*, not to share answers.

## ❓ Why Am I Doing This?

1. **Proof of practical skill.** A certificate says I finished a course. A write-up shows *what I actually did*: investigated alerts, made verdicts, wrote reports, and escalated.
2. **Hands-on, job-like practice.** The SOC L1 path uses simulated SIEM dashboards, alert queues, and escalation workflows that mirror what an L1 analyst does on shift. It's practice for the day-to-day work, though it isn't a substitute for a real job.
3. **Learning by explaining.** Writing a lab up in my own words forces me to understand it properly. I even rewrite my own reports when I spot weaknesses.
4. **A portfolio recruiters can verify.** Every claim on my resume (alert triage, incident reporting, escalation, phishing analysis) links to a lab in this repo where the work can be seen.

---

## 📚 Labs Completed

| # | Module | Room | Status |
|---|---|---|---|
| 1 | SOC Team Internals | [SOC L1 Alert Reporting](soc-team-internals/soc-l1-alert-reporting/README.md) | ✅ Completed |

*(New rows are added as I finish each room.)*

---

## 🧠 What I Learned, Lab by Lab

### 1. SOC L1 Alert Reporting
**What it is:** The room teaches what an L1 analyst does *after* triaging an alert: documenting it, handing it off, and communicating about it.

**What I did:**
- Worked in a simulated SIEM dashboard: assigned alerts to myself, moved them to *In Progress*, and set verdicts
- Investigated a **phishing email** (spoofed Microsoft sender, failed SPF and DKIM, suspicious `.rar` attachment) and a **data-leak alert** (HR spreadsheet shared to an external address)
- Wrote alert reports using the **Five Ws** (Who, What, When, Where, Why)
- Practised **escalating to L2** with the right assignee, verdict, and comment
- Analysed a **suspected web shell** on an Exchange server (an IIS process spawning a reverse shell and running AD discovery commands)
- Studied SOC communication scenarios: unresponsive L2, compromised chat channels, alert floods, and admitting mistakes early

**Skills gained:** alert reporting · escalation workflow · phishing analysis · Windows process-chain analysis · MITRE ATT&CK mapping · SOC communication

[**→ Read the full write-up**](soc-team-internals/soc-l1-alert-reporting/README.md)

*More labs will appear here as I complete them.*

---

## 🛠️ Skills Demonstrated So Far

| Skill | Where it's shown |
|---|---|
| Alert triage and verdicts (TP/FP) | Alert Reporting |
| Incident reporting (Five Ws) | Alert Reporting |
| Escalation to L2 | Alert Reporting |
| Phishing analysis (SPF/DKIM, attachments) | Alert Reporting |
| Process-chain and web shell analysis | Alert Reporting |
| MITRE ATT&CK mapping | Alert Reporting |

---

## 🗂️ Repo Structure

```
tryhackme-soc-l1-labs/
├── README.md                      ← you are here
└── <module-name>/
    └── <room-name>/
        ├── README.md              ← full write-up
        └── screenshots/           ← evidence, flags redacted
```

## ⚠️ A Note on Honesty

These labs are **simulated environments**, not production SOC work. I list them as *hands-on practice and training*, and I'm building toward real-world experience through internships and entry-level roles.

---

## 🔗 Connect

GitHub: [@Ajaysinxh7](https://github.com/Ajaysinxh7)

⭐ If you're also on the SOC L1 path, feel free to star the repo or open an issue with suggestions.