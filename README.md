# Health360 — Smart Healthcare Analytics

## Project overview
Health360 is a browser-based analytics dashboard for exploring the supplied smart healthcare dataset. It presents descriptive population-level summaries, health outcomes, age distribution, lifestyle indicators, health measurements, and risk-score bands.

## LINKS 
  - web : https://health360-1-4ov6.onrender.com/
  - story : https://public.tableau.com/app/profile/insiya.jabalpurwala/viz/Health360_17931255272280/Story1?publish=yes
  - dashboard : https://public.tableau.com/app/profile/insiya.jabalpurwala/viz/Health360_17931255272280/HealthCareDashboard?publish=yes
## Included files
- `website/index.html` — interactive website dashboard.
- `data/smart_healthcare_dataset.csv` — source dataset supplied for the project.
- `documentation/Project_Report.docx` — editable project report.
- `documentation/data_dictionary.csv` — field types, non-null counts, missing values, and unique values.
- `presentation/Health360_Project_Presentation.pptx` — editable presentation deck.
- `templates/Project_Summary_Template.docx` — reusable project summary template.
- `templates/Testing_Checklist.md` — website testing checklist.
- `templates/Project_Plan_Template.md` — project plan template.

## Run the website
1. Open `website/index.html` in a recent browser such as Chrome or Edge.
2. Keep an internet connection available because the chart library is loaded from a CDN.
3. Use the filter controls to explore gender, age range, and exercise level.

## Technologies
- HTML and CSS for layout and responsive styling
- JavaScript for filtering and summary calculations
- Chart.js for interactive charts
- CSV dataset for the source records

## Dashboard sections
- Summary KPIs: records analysed, average age, average risk score, heart disease share
- Health outcomes: heart disease, diabetes, stroke
- Age distribution and gender breakdown
- Average BMI, blood pressure, cholesterol, and glucose
- Lifestyle indicators: smoking, alcohol, fatigue, chest pain, dizziness
- Risk score distribution
- Quick insights and a filtered record preview

## Important note
This is a student analytics project, not a medical device. Values and indicators are descriptive summaries of the dataset and must not be used as a diagnosis or treatment recommendation.
