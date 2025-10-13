# AIRTWIN — Market Questionnaire (v1.0)

## Questionnaire Design Template

**Notes:** Consider GDPR & PID/PII – discuss with inventors & supervisors under which umbrella this will be covered – By the **AIRTWIN TEAM** OR **ENTERPRISE TECH** OR **CAMBRIDGE UNIVERSITY**

### Identified Respondent Groups:
- Airlines (Operators)
- Engine OEMs
- MROs (Independent Maintenance Providers)
- Aircraft Lessors
- Insurers
- Regulators

---

**Purpose:** Capture decision-grade signal on exposure-linked maintenance needs, current tooling, and pilot appetite for AirTwin (exposure-aware predictive maintenance with confidence bands).

**Estimated time:** 6–9 minutes

**Scale anchors:** Likert-5 → 1 *Not at all* · 2 *Slightly* · 3 *Moderately* · 4 *Very* · 5 *Extremely*

---

## 0) Respondent Info

**Name:**  
*[Short answer]*

**E-mail:**  
*[Short answer]*

**Organization Name:**  
*[Short answer]*

**Job Title / Position:**  
*[Short answer]*

**Organization Type:**  
*[Dropdown: Airline/Operator · Engine OEM · MRO · Aircraft Lessor · Insurer · Regulator · Other]*

**Privacy note:** Individual responses are confidential and used only for product research and pilot design. Data will be processed in accordance with GDPR and applicable data protection regulations. No personally identifiable information (PII) will be shared without explicit consent.

---

## A) Current Maintenance Practice

### Q1. How frequently do you perform scheduled engine maintenance?
*Type: Multiple choice (single)*

- [ ] FH-based intervals
- [ ] FC-based intervals
- [ ] Calendar-based
- [ ] Condition-based
- [ ] Mixed (Other — please specify): _______________

### Q2. Main causes of unplanned maintenance or flight delays in the last 12 months (select up to 3)
*Type: Multiple choice (multi-select; cap = 3)*

- [ ] Hot-section wear
- [ ] LLP life variance
- [ ] FOD
- [ ] Icing
- [ ] Salt / sand
- [ ] De-icing chemicals
- [ ] Volcanic ash
- [ ] Air quality (NOx / SOx / PM)
- [ ] Parts / rotable shortage
- [ ] Other: _______________

### Q3. How is environmental exposure (dust, chemicals, ash, salt, etc.) currently monitored or recorded?
*Type: Multiple choice (multi-select)*

- [ ] Not monitored
- [ ] Manual tech-log notes
- [ ] Airport / NOTAM reports
- [ ] Onboard sensors / QAR / FOQA
- [ ] OEM portals
- [ ] Third-party data feeds
- [ ] Internal data lake
- [ ] Other: _______________

---

## B) Reliability & Cost

### Q4. Have you experienced reliability issues linked to weather/environment in the last 12 months?
*Type: Multiple choice (single)*

- [ ] Yes
- [ ] No

**If "Yes", answer Q4a and Q4b:**

#### Q4a. Approximate number of events (banded)
*Type: Multiple choice (single)*

- [ ] 1–2
- [ ] 3–5
- [ ] 6–10
- [ ] >10

#### Q4b. Typical AOG hours per event
*Type: Multiple choice (single)*

- [ ] <4
- [ ] 4–12
- [ ] 12–24
- [ ] >24

### Q5. How significant are maintenance-related costs or downtime for your operations?
*Type: Likert-5 (1–5)*

- [ ] 1 — Not at all
- [ ] 2 — Slightly
- [ ] 3 — Moderately
- [ ] 4 — Very
- [ ] 5 — Extremely

---

## C) Awareness & Technology Adoption

### Q6. How familiar are you with digital-twin / predictive-maintenance technologies?
*Type: Likert-5 (1–5)*

- [ ] 1 — Not at all
- [ ] 2 — Slightly
- [ ] 3 — Moderately
- [ ] 4 — Very
- [ ] 5 — Extremely

### Q7. Which predictive tools are currently in use? (select all that apply)
*Type: Multiple choice (multi-select)*

- [ ] Airbus Skywise
- [ ] Rolls-Royce Intelligent Engine
- [ ] GE/CFM portals
- [ ] In-house models
- [ ] Third-party PdM vendor
- [ ] Other(s) — please list: _______________

---

## D) Value & Pilot

### Q8. How valuable would confidence-based predictions (with uncertainty ranges) be for exposure-related maintenance?
*Type: Likert-5 (1–5)*

- [ ] 1 — Not at all
- [ ] 2 — Slightly
- [ ] 3 — Moderately
- [ ] 4 — Very
- [ ] 5 — Extremely

### Q9. Would you be interested in piloting a solution that quantifies exposure-related degradation?
*Type: Multiple choice (single)*

