# Aviation Accident Analysis

## Overview
This project analyzes aviation accident data to identify trends, risk factors, and actionable business recommendations for stakeholders in the aviation industry. The analysis includes accident causes, aircraft characteristics, and fatality rates to guide decisions on safety improvements and risk mitigation.

## Business Understanding
### Stakeholders:
- **Aviation Safety Authorities** (e.g., FAA, NTSB, ICAO) – for policy improvements
- **Airlines & Operators** – to enhance fleet management and pilot training
- **Aircraft Manufacturers** – to improve design and reliability
- **Insurance Companies** – for risk assessment and premium calculations

### Key Business Questions:
1. What are the primary causes of aviation accidents?
2. Which aircraft types are most frequently involved in severe accidents?
3. How do aircraft characteristics (e.g., engine count) relate to accident severity?
4. What measures can be taken to reduce accident rates and fatal injuries?

## Data Understanding and Analysis
### Source of Data:
The [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) was sourced from publicly available aviation accident databases, including the NTSB (National Transportation Safety Board) and other aviation regulatory agencies and contains records from 1962 to 2023

### Description of Data:
- **Event ID** – Unique identifier for each accident.
- **Flight Phase** – The phase of flight during which the accident occurred.
- **Accident Category** – Categorization of what led to the accident (e.g., human error, mechanical failure).
- **Aircraft Type** – Type of aircraft involved in the accident.
- **Fatal Injuries** – The number of deaths resulting from the accident.
- **Aircraft Engine Count**
- **Weather Conditions** (IMC/VMC)

### Visualizations:
#### 1. **Distribution of Accidents Across Flight Phases**
   - This visualization highlights that the highest number of accidents occur during landing then takeoff phases.

     ![image](https://github.com/user-attachments/assets/165c98ee-385a-4483-bd0f-a18b1b6635d2)


   
#### 2. **Correlation Matrix of Key Variables**
   - Shows relationships between accident causes, aircraft characteristics, and fatalities.

   - ![image](https://github.com/user-attachments/assets/b61e0bd7-1424-44c8-b8e1-c6289758688e)

   
#### 3. **Accident Causes and Their Impact on Fatalities**
   - Human error and mechanical failures emerge as the top contributors to fatal accidents.

## Conclusion
### Key Findings:
1. **Human Error & Mechanical Failures Are the Leading Causes of Accidents**
   - Emphasizes the need for better pilot training and aircraft maintenance.

2. **Weather Conditions Have a Minimally Moderate Impact**
   - Poor weather is a contributing factor but not the primary cause of fatal injuries.

3. **Engine Count Does Not Directly Affect Fatality Rates**
   - More engines do not necessarily mean safer or more dangerous aircraft.

### Business Recommendations:
- **Enhance Pilot Training & Safety Measures** – Address human error with stricter protocols.
- **Fleet Selection & Risk Management** – Choose aircraft with historically lower accident rates.
- **Emergency Preparedness & Response** – Improve emergency protocols to reduce accident severity.

---
This README provides an overview of the aviation accident analysis, offering insights and recommendations for improved aviation safety.
