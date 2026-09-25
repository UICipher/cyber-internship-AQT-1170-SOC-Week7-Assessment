# Week 7 SOC / Blue Team Assessment

**Student:** Muahmmad Umer Imran
**Student ID:** AQT-1170
**Program:** AstraQuantum Tech — Summer of Cybersecurity 2026
**Instructor / Mentor:** Muhammad Ehtisham

## Overview

This repository contains my Week 7 practical work on Security Operations Center fundamentals, Level 1 alert triage, log correlation, incident investigation, and defensive reporting. The work was completed only in the authorized TryHackMe and Blue Team Labs Online training environments.

## Completed Activities

### 1. TryHackMe — SOC Fundamentals

The room covered SOC roles, People/Process/Technology, detection versus response, alert handling, and a practical port-scanning alert. The completion evidence records seven completed tasks and 128 points.

Key learning: an L1 analyst must validate an alert with surrounding context, record the five Ws, and escalate when evidence or impact requires a higher level of investigation.

### 2. TryHackMe — SOC L1 Alert Triage

The room covered the event-to-alert workflow, severity and age-based prioritisation, assignment, investigation, verdicts, and closure or escalation. The completion evidence records six completed tasks and 80 points.

The primary case documented in the report is **Double-Extension File Creation**, a High-severity True Positive involving `cats2025.mp4.exe` from an untrusted domain.

### 3. Blue Team Labs Online — The Report II

This defensive challenge focused on SOC structure and operational improvement. The completed answers covered NOC/SOC/ICM, response options, the OODA Loop, distributed SOC design, the SOC Operations Lead, Deception and Insider Threat capabilities, and iLO/iDRAC technologies.

## Evidence

The `evidence/` directory should contain the original screenshots used in the report. Each image should retain its original platform context and should be accompanied by a short caption when used in a report or post.

Recommended evidence files:

- `soc-fundamentals-alert.png`

- `soc-fundamentals-completion.png`

- `soc-l1-priority.png`

- `double-extension-alert.png`

- `soc-l1-completion.png`

- `btlo-the-report-ii-scenario.png`

- `btlo-the-report-ii-answers.png`

- `btlo-the-report-ii-completion.png`

## Report

The full professional report is available as:

`AQT-1170_Muahmmad_Umer_Imran_SOC_Week7_Assessment.pdf`

The report includes the executive summary, scope, tools, learning summaries, alert investigation, 5 Ws, six-event timeline, evidence captions, severity and verdict rationale, impact, recommended response, assessment questions, and submission checklist.

## Investigation Note

The selected case was classified as a **High-severity True Positive** in the training environment. The filename `cats2025.mp4.exe` uses a misleading media extension before the executable extension, and the record identifies an untrusted download domain. The recommended next steps are to verify execution, collect the endpoint process tree, search the file hash across the environment, review DNS/proxy activity, and escalate if compromise or lateral movement is identified.

## Links

- TryHackMe SOC Fundamentals: [https://tryhackme.com/room/socfundamentals](https://tryhackme.com/room/socfundamentals)

- TryHackMe SOC L1 Alert Triage: [https://tryhackme.com/room/socl1alerttriage](https://tryhackme.com/room/socl1alerttriage)

- Blue Team Labs Online — The Report II: [https://blueteamlabs.online/home/challenge/the-report-ii-82ea7781c5](https://blueteamlabs.online/home/challenge/the-report-ii-82ea7781c5)

- LinkedIn post: **[Add the published LinkedIn URL here]**

## Academic Integrity

All screenshots in the evidence set were captured from my own practical activity in the authorized training platforms. The report is written in my own words and distinguishes observed evidence from recommended follow-up investigation. No production system or real organization was investigated.

## Author

**Muahmmad Umer Imran**
AQT-1170
Cybersecurity Intern — AstraQuantum Tech Summer of Cybersecurity 2026

**Mentor:** Muhammad Ehtisham
