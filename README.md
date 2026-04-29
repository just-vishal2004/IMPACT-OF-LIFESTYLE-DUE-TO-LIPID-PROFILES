# IMPACT-OF-LIFESTYLE-DUE-TO-LIPID-PROFILES
Statistical analysis of the LDL/HDL ratio in rural vs. urban India, revealing the "Rural Paradox"
Impact of Lifestyle on Lipid Profiles: A Rural-Urban Analysis
This repository contains the code, analysis, and final report for the B.E. research project, "Impact of Lifestyle on Lipid Profiles: A Rural-Urban Analysis," completed at Chandigarh University.

The project investigates the impact of modernization on cardiovascular risk by analyzing the LDL/HDL ratio in 4,015 individuals across North India. The core finding is the "Rural Paradox": rural populations now exhibit significantly higher atherogenic risk (mean ratio 3.52) compared to urban counterparts (mean ratio 2.73).

The goal of this research is to validate the LDL/HDL ratio as a low-cost, robust, and scalable biomarker for cardiovascular risk screening in public health programs.


🔑 Key Research Question
This study addresses the "Rural Paradox"—why are rural populations in India, traditionally presumed healthier, now showing higher cardiovascular risk markers than urban populations? 


The analysis attributes this to:


Mechanization of agriculture (e.g., tractors replacing manual labor).



Shift in diet from traditional coarse grains to refined carbohydrates and low-cost saturated fats.


Lack of healthcare infrastructure and awareness in rural areas compared to the urban "safety nets" of routine screening.


📊 Key Findings

Dataset: 4,015 anonymized lipid profile records.


Urban Cohort (New Delhi, Mohali): Mean LDL/HDL = 2.73 ± 0.58.


Rural Cohort (Patiala, Yamuna Nagar): Mean LDL/HDL = 3.52 ± 0.69.


Statistical Significance: The difference was highly significant (p < 0.001).


Core Result: Rural adults were found to be approximately 4.5 times more likely to have a high-risk ratio (> 3.5) than urban adults.

💻 Tech Stack & Tools
This project utilized the following tools for its analytical pipeline:


Core Statistical Analysis: R Studio v4.2.1.



R Packages: dplyr, tidyr (for data wrangling), ggplot2, plotly (for visualization), summarytools (for descriptive modeling).




Secondary Validation & Automation: Python 3.10 (with Pandas, Matplotlib).



Data Inspection: MS Excel 2021.



Visualization & Dashboards: Tableau Public / Power BI.




Version Control: Git / GitHub.



Schematic Design: Lucidchart & Draw.io.


📁 Repository Structure
The repository is organized based on the project's data flow architecture :

/project_lipid_rural_urban/
├── data_raw/         # Raw anonymized data (CSVs from districts)
├── data_clean/       # Processed datasets after filtering and validation
├── scripts_r/        # Modular R scripts (e.g., data_cleaning.R, ratio_calc.R)
├── results/          # Archived statistical outputs (p-values, tables, etc.)
├── visualizations/   # Generated boxplots, histograms, and heatmaps
├── reports/          # Final research paper and policy briefs
├── dashboard/        # Tableau/Power BI dashboard files
└── README.md         # You are here
🚀 How to Run & Replicate
To replicate the findings of this study:

Clone the repository:

Bash

git clone https://github.com/just-vishal2004/IMPACT-OF-LIFESTYLE-DUE-TO-LIPID-PROFILES.git
Install Dependencies:

Ensure you have R Studio (v4.2.1) and the required packages (dplyr, tidyr, ggplot2, cowplot, summarytools, psych) .



Ensure you have Python (v3.10) with pandas and matplotlib.


Run the Scripts:

Execute the R scripts in the scripts_r/ folder, starting with data_cleaning.R to process the raw data, followed by the analysis scripts.

The scripts will regenerate the figures and tables in the results/ and visualizations/ folders.

View the Dashboard:

Open the dashboard files located in the dashboard/ directory using Tableau Public or Power BI to interact with the visual data.

🎓 Academic Context
This project was submitted in partial fulfillment for the award of the degree of Bachelor of Engineering in Computer Science (IoT Specialization).



Author: Vishal Kumar (22BIT70052).


Supervisor: Er. Tejinder Pal Singh.



Institution: Chandigarh University, Department of AIT-CSE.
