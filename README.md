# Hiring Funnel Drop-Off & Time-to-Hire Analysis

---

## Problem Statement

Organizations lose significant time and budget due to inefficient hiring pipelines. 
Recruiters often lack visibility into where candidates drop off across funnel stages 
and which factors drive longer time-to-hire. Without this insight, HR teams cannot 
prioritize process improvements or set data-driven SLA targets.

This project analyzes a simulated 5,000-record hiring dataset to answer three 
key questions:
- At which funnel stage do we lose the most candidates?
- Which departments have the lowest offer and acceptance rates?
- What factors predict time-to-hire, and by how much?

<img width="1164" height="643" alt="Screenshot 2026-04-07 163237" src="https://github.com/user-attachments/assets/a8d9ac52-84ac-423c-8694-0e71a325a8c9" />
<img width="1239" height="692" alt="Screenshot 2026-04-07 163326" src="https://github.com/user-attachments/assets/c4c026a1-15ef-4c38-9536-f6b85620cdff" />
<img width="1145" height="635" alt="Screenshot 2026-04-07 163342" src="https://github.com/user-attachments/assets/d85e024e-36e8-4066-831d-6d6d8445d1e6" />
<img width="948" height="663" alt="Screenshot 2026-04-07 163403" src="https://github.com/user-attachments/assets/10bbdb20-efc4-44c3-a2cc-f5b7c90c13af" />




---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python (Google Colab) | Data simulation & linear regression model |
| pandas, numpy | Data generation and manipulation |
| scikit-learn | Linear regression, train/test split, model evaluation |
| matplotlib | Regression scatter plot visualization |
| MySQL | Data storage and CTE-based SQL analysis |
| Power BI | Interactive dashboard and executive report |

---

## Dataset

- 5,000 simulated hiring records
- Fields: applicant_id, department, role_level, recruiter_id, application_date,
  last_stage, stages_passed, time_to_hire, offer_accepted
- 6 funnel stages: Applied → Screened → Phone Interview → 
  Technical Interview → Final Interview → Offer Extended
- 6 departments: Engineering, Sales, HR, Finance, Marketing, Operations
- 4 role levels: Junior, Mid, Senior, Lead
- 15 recruiters

---

## Project Structure
