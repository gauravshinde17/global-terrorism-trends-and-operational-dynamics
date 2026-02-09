# Global Terrorism Database (GTD) – Data Source Description

## Dataset Overview
This project uses data from the **Global Terrorism Database (GTD)**, an open-source database maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism (START).

The GTD records terrorist incidents worldwide from **1970 to 2020**, covering event-level information related to attack characteristics, location, targets, weapons, outcomes, and impact.

---

## Data Provider
- **Source**: Global Terrorism Database (GTD)
- **Maintained by**: START, University of Maryland
- **Accessed from**: Official GTD public release

---

## Temporal Coverage
- **Start Year**: 1970  
- **End Year**: 2020  

---

## Geographical Coverage
- Global coverage across all major regions and countries
- Location granularity includes region, country, and administrative areas where available

---

## Key Data Domains
The dataset contains structured information across multiple analytical dimensions, including:
- Incident timing (year, month, day)
- Geographic location
- Attack type and weapon type
- Target category
- Casualties (deaths and injuries)
- Incident outcomes and success status
- Reporting certainty and classification flags

---

## Data Usage in This Project
- The original raw dataset is **not stored in this repository** due to size constraints.
- Data was cleaned, normalized, and transformed using Python.
- The analysis focuses on **aggregated trends**, not individual incidents.
- Cleaned and processed datasets are stored in the `01_Dataset/02_Cleaned` directory.

---

## Ethical Considerations
This dataset represents real-world violence and human impact.  
All analyses are conducted at an aggregated level to avoid sensationalism, misinterpretation, or misuse of sensitive information.

---

## License & Attribution
The GTD is provided for research and educational use.  
Users of this repository should refer to the official GTD documentation for licensing and citation guidelines.
