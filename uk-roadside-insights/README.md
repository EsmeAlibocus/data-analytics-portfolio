# UK Roadside Incident Insights (SQL, Excel & Power BI)

## Project Overview
This project analyses UK road collision data as a proxy for roadside assistance demand.  
The objective is to uncover patterns in incident volume, severity, and contributing factors, and to translate these findings into insight-led recommendations that could support operational decision-making for a national motoring organisation.

The project focuses on demand patterns, incident complexity, and environmental drivers that influence response pressure.

---

## Data Source
The analysis uses publicly available UK road accident data published by the Department for Transport and accessed via Kaggle.  
The dataset is based on the STATS19 collision reporting system and includes information on reported personal injury collisions on public roads.

For the purpose of this analysis, collisions are treated as a proxy for roadside incidents requiring operational response.

---

## Tools Used
- **SQL** – data cleaning, joins, aggregations, and creation of analytical views  
- **Excel** – exploratory analysis, pivot tables, and initial validation  
- **Power BI** – interactive dashboards, KPI reporting, and stakeholder-focused visualisation  

---

## Data Structure
The dataset is relational and consists of three main tables:

- **Accidents** – one row per reported incident, including date, time, location, severity, and conditions  
- **Vehicles** – details of vehicles involved in each incident  
- **Casualties** – information on people injured in each incident  

Tables are joined using a shared `Accident_Index` field.  
Vehicle and casualty counts are aggregated to the accident level to support analysis of incident complexity.

---

## Analysis Performed
- Incident demand analysis by hour of day, day of week, month, and year  
- Severity distribution and identification of high-impact incidents  
- Analysis of environmental drivers, including weather, lighting, and road surface conditions  
- Incident complexity assessment using number of vehicles and casualties involved  
- Identification of peak demand periods and high operational pressure scenarios  

---

## Key Insights
- Incident demand consistently peaks during weekday commuter hours, indicating predictable pressure on response services  
- Adverse weather and poor lighting conditions are associated with higher average incident severity  
- A relatively small proportion of incidents account for a disproportionately high operational burden due to increased severity and complexity  

---

## Recommendations
- Align patrol capacity and staffing levels with predictable peak demand periods  
- Apply enhanced prioritisation and response strategies during adverse weather and low-visibility conditions  
- Use severity and complexity indicators to support triage, escalation, and resource allocation decisions  

---

## Deliverables
- SQL scripts to build a clean, reusable analysis layer  
- A structured analysis view aggregating vehicle and casualty data to incident level  
- Power BI report featuring KPI cards, trend analysis, and interactive filters  
- Supporting Excel exploration for validation and sense-checking  

---

## Limitations
- The dataset includes only police-reported personal injury collisions and does not capture all roadside breakdowns  
- Collisions are used as a proxy for roadside assistance demand and may not fully reflect real-world service call volumes  
- Findings are based on historical data and should be supplemented with operational data where available  

---

## Notes
This project is intended to demonstrate analytical thinking, SQL capability, and insight communication rather than to replicate internal systems or data used by any specific organisation.
