# Holistic Overview of Patient Demographics, Billing, and Admission Trends

## Objective

This Tableau storyboard provides a comprehensive view of patient demographics, billing patterns, and hospital admission trends. It is designed to support healthcare managers, hospital administrators, and insurance analysts in understanding patient population characteristics, identifying high-cost conditions, and optimising resource allocation across admissions and insurance providers. By integrating patient-level, insurance, and medical condition data, the storyboard enables decision-makers to explore patterns, uncover cost drivers, and better understand patient care dynamics.

The storyboard is composed of three interconnected dashboards, each highlighting complementary aspects of healthcare analytics: demographics, billing, and admission analysis. Together, they create a holistic perspective of hospital operations, supporting strategic and operational planning.

---

## Tableau Public Link

🔗 [View the Storyboard on Tableau Public](https://public.tableau.com/app/profile/vipin.premkumar/viz/Task3Tableau-HolisticOverviewofPatientDemographicsBillingandAdmissionTrends/HolisticOverviewofPatientDemographicsBillingandAdmissionTrends)

---

## Data

- **Source**: [Kaggle Synthetic Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)  
- **Coverage**: Patient demographics, medical conditions, insurance providers, billing amounts, and admission types.  

**Preparation Steps:**

1. Standardised age bins and medical condition codes.  
2. Removed incomplete patient records and anonymised identifiers.  
3. Aggregated billing amounts by patient, condition, and admission type for accuracy.  
4. Calculated KPI measures such as average billing per admission, total billing, and dominant age group.  

This dataset was chosen for its comprehensiveness across multiple hospital metrics, ensuring the dashboards provide actionable insights for operational and financial planning.

---

## Dashboard Overview

### 1. Patient Demographics and Medical Insights

This dashboard provides a high-level understanding of the patient population and condition prevalence. It highlights **average patient age (54 years)**, the **most diagnosed medical condition (Obesity)**, and the **dominant age group (45–59 years)**. These KPIs contextualise the patient base and highlight priority areas for intervention.

The **Patient Breakdown by Gender and Age Bin** is a bar chart showing billing distribution for male and female patients across age bins (12, 24, 36, 48, 60, 72+). Hovering over the bars reveals the average length of stay, indicating which age groups consume the most resources. Middle-aged patients (45–59) emerge as the highest billing segment, suggesting targeted wellness or preventive programs could reduce financial burden.  

![Patient Demographics and Medical Insights](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Patient%20Demographic%20and%20Medical%20Insights%20Dashboard.jpg)  
![Patient Age Breakdown by Gender](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Breakdown%20by%20Gender%20Detail.jpg)

The **Patient Age Distribution** uses horizontal stacked bars to visualise case counts by gender for each age group, with hover details revealing admission type (elective, emergency, urgent). The concentration in the 49–59 age group reinforces that healthcare resources are predominantly consumed by middle-aged adults, highlighting the need for condition-specific care planning.

![Patient Age Distribution](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Age%20Distribiton%20Detail.jpg)

**Age-Related Variance by Insurance Provider** is presented via vertical box plots showing billing distribution across age groups for each provider. Medicare has the broadest distribution, indicating variability in cost per patient, while United Healthcare is more concentrated. Hovering displays average billing per age group, supporting cost variance analysis across insurers.

![Age-Related Variance in Healthcare Costs](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Age%20Related%20Variance%20Detail.jpg)

**Implication:** This dashboard allows administrators to identify patient groups driving the most billing and admissions, highlighting differences by gender, age, and insurance provider. It provides a foundation for targeted interventions, cost management, and strategic planning.

---

### 2. Billing Overview: Insurance, Admissions & Conditions

This dashboard focuses on financial performance and insurance-related patterns. KPIs include **average billing per admission (25K)**, **costliest condition (Hypertension)**, and **total billing amount (458M)**.

The **Billing Distribution by Insurance Provider** shows Medicare and Aetna dominating with 133M and 128M respectively. Hovering reveals gender splits, providing insights into patient composition across insurers.

![Billing Overview: Insurance, Admissions & Conditions](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Billing%20Overview%20Dashboard.jpg)  
![Billing Distribution Across Insurance Providers](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Insurance%20Providers%20Distribution%20Detail.jpg)

**Billing Overview by Medical Condition** uses bar charts with trend lines to show average billing per condition. Obesity and asthma top both total and average costs. Hovering shows age breakdowns, aiding condition-specific planning.

![Billing Overview by Medical Condition](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Billing%20Overview%20Detail.jpg)

The **Distribution of Patient Admission Types** is visualised with a pie chart showing elective, urgent, and emergency admissions. Elective cases dominate (37.8% of 6,700+ cases), with hover details showing age bin breakdown.  

**Implication:** This dashboard provides finance teams and administrators with insights on cost drivers, insurance impacts, and admission trends, enabling informed resource allocation and preventive care strategies.

---

### 3. Healthcare Billing and Admissions Analysis

This dashboard synthesises patient, billing, and admission data to guide actionable hospital management decisions. KPIs include **top insurance provider by billing (Medicare – 133M)**, **total admissions (18,000)**, and **top billed admission type (Elective)**.

**Billing Amount vs Patient Volume Comparison** shows medication-level billing totals (e.g., Aspirin highest at 25K average) with hover revealing number of cases, highlighting medications contributing most to expenditure.

![Healthcare Billing and Admissions Analysis](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Heahthcare%20Billing%20%26%20Admissions%20Dashboard.jpg)  
![Billing Amount and Patient Volume Comparison](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Billing%20Amount%20Patient%20Volume%20Detail.jpg)

**Medical Condition and Billing Amount by Admission Type** uses horizontal stacked bars to show billing for each condition by admission type. Asthma and Obesity dominate. Hovering provides number of cases per condition-admission combination, enabling disease-specific resource allocation and cost control.

**Billing Distribution by Admission Type** employs donut charts for elective, urgent, and emergency admissions. Inner circles show total billing, while hover details display insurance breakdown percentages.

![Billing Distribution by Admission Type](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Admission%20Distribution%20Detail.jpg)

**Implication:** By combining admissions, conditions, and billing metrics, this dashboard equips decision-makers to optimise financial performance, identify high-cost patient segments, and support strategic operational planning.

---

## Visualisation Design Choices

The storyboard is tailored for hospital administrators, finance managers, and healthcare analysts. It uses a **neutral colour palette with blue and orange accents**, and features bar charts, stacked bars, box plots, pie charts, donut charts, and trend lines. Interactive elements include hover tooltips, drill-downs by age, gender, condition, and insurance provider, and navigation linking the three dashboards for a cohesive overview from demographics to billing to admissions.

---

## Key Takeaways

- Middle-aged patients (45–59) drive both admissions and billing, suggesting focus areas for care management.  
- Obesity and asthma are the highest cost conditions, highlighting preventive program opportunities.  
- Medicare and Aetna dominate total billing, demonstrating insurance-driven financial exposure.  
- Elective admissions, while high in volume, also carry significant billing implications, necessitating careful capacity and cost management.  
- Detailed breakdowns by gender, age, insurance, and admission type provide actionable insights for planning, allocation, and optimisation.

---

## Strategic Implications

This storyboard enables hospitals and healthcare organisations to:

- Identify high-cost patient groups and conditions.  
- Optimise resource allocation across admissions, insurance providers, and departments.  
- Plan preventive care programs targeting conditions with highest financial and clinical impact.  
- Support data-driven operational and financial decision-making to ensure better patient care and sustainable hospital operations.
