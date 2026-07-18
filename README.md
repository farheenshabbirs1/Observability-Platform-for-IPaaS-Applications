## Observability & Performace Monitoring Platform For Study Abroad Program, Monitorng Across 300+ institutes and 20+ Cities


Data storytelling dashboards for the **University of the Pacific – Office of Global Education** (Summer 2025). Visualizes Study Abroad participation across **Fall, Spring, Summer, and Faculty-Led Trips (2014–2025)** to inform decisions on **diversity, inclusion, and engagement**.

---

## Table of Contents
- [Overview](#overview)
- [Problem](#problem)
- [Users & Customer Needs](#users--customer-needs)
- [My Role](#my-role)
- [Design Process](#design-process)
- [Features](#features)
- [Impact](#impact)
- [User Interface](#screenshots)
- [Tech Stack](#tech-stack)
- [Run / View](#run--view)
- [Brand & Accessibility](#brand--accessibility)
- [Repository Structure](#repository-structure)
- [How This Maps to Amazon UX Internship Qualifications](#how-this-maps-to-amazon-ux-internship-qualifications)
- [Credits](#credits)
- [License](#license)

---

## Overview
The **Study Abroad Dashboard** provides a unified, interactive view of:
- participation by **term** (Fall, Spring, Summer, Faculty-Led),
- **gender** and **ethnicity** distribution,
- **majors** and **schools** sending students,
- **top countries** and destinations over time.

The dashboards were used in presentations to the **Dean of Global Admission** and multiple **school deans** to guide strategic outreach and program planning.

---

## Problem
Prior to this work, the Study Abroad office lacked:
- Centralized, presentation-ready reporting,
- Disaggregated insights by **gender, ethnicity, majors, and schools**,
- Clear, consistent visual hierarchy for leadership storytelling.

---

## Customer Requirements
**Primary users:** Study Abroad coordinators, deans, advisors.  
**Key needs:** quick trend scanning, trustworthy metrics, exportable visuals, and accessible presentation view for decision meetings.

---

## My Role
- **UX Designer & Data Visualization Engineer**  
- Researched user needs, designed wireframes, and built final dashboards.  
- Implemented visualizations in Tableau and embedded them via React.  
- **Trained supervisors and coordinators** on how to:  
  - Update the data source in the dashboard,  
  - Access and share published dashboard links,  
  - Use interactive filters to view data by **term** and **academic year**.  
- Delivered documentation and live demos to ensure the dashboards could be sustained and updated after my internship.  
- Worked in Agile sprints with weekly cross-team feedback from Study Abroad, Media & Design, and student testers.  

---

## Design Process
1. **Research & Discovery** – The design process began with a thorough research and discovery phase, where stakeholder interviews were conducted to understand the needs of staff, students, and decision-makers. Alongside these discussions, a detailed data audit was performed to evaluate the quality, structure, and relevance of the available datasets. This phase ensured that the project was grounded in both user expectations and reliable data sources.
  
2. **Ideation & Early Iterations** – Following the research phase, the project moved into ideation and early iterations. Low-fidelity chart sketches were created to explore different ways of presenting the information effectively, while Figma layouts were used to experiment with structure, hierarchy, and overall visual design. These early prototypes were tested and refined to improve clarity, labeling, and user flow before development began.
  
3. **Implementation** – During implementation, the finalized designs were translated into functional solutions using Tableau dashboards integrated with React-based embeds. Special attention was given to performance optimization, particularly when handling large category sets and complex visualizations. This stage focused on ensuring that the platform remained responsive, scalable, and user-friendly.

4. **Validation & Delivery** – The final stage involved validation and delivery. Usability checks were carried out with staff and students to confirm that the dashboards were intuitive and met practical needs. Based on this feedback, final refinements were made before the project was packaged and delivered, including a polished presentation deck prepared for deans and other academic stakeholders.

> **Brand Compliance:** Followed the official **University of the Pacific Brand Guidelines** for typography, spacing, color, and layout rhythm.
> 📄 Guidelines: https://www.pacific.edu/sites/default/files/users/user245/UPac_BrandGuidelines_Final_compressed.pdf

---

## Features
-  **Multi-term views:** Fall, Spring, Summer, Faculty-Led (2014–2025)
-  **Top Countries** per term and overall
-  **Diversity lenses:** Gender and Ethnicity
-  **Academic lenses:** Majors and UOP Schools
-  Clear visual hierarchy, consistent spacing/alignment, export-ready

---

## Impact
- Informed **diversity & inclusion** initiatives and outreach
- Improved leadership visibility and accountability for program goals
- Used in dean-level briefings; supports planning for future cohorts

---

## Dashboards
<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 10 47 AM" src="https://github.com/user-attachments/assets/60e05efb-f4e6-45fd-807a-be2b67b6d7c1" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 11 03 AM" src="https://github.com/user-attachments/assets/f3459a93-db2f-4942-8216-14e5248b42b4" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 11 21 AM" src="https://github.com/user-attachments/assets/b31c2453-171e-48b5-923b-4f861a2b938b" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 11 30 AM" src="https://github.com/user-attachments/assets/134ddd5e-a595-47e2-9f24-6e1435fa6fbf" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 11 46 AM" src="https://github.com/user-attachments/assets/dce02eb8-3aca-456f-b6d1-2938447775ea" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 11 56 AM" src="https://github.com/user-attachments/assets/9576a42c-3590-4249-a5c4-238275ffdfbb" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 12 03 AM" src="https://github.com/user-attachments/assets/1eb3a619-c513-4e8e-9951-571bbf13161c" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 12 09 AM" src="https://github.com/user-attachments/assets/eb5cd2ee-f0b7-4983-b8df-816ca8709412" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 12 17 AM" src="https://github.com/user-attachments/assets/c6e3bf3b-91ee-46b2-839b-2434879e5bf8" />
<br>

<img width="600" height="400" alt="Screenshot 2025-09-17 at 12 12 23 AM" src="https://github.com/user-attachments/assets/331a65d3-df98-4b93-8b01-3db4f63e297a" />
<br>


---

## Tech Stack
- **Visualization:** Tableau (primary), Python (pandas/matplotlib) for preprocessing
- **Frontend:** React, HTML, CSS (for embedding and layout)
- **Design:** Figma for wireframes
- **Workflow:** Agile sprints with weekly reviews

---

## Installation Setup
- Dashboards are deployed internally via **Tableau** and embedded in a React app.
  ```bash
  npm install
  npm run dev # or npm start

## Interactive Dashboards (Published)

You can explore the dashboards live on **Tableau Public** here:

1. **Overview by Major and UOP Schools**  
   -> [View Dashboard](https://public.tableau.com/app/profile/farheen.shaikh8731/viz/UOPSchoolandMajorParticipationsAnalysis/UOPSchoolsParticipation?publish=yes)

2. **Study Abroad Student Participation Analysis**  
   -> [View Dashboard](https://public.tableau.com/app/profile/farheen.shaikh8731/viz/StudentParticipationAnalysis/Studentsparticipation?publish=yes)

3. **Diversity & Inclusion Analysis**  
   -> [View Dashboard](https://public.tableau.com/app/profile/farheen.shaikh8731/viz/DiversityInclusionAnalysis/DiversityInclusion?publish=yes)
   
