# Cybersecurity GRC Portfolio — University of Melbourne IAM Case Study

**Personal learning project | Work in progress | October 2026**

## Why I'm doing this project

I'm working towards my first role in cybersecurity Governance, Risk and Compliance (GRC).

My background is in mechanical engineering, and I've since completed a Certificate IV in Cyber Security and CompTIA Security+. I've also worked on hands-on cybersecurity projects, but I wanted to understand another side of security: how organisations identify risks, set security requirements, check whether controls are working, and follow up when improvements are needed.

Reading about frameworks and passing exams gave me a foundation, but I realised I couldn't yet confidently explain what a GRC analyst actually does with a risk register, a policy, an access review, or an evidence request in a real workplace. I started this project to close that gap and build something I can discuss honestly in a job interview.

This repository is both a **portfolio of my work** and a **record of what I'm learning as I work through it**. I expect to revise parts of it as my understanding improves.

## The project

I'm using the **University of Melbourne** as a real-world case organisation for a **simulated GRC assessment of workforce Identity and Access Management (IAM)**.

I chose a university because it has a large and changing population of staff, students, researchers and external collaborators. That makes access management an interesting area to examine. The University also publishes security, privacy and governance information that I can use to establish context without pretending I have access to its internal systems.

My central question is:

> If I were supporting a GRC assessment of workforce IAM, how would I identify the relevant risks, understand the requirements, request and assess evidence, document findings, and track improvements?

I'm focusing on staff and relevant contractor accounts: onboarding, changes of role, offboarding, MFA, privileged access and periodic access reviews. I'm **not** attempting to assess every University system or its overall cybersecurity posture.

> **Important:** This is an independent educational simulation, not an audit commissioned by or affiliated with the University of Melbourne. I do not have access to the University's internal systems, configuration records or control-testing evidence. Potential risks, sample records and risk ratings in this repository are hypothetical exercises, **not findings about the University**.

## How I'm approaching the work

I'm building the project in stages rather than trying to produce a finished report all at once:

1. **Understand the organisation.** Read publicly available policies, annual reports and security guidance to establish the context and decide what is in scope.
2. **Separate facts from assumptions.** Record what public sources support, what I am assuming for the simulation, and what would require internal evidence.
3. **Identify and assess risks.** Develop workforce IAM scenarios and apply a consistent likelihood-and-impact methodology. The initial scores are illustrative, not verified ratings of the University's risks.
4. **Connect risks to controls and frameworks.** Use selected relevant ISO/IEC 27001:2022 Annex A controls, ISO/IEC 27002 guidance and applicable Essential Eight strategies where appropriate.
5. **Practise evidence-based assessment.** Build clearly labelled sample evidence and test records to demonstrate how I would assess control design and operation.
6. **Document follow-up.** Develop remediation tracking and management reporting as later stages of the project.

The later stages are planned work, not completed assessments.

## How I'm Using AI in This Project

I'm using **ChatGPT and Google Gemini** as learning and research assistants throughout this project.

**ChatGPT** has helped me understand unfamiliar GRC concepts, break down assessment tasks, develop document structures, and work through practical examples. It has also helped prepare and organise some of the initial Word and Excel deliverables.

I've used **Google Gemini** mainly for research, particularly when gathering information about the University of Melbourne. It helped me find publicly available information about the University's size, authentication systems, security policies, governance, and other relevant areas. It also provided links to official sources that I could use to support and verify the information collected.

I'm being open about using these tools because I don't want to give the impression that I produced everything independently. However, my goal isn't simply to generate documents with AI. I'm using this project to learn how GRC work is actually carried out, understand the reasoning behind each assessment, and develop practical skills that I can apply in a real workplace.

I'm reviewing the materials, questioning assumptions, checking information against public sources, and working through the methodology to make sure I understand what I'm doing. Where information hasn't been fully verified, I intend to make that clear rather than present it as an established fact.

I see AI as a useful resource for learning, researching, and improving my work. But ultimately, **understanding the assessment, making informed decisions, and taking responsibility for what I publish are my responsibility.**

## What I've learned so far

These are the lessons I've worked through during the initial organisation research and project review:

- **A policy is not proof that a control works.** A published MFA requirement doesn't establish that every applicable account is covered or that enforcement worked throughout the review period.
- **A potential risk is not a confirmed finding.** For example, delayed removal of a departing employee's access is a valid risk scenario, but I cannot claim it has occurred at the University without evidence.
- **Evidence has to answer the question being tested.** A list of user permissions may show who has access, but it doesn't by itself prove that periodic access reviews took place.
- **The assessment boundary matters.** A university has many systems and risks; keeping this exercise focused on workforce IAM makes it possible to assess a defined area rather than produce a broad, unsupported report.
- **Being clear about unknowns is part of the work.** If internal configuration or access records aren't available, I should say that a control cannot be verified, not assume it is effective or ineffective.

I still have more to learn about practical control testing, ISO control mapping, risk treatment and reporting. I'll update this section as I complete those stages.

## Repository contents

```text
University-IAM-GRC-Portfolio/
├── README.md
├── 01-Organisation-Scenario/
│   ├── README.md
│   ├── Organisation-Profile.docx
│   ├── Source-Register.docx
│   └── Facts-Assumptions-Unknowns.docx
└── 02-Risk-Assessment/
    ├── README.md
    ├── Risk-Assessment-Methodology.docx
    └── Cyber-Risk-Register.xlsx
```

### Current working documents

| Document | What I'm using it for | Status |
|---|---|---|
| [Organisation Profile](01-Organisation-Scenario/Organisation-Profile.docx) | Establishing organisational context and the workforce IAM boundary | Draft |
| [Source Register](01-Organisation-Scenario/Source-Register.docx) | Tracking public sources and claims that need checking | Draft; some verification outstanding |
| [Facts, Assumptions and Unknowns](01-Organisation-Scenario/Facts-Assumptions-Unknowns.docx) | Keeping verified information separate from simulation and evidence gaps | Draft |
| [Risk Assessment Methodology](02-Risk-Assessment/Risk-Assessment-Methodology.docx) | Defining how likelihood, impact and risk scores are assigned | Draft |
| [Cyber Risk Register](02-Risk-Assessment/Cyber-Risk-Register.xlsx) | Working through illustrative workforce IAM risk scenarios | Draft; simulated ratings |

The Word and Excel files are working documents. Some details may be easier to inspect after downloading them from GitHub.

## What comes next

My next step is to review the risk assessment methodology and the scenarios in the risk register until I can explain how each rating was reached. After that, I'll develop a control assessment and evidence register, map relevant ISO and Essential Eight controls, practise testing with clearly labelled simulated evidence, and build remediation and reporting deliverables.

As those stages are completed, I'll add their folders and update this README with **what I did, what I found in the simulation, and what I learned**. I don't want to describe future work as if it's already finished.

## A note to anyone reviewing this portfolio

I'm not presenting myself as an experienced GRC practitioner. I'm using this project to make the transition into the field, practise the kind of work an entry-level analyst might support, and demonstrate how I think through risks, requirements and evidence.

If something in this repository is marked as simulated, assumed, unknown or awaiting verification, that distinction is intentional. I'd rather be clear about the limits of the work than make claims I can't support.
