# Simulated Cybersecurity GRC Assessment — University of Melbourne

**Portfolio project | Work in progress | Workforce Identity & Access Management (IAM)**

> **Independent educational simulation — not an audit of the University of Melbourne.** This repository is not affiliated with, commissioned by, or endorsed by the University. It uses public-facing material for organisational context and explicitly hypothetical scenarios to demonstrate GRC methods. No internal University configurations, control effectiveness, risk ratings, or security weaknesses have been independently verified.

## Project overview

This portfolio demonstrates how a junior cybersecurity Governance, Risk and Compliance (GRC) analyst might scope a workforce IAM review, identify and document risks, plan evidence-based control assessments, and track follow-up actions. The case organisation is the University of Melbourne, chosen because it publishes relevant governance, security and privacy information.

**Assessment question:** How would a GRC analyst evaluate risks and controls relating to workforce account lifecycle, authentication, privileged access and access review, if appropriate internal evidence were available?

## Scope

**In scope (simulated):** workforce identities; staff and applicable contractor onboarding, changes and offboarding (joiner–mover–leaver); authentication and MFA; privileged access; periodic access reviews; workforce-related external access.

**Out of scope:** student identity lifecycle; Canvas LMS application security; clinical and research infrastructure security; general vulnerability management; and a real-world conclusion about the University's security posture. Public incidents may be discussed as background context, not evidence of workforce IAM control failures.

## Repository structure

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

## Deliverables

| Stage | Deliverable | Purpose | Status |
|---|---|---|---|
| 01 | [Organisation profile](01-Organisation-Scenario/Organisation-Profile.docx) | Describes organisational context and assessment boundary | Draft for review |
| 01 | [Source register](01-Organisation-Scenario/Source-Register.docx) | Tracks public references and verification notes | Draft; verification items remain |
| 01 | [Facts, assumptions and unknowns](01-Organisation-Scenario/Facts-Assumptions-Unknowns.docx) | Separates supported facts from simulation and evidence gaps | Draft for review |
| 02 | [Risk assessment methodology](02-Risk-Assessment/Risk-Assessment-Methodology.docx) | Defines likelihood, impact, scoring and evidence limitations | Draft for review |
| 02 | [Cyber risk register](02-Risk-Assessment/Cyber-Risk-Register.xlsx) | Illustrative workforce IAM risk scenarios and tracking | Illustrative, not verified findings |

The Word and Excel files are the primary working artifacts. GitHub may require downloading them to view all content, formulas and formatting.

## Assessment approach

1. **Establish context and scope.** Identify relevant systems, information, obligations and responsible functions from public sources.
2. **Classify information.** Keep public source claims, explicit project assumptions, unknowns and simulated evidence separate.
3. **Identify potential IAM risks.** Frame risks as plausible cause → event → consequence scenarios, not allegations of actual control failure.
4. **Assess risk consistently.** Use the documented 5×5 likelihood–impact method. Scores in the workbook are illustrative and are not ratings of the University's actual risk posture.
5. **Plan control verification.** Map relevant requirements and controls to evidence requests; evaluate design and operation only when sufficient evidence is available.
6. **Document remediation and reporting.** Record findings, owners, actions and status in future project stages using clearly labelled simulated records.

## Standards and frameworks

The project will use **selected, relevant ISO/IEC 27001:2022 Annex A controls**, with ISO/IEC 27002:2022 as guidance, and applicable aspects of the **Australian Essential Eight**. These are intended as assessment references, **not claims of University certification or compliance**. Detailed mapping and testing will be developed in the control-assessment stage.

## Evidence integrity and limitations

- **Public source claim:** cited organisational information, subject to the verification notes in the source register.
- **Project assumption:** a deliberate hypothetical choice used to make the exercise workable (for example, simulated Entra ID integration).
- **Unknown:** information that would require internal access or evidence, such as actual privileged-account MFA coverage.
- **Simulated evidence:** invented sample records for demonstrating testing; must be prominently labelled as simulated.
- **Potential risk:** a plausible scenario, not an established University weakness.

Do not interpret a published policy as proof that a control is implemented or operating effectively. Likewise, absence of public evidence does not establish control failure. Some source details and policy interpretations remain flagged for re-verification before the portfolio is considered final.

## Planned next stages

- `03-Control-Assessment/` — selected control mapping, evidence register and sample control tests.
- `04-Essential-Eight/` — scoped Essential Eight applicability and assessment.
- `05-Third-Party-Risk/` — simulated vendor intake and security assessment.
- `06-Remediation/` — corrective action and remediation tracker.
- `07-Executive-Reporting/` — management summary and dashboard.

These folders will be added as the corresponding deliverables are developed; they are **not completed work**.

## Reading order

Start with the organisation profile, then facts/assumptions/unknowns and source register. Read the risk methodology before opening the risk register, especially the workbook's **Read Me** and **Risk Matrix** tabs.

## Project status

**In progress (October 2026).** Initial context and risk-assessment artifacts exist; evidence-based control testing, validation, remediation and reporting are upcoming exercises.