- [ ] Yes (0–3 months)
- [ ] Yes (3–6 months)
- [ ] Maybe — need more info
- [ ] Not now

### Q10. Which outcomes matter most? (select up to 2)
*Type: Multiple choice (multi-select; cap = 2)*

- [ ] Reduced downtime / AOG
- [ ] Cost predictability
- [ ] Extended on-wing time
- [ ] Safety margin improvement
- [ ] Sustainability / ESG reporting (CORSIA / EU ETS)

---

## E) Commercials

### Q11. Preferred commercial model for predictive tools
*Type: Multiple choice (single)*

- [ ] Per-engine / month (SaaS)
- [ ] Fleet-tier SaaS
- [ ] OEM-bundled
- [ ] Outcome / SLA-based
- [ ] Other: _______________

### Q12. Reasonable payback period for adoption
*Type: Multiple choice (single)*

- [ ] <6 months
- [ ] 6–12 months
- [ ] 12–24 months
- [ ] >24 months

---

## F) Open-Ended

### OE1 — Pain / Experience
*Type: Long answer (50–120 words)*

**Question:** Briefly describe the most costly or frustrating engine-maintenance issue you've faced recently.

*[Your answer here]*

---

### OE2 — Exposure Event
*Type: Long answer (50–120 words)*

**Question:** Describe one exposure-linked maintenance event in the last 12 months that materially impacted operations—what happened, suspected cause (dust/salt/chemicals/ash/icing), AOG hours/cost band, and what you wish you'd known two weeks earlier.

*[Your answer here]*

---

### OE3 — New Tech: Impact / Risk / Accuracy / Result
*Type: Short answer (list 2–3 items)*

**Question:** What proof point(s) would make AirTwin a must-have? (e.g., AOG ↓ ≥10% with ≤5% false alerts; on-wing ↑ ≥3 months; lead time ≥30 days; specific validation evidence).

*[Your answer here]*

---

## Optional Demographics (for segmentation)

**Region of operation:**  
*[Dropdown: Africa · APAC · Europe · LATAM · Middle East · North America]*

**Fleet size (if applicable):**  
*[Dropdown: 1–20 · 21–50 · 51–150 · 151–300 · 301+]*

---

## Form Logic & Clean-Data Conventions

- **Required:** Q1, Q2, Q3, Q5, Q6, Q7, Q8, Q9, Q10, Q11, Q12
- **Branching:** Q4 → show Q4a/Q4b only if "Yes"
- **Caps:** Q2 (max 3 selections), Q10 (max 2 selections)
- **Likert anchors:** 1 *Not at all* … 5 *Extremely*
- **Use banded values** (events/hours) to avoid free-text noise
- **Include "Other (specify)"** where listed

---

## Data Protection & Compliance

### GDPR Compliance Checklist:
- [ ] Lawful basis for processing identified (e.g., consent, legitimate interest)
- [ ] Data retention period defined
- [ ] Data processor agreement in place (if applicable)
- [ ] Respondent rights communicated (access, rectification, erasure, portability)
- [ ] Data security measures implemented
- [ ] Privacy policy/notice reviewed and approved
- [ ] DPO consultation completed (if required)

### PII/PID Handling:
- **Data collected:** Name, email, organization name, job title
- **Purpose:** Research and pilot program coordination
- **Storage:** [To be defined by AIRTWIN Team/Enterprise Tech/Cambridge University]
- **Access:** Limited to authorized research team members
- **Retention:** [To be defined based on institutional policy]
- **Anonymization:** Responses will be anonymized for analysis and reporting

### Consent Statement (to be included at survey start):
> "By completing this questionnaire, you consent to the collection and processing of your responses for research purposes related to the AIRTWIN project. Your data will be handled in accordance with GDPR and will not be shared with third parties without your explicit consent. You may withdraw your consent at any time by contacting [contact email]."

---

## Distribution & Implementation Notes

### Target Sample Size:
- Airlines/Operators: [X respondents]
- Engine OEMs: [X respondents]
- MROs: [X respondents]
- Aircraft Lessors: [X respondents]
- Insurers: [X respondents]
- Regulators: [X respondents]

### Distribution Channels:
- [ ] Direct email outreach
- [ ] Industry associations
- [ ] Conference/trade show participants
- [ ] LinkedIn professional networks
- [ ] Partner organizations

### Survey Platform Recommendations:
- Google Forms (free, GDPR-compliant with appropriate settings)
- Qualtrics (enterprise, robust compliance features)
- Microsoft Forms (institutional license)
- LimeSurvey (open-source, self-hosted option)

---

**Version:** 1.0  
**Last Updated:** 13-10-2025 
**Authored By:** Airtwin Team - Group 1
**Data Controller:** [AIRTWIN Team / Enterprise Tech / Cambridge University]
