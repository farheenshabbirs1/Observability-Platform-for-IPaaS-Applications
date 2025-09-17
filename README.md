> Data storytelling dashboards for the **University of the Pacific – Office of Global Education** (Summer 2025).  
> Visualizes Study Abroad participation across **Fall, Spring, Summer, and Faculty-Led Trips (2014–2025)** to inform decisions on **diversity, inclusion, and engagement**.

---

## Table of Contents
- [Overview](#overview)
- [Problem](#problem)
- [Users & Customer Needs](#users--customer-needs)
- [My Role](#my-role)
- [Design Process](#design-process)
- [Features](#features)
- [Impact](#impact)
- [Screenshots](#screenshots)
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

## Users & Customer Needs
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
1. **Research & Discovery** – stakeholder interviews; data audit.  
2. **Ideation & Early Iterations** – low-fi chart sketches and Figma layouts; tested hierarchy/labels.  
3. **Implementation** – Tableau dashboards + React embeds; performance passes on large category sets.  
4. **Validation & Delivery** – usability checks with staff/students; shipped presentation deck for deans.

> **Brand Compliance:** Followed the official **University of the Pacific Brand Guidelines** for typography, spacing, color, and layout rhythm.  
> 📄 Guidelines PDF: https://www.pacific.edu/sites/default/files/users/user245/UPac_BrandGuidelines_Final_compressed.pdf

---

## Features
- 📅 **Multi-term views:** Fall, Spring, Summer, Faculty-Led (2014–2025)
- 🌍 **Top Countries** per term and overall
- 🧑‍🤝‍🧑 **Diversity lenses:** Gender and Ethnicity
- 🎓 **Academic lenses:** Majors and UOP Schools
- 🧭 Clear visual hierarchy, consistent spacing/alignment, export-ready

---

## Impact
- Informed **diversity & inclusion** initiatives and outreach
- Improved leadership visibility and accountability for program goals
- Used in dean-level briefings; supports planning for future cohorts

---

## Screenshots
<img width="866" height="463" alt="Screenshot 2025-09-17 at 12 10 47 AM" src="https://github.com/user-attachments/assets/60e05efb-f4e6-45fd-807a-be2b67b6d7c1" />
<img width="892" height="280" alt="Screenshot 2025-09-17 at 12 11 03 AM" src="https://github.com/user-attachments/assets/f3459a93-db2f-4942-8216-14e5248b42b4" />
<img width="936" height="408" alt="Screenshot 2025-09-17 at 12 11 21 AM" src="https://github.com/user-attachments/assets/b31c2453-171e-48b5-923b-4f861a2b938b" />

<img width="939" height="487" alt="Screenshot 2025-09-17 at 12 11 30 AM" src="https://github.com/user-attachments/assets/134ddd5e-a595-47e2-9f24-6e1435fa6fbf" />
<img width="959" height="469" alt="Screenshot 2025-09-17 at 12 11 46 AM" src="https://github.com/user-attachments/assets/dce02eb8-3aca-456f-b6d1-2938447775ea" />

<img width="887" height="342" alt="Screenshot 2025-09-17 at 12 11 56 AM" src="https://github.com/user-attachments/assets/9576a42c-3590-4249-a5c4-238275ffdfbb" />
<img width="940" height="421" alt="Screenshot 2025-09-17 at 12 12 03 AM" src="https://github.com/user-attachments/assets/1eb3a619-c513-4e8e-9951-571bbf13161c" />

<img width="804" height="435" alt="Screenshot 2025-09-17 at 12 12 09 AM" src="https://github.com/user-attachments/assets/eb5cd2ee-f0b7-4983-b8df-816ca8709412" />

<img width="947" height="322" alt="Screenshot 2025-09-17 at 12 12 17 AM" src="https://github.com/user-attachments/assets/c6e3bf3b-91ee-46b2-839b-2434879e5bf8" />

<img width="915" height="298" alt="Screenshot 2025-09-17 at 12 12 23 AM" src="https://github.com/user-attachments/assets/331a65d3-df98-4b93-8b01-3db4f63e297a" />


<!--
![Fall & Spring Participation](./images/fall-spring.png)
![Summer & Faculty-Led](./images/summer-faculty.png)
![Gender Distribution](./images/gender.png)
![Ethnic Diversity](./images/ethnicity.png)
![Top Countries](./images/top-countries.png)
![Majors & Schools](./images/majors-schools.png)
-->
---

## Tech Stack
- **Visualization:** Tableau (primary), Python (pandas/matplotlib) for preprocessing
- **Frontend:** React, HTML, CSS (for embedding and layout)
- **Design:** Figma for wireframes
- **Workflow:** Agile sprints with weekly reviews

---

## Run / View
- Dashboards are deployed internally via **Tableau** and embedded in a React app.
  ```bash
  npm install
  npm run dev # or npm start
 
## Interactive Dashboards (Published)

You can explore the dashboards live on **Tableau Public** here:

1. **Overview by Major and UOP Schools**  
   👉 [View Dashboard](https://public.tableau.com/app/profile/farheen.shaikh8731/viz/UOPSchoolandMajorParticipationsAnalysis/UOPSchoolsParticipation?publish=yes)

2. **Study Abroad Student Participation Analysis**  
   👉 [View Dashboard](https://public.tableau.com/app/profile/farheen.shaikh8731/viz/StudentParticipationAnalysis/Studentsparticipation?publish=yes)

3. **Diversity & Inclusion Analysis**  
   👉 [View Dashboard](https://public.tableau.com/app/profile/farheen.shaikh8731/viz/DiversityInclusionAnalysis/DiversityInclusion?publish=yes)
   
