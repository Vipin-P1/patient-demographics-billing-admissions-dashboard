# Holistic Overview of Patient Demographics, Billing, and Admission Trends

## Objective

This Tableau storyboard was created to provide a comprehensive view of patient demographics, billing patterns, and hospital admission trends. The project aims to support healthcare managers, hospital administrators, and insurance analysts in understanding patient population characteristics, identifying high-cost conditions, and optimising resource allocation across admissions and insurance providers.

The storyboard consists of three interconnected dashboards, each focusing on complementary aspects of healthcare analytics: demographics, billing, and admission analysis. By integrating patient-level, insurance, and medical condition data, the dashboards allow decision-makers to explore patterns, identify cost drivers, and understand patient care dynamics.

---

## Tableau Public Link

🔗 [View the Storyboard on Tableau Public](https://public.tableau.com/app/profile/vipin.premkumar/viz/Task3Tableau-HolisticOverviewofPatientDemographicsBillingandAdmissionTrends/HolisticOverviewofPatientDemographicsBillingandAdmissionTrends)

---

## Data

- **Source**: [Kaggle Synthetic Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)  
- **Coverage**: Patient demographics, medical conditions, insurance providers, billing amounts, and admission types.  
- **Preparation Steps**:
  - Standardised age bins and medical condition codes.
  - Removed incomplete patient records and anonymised identifiers.
  - Aggregated billing amounts by patient, condition, and admission type for accuracy.
  - Calculated KPI measures such as average billing per admission, total billing, and dominant age group.  

This dataset was chosen for its comprehensiveness across multiple hospital metrics, supporting actionable insights for operational and financial planning.

---

## Dashboard Overview

### 1. Patient Demographics and Medical Insights

This dashboard provides a high-level overview of the hospital’s patient population and prevalent medical conditions. It highlights key KPIs such as average patient age (54 years), the most diagnosed medical condition (Obesity), and the dominant age group (45–59 years). The visualisations allow administrators to quickly identify which patient segments contribute most to admissions and billing, and how these segments differ by age, gender, and insurance coverage.

The **Patient Breakdown by Gender and Age Bin** chart shows billing distribution for male and female patients across age bins (12, 24, 36, 48, 60, 72+). Hovering over bars reveals the average length of stay, highlighting which age groups generate higher resource use. This provides insights into middle-aged patients as the primary drivers of hospital billing, informing targeted interventions or wellness programs.  

![Patient Demographics and Medical Insights](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Patient%20Demographic%20and%20Medical%20Insights%20Dashboard.jpg)

The next chart focuses on **gender and age distribution of patient cases**. Horizontal stacked bars show the number of cases for male and female patients in each age group. Hovering provides a breakdown of admission type (elective, emergency, urgent), enabling administrators to see where hospital resources are concentrated.  

![Patient Age Breakdown by Gender](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Breakdown%20by%20Gender%20Detail.jpg)

**Patient Age Distribution** reinforces the predominance of the 49–59 age group. Hovering on these bars reveals admission type splits, making it clear how middle-aged patients drive both patient volume and resource utilisation.  

![Patient Age Distribution](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Age%20Distribiton%20Detail.jpg)

Finally, the **Age-Related Variance by Insurance Provider** chart uses vertical box plots to show billing distribution by age group across insurers. Medicare shows the widest cost spread, whereas United Healthcare is more concentrated. Hovering highlights average billing per age group, providing actionable insights for cost management and insurance negotiations.  

![Age-Related Variance in Healthcare Costs](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Age%20Related%20Variance%20Detail.jpg)

---

### 2. Billing Overview: Insurance, Admissions & Conditions

This dashboard focuses on financial performance and insurance patterns. It presents key KPIs such as average billing per admission (25K), costliest condition (Hypertension), and total billing amount (458 million). Administrators and finance teams can use this dashboard to understand which insurance providers and medical conditions contribute most to hospital revenue and resource allocation.

**Billing Distribution by Insurance Provider** shows that Medicare and Aetna dominate total billing (133M and 128M). Hovering reveals gender split for each provider, highlighting patient composition and potential equity considerations.  

![Billing Overview: Insurance, Admissions & Conditions](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Billing%20Overview%20Dashboard.jpg)

The next chart provides a more granular view of **billing across insurance providers by gender**, helping decision-makers visualise which patient segments are driving revenue within each insurer.  

![Billing Distribution Across Insurance Providers](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Insurance%20Providers%20Distribution%20Detail.jpg)

**Billing Overview by Medical Condition** highlights average billing for each condition, with obesity and asthma at the top. Hovering shows age breakdown, supporting condition-specific planning and resource allocation strategies.  

![Billing Overview by Medical Condition](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Billing%20Overview%20Detail.jpg)

This dashboard also provides insights into **admission types**, showing elective, urgent, and emergency cases. Elective admissions dominate, and hovering reveals age bin and case count, supporting operational planning and staffing strategies.  

---

### 3. Healthcare Billing and Admissions Analysis

The final dashboard synthesises patient, billing, and admission data to provide actionable insights for hospital management. It presents KPIs including top insurance provider by billing (Medicare, 133M), total admissions (18,000), and top billed admission type (Elective). 

**Billing Amount vs Patient Volume Comparison** shows the contribution of each medication to hospital expenditure, with hover displaying number of cases. This helps identify opportunities for cost optimisation and inventory planning.  

![Healthcare Billing and Admissions Analysis](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Heahthcare%20Billing%20%26%20Admissions%20Dashboard.jpg)

The **Medical Condition and Billing Amount by Admission Type** chart uses horizontal stacked bars to highlight high-cost conditions and their respective admission types, with asthma and obesity at the top. Hovering shows the number of cases per condition-admission combination, informing disease-specific resource allocation.  

![Billing Amount and Patient Volume Comparison](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Billing%20Amount%20Patient%20Volume%20Detail.jpg)

Finally, **Billing Distribution by Admission Type** uses donut charts to visualise how billing varies by admission type and insurance provider. The central portion of each donut shows total billing, and hovering reveals percentage contribution by insurer, supporting detailed budgeting and pricing strategies.  

![Billing Distribution by Admission Type](https://github.com/Vipin-P1/patient-demographics-billing-admissions-dashboard/blob/main/visualizations/Admission%20Distribution%20Detail.jpg)

---

## Visualisation Design Choices

- **Audience**: Hospital administrators, finance managers, and healthcare analysts.  
- **Colour palette**: Neutral base with blue and orange accents to distinguish metrics while keeping focus on data.  
- **Chart types**: Bar charts, horizontal stacked bars, vertical box plots, pie charts, donut charts, and trend lines.  
- **Interactive elements**: Hover tooltips, drill-downs by age, gender, condition, and insurance provider.  
- **Storyboard structure**: Three dashboards linked via navigation to provide a holistic view from demographics to billing to admissions.

---

## Key Takeaways

- Middle-aged patients (45–59) drive both admissions and billing, indicating focus areas for care management.  
- Obesity and asthma are the highest cost conditions, with implications for preventive programs.  
- Medicare and Aetna dominate total billing, highlighting insurance-driven financial exposure.  
- Elective admissions, though high in number, represent significant billing impact, necessitating careful capacity and cost management.  
- Detailed breakdowns by gender, age, insurance, and admission type provide actionable insights for strategic planning, resource allocation, and cost optimisation.

---

## Strategic Implications

This storyboard enables hospitals and healthcare organisations to:

- Identify high-cost patient groups and conditions.  
- Optimise resource allocation across admissions, insurance providers, and departments.  
- Plan preventive care programs for conditions driving the greatest financial and clinical impact.  
- Support data-driven financial and operational decisions, ensuring better patient care and sustainable hospital operations.
