# Analysis of Covid-19 Pandemic in Vietnam
Analyzed and visualized Covid-19 data in Vietnam using Python and Tableau, culminating in an interactive dashboard and a class presentation to effectively communicate key trends.

## Project Goal and Motivation

The Covid-19 pandemic disrupted all aspects of life — from health to economies and mental well-being — and its impacts are still felt today. In this context, data became vital for understanding and responding to the crisis. This project analyzes Covid-19 data in Vietnam to visualize key trends and provide an objective view of the pandemic’s progression and impact.

## Data Source

This project is based on the **JHU CSSE COVID-19 Dataset**, curated by the [Center for Systems Science and Engineering (CSSE)](https://github.com/CSSEGISandData/COVID-19) at **Johns Hopkins University**. The dataset has been widely cited by researchers, governments, and journalists as a reliable source of global Covid-19 statistics.

Specifically, the dataset includes daily records of confirmed cases, deaths, and recoveries across **240 countries and territories**. The time span covers data from **January 22, 2020** to **March 10, 2023**, offering a comprehensive view of the pandemic’s evolution over more than three years. The dataset contains over **4.28 million rows**, making it a rich resource for in-depth analysis and trend exploration.

## Data Preprocessing

Before analysis, the dataset was thoroughly cleaned to ensure consistency and reliability. This included standardizing time formats, unifying inconsistent country names, removing irrelevant or incomplete data (e.g., subnational regions and outdated recovery figures), and aggregating data at the national level. Countries with insufficient data (fewer than 100 records) were also excluded.

Further details on data description and data preprocessing can be found in the **report** (in Vietnamese), which can be found in this repository.

## Dashboard 

The interactive Tableau dashboard is structured into three main sections: a header area for summary information and controls, and two lower sections featuring data visualizations.

1. **Header Area**:
   - Includes the dashboard title (left), an info button, time filter (by month), and options to download the dashboard as PDF or bitmap.
   - On the right are three interactive summary cards showing: Total Confirmed Cases, Total Recoveries, and Total Deaths. These also function as filters.

2. **Time-Based Visualizations**:
   - A vertical bar chart displaying daily new confirmed cases.
   - A line chart showing trends over time for new confirmed cases, recoveries, and deaths.

3. **Geographic Visualizations**:
   - A bubble map highlighting the global distribution of confirmed cases.
   - A horizontal bar chart ranking countries/territories by the number of cases.

These elements provide both high-level insights and detailed exploration capabilities through interactive filtering and time-based views.

🔗 [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/.t.l.7247/viz/AnalyzeCovid-19PandemicGroup10_17124837672910/FinalDashboard)

## Design Considerations

The dashboard was designed with a strong emphasis on usability, accessibility, and clarity, particularly for non-expert users. Key design principles include:

- **Chart Types**: Selected commonly used and easy-to-understand chart types to ensure accessibility for a general audience with no technical background.
- **Color Coding**: Applied color schemes that align with the meaning of each data category and ensured color contrast is suitable for users with color vision deficiencies.
- **Layout**: Organized the dashboard with a clean and balanced layout that supports intuitive navigation and readability.
- **Interactivity**: Prioritized interactive elements such as clickable summary boxes and filters to allow users to explore data dynamically.

Details of the design choices made can be found in the *"Đánh giá Dashboard"* (Dashboard Evaluation) section of the report.

## Analysis

The project includes an in-depth analysis of the pandemic’s overall trends and changes over time across different regions of the world. It explores patterns in case surges, recoveries, and fatalities, and provides potential explanations for observed differences — such as the timing of outbreaks, government interventions, and healthcare system responses.

All detailed analyses and insights are documented in the report in the section titled *"Phân tích Dashboard"* (Dashboard Analysis).

## User Feedback

To evaluate the dashboard's usability and effectiveness, we conducted a user study with **20 participants**. Their feedback provided valuable insights that helped improve the design, interactivity, and clarity of the dashboard.

Details of the feedback and adjustments made can be found in the *"Phản hồi ý kiến"* (User Feedback) section of the report.

## Integration and Sharing

The dashboard is publicly available and can be accessed via Tableau Public:

🔗 [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/.t.l.7247/viz/AnalyzeCovid-19PandemicGroup10_17124837672910/FinalDashboard)

In addition to the standalone Tableau link, the dashboard has also been integrated into:

- 🌐 Our website: [gr10.netlify.app](https://gr10.netlify.app/lt/gk#dashboard)
- 📓 A Kaggle Notebook (integration example): [View on Kaggle](https://www.kaggle.com/code/mplee30/tableau-integration)

These integrations demonstrate how the dashboard can be embedded and shared across different platforms to enhance accessibility and visibility.

## Team Members

This project was collaboratively developed by:

- Lê Công Đắt  
- Lê Trần Minh Khuê  
- Hoàng Trung Nam  
- Lê Trần Như Ngọc  
- Lê Thị Minh Phương (repository owner and team leader)

The project was completed under the guidance of **Dr. Bùi Tiến Lên** as part of the *Data Visualization* course at the **University of Science, VNU-HCM**.
