
**HERB AWARENESS SURVEY ANALYSIS**

**Project Overview**

This project began as a practical exercise to create a Google Form, collect responses and analyse the results.

I designed a survey about medicinal-herb awareness, knowledge, usage, information sources and interest in buying herb-based products. I shared it with close friends and family and collected 28 responses.

I loaded the responses into Google Colab, cleaned and explored the data, created useful categories and exported the analysed data to Google Sheets. With AI assistance, I developed a dashboard to communicate the findings.

**Project Objectives**

- Explore awareness and self-rated knowledge of medicinal herbs.
- Understand how often respondents use herbs.
- Identify where respondents get information about herbs.
- Examine what respondents associate herbs with.
- Explore interest in buying herb-based products.
- Present the findings through a clear dashboard.

**Tools Used**

- Google Forms for survey design and response collection.
- Google Sheets for storing responses and analysed data.
- Google Colab for running the analysis.
- Python and Pandas for data cleaning, exploration and feature engineering.
- HTML, CSS and JavaScript for the dashboard, developed with AI assistance.
- PDF for presenting the dashboard with clickable page navigation.

**Project Workflow**

Google Forms → Google Sheets → Google Colab → Analysed Data → Dashboard

**1. Data Collection**

I created a Google Form and shared it with friends and family. The survey asked about age, gender, herb awareness, knowledge, usage, information sources, associations and purchase intention.

**2. Data Cleaning**

I checked the data structure, missing values and duplicate records. I shortened the question headings, removed unnecessary spaces, converted age and knowledge scores to numeric values and excluded names from the analysis.

**3. Exploratory Data Analysis**

I used counts, percentages and cross-tabulations to explore the responses. I compared purchase interest across usage groups and herb associations.

Some respondents listed several information sources. I separated these answers so each source could be counted once per response.

**4. Feature Engineering**

I created age groups, awareness indicators, usage scores, purchase-interest groups and descriptive customer segments. These fields helped organise the responses and make comparisons.

**5. Data Export**

After completing the analysis, I prepared the data for export to Google Sheets. The export included the analysed responses, information-source mentions and summary measures.

**6. Dashboard**

The dashboard presents the findings in three sections:

- **Overview:** key figures for awareness, usage and purchase interest.
- **Purchase Potential:** buying interest, usage patterns and herb associations.
- **Marketing and Audience:** information sources, age, gender and interest within groups.

**Key Findings**

- 82.1% had heard of medicinal herbs.
- 71.4% had used herbs occasionally or frequently.
- 25.0% reported frequent herb use.
- 89.3% would definitely or probably consider buying herb-based products.
- 53.6% would definitely consider buying.
- 50.0% primarily associated herbs with health and wellness.
- 53.6% mentioned social media as an information source.

Awareness was common, while frequent usage was less common. Health and wellness was the leading association, followed by cooking and flavour. Purchase interest also extended beyond current users: six of the eight non-users would consider buying herb-based products.

**Repository Structure**

**01_Raw_Data**  
Original survey responses with identifying details removed.

**02_Data_Processing**  
The analysis notebook and cleaned, transformed datasets.

**03_Dashboard**  
The dashboard PDF.

**Skills Practised**

- Survey design and data collection.
- Data cleaning using Python and Pandas.
- Exploratory data analysis.
- Feature engineering.
- Exporting analysed data to Google Sheets.
- Dashboard design and communicating findings.

**About the Sample**

This was a learning exercise using responses from friends and family. The findings describe these 28 respondents. Purchase intention reflects stated interest rather than confirmed purchases or sales.
