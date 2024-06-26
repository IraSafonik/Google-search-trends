<img width="783" alt="Знімок екрана 2024-06-24 о 20 04 25" src="https://github.com/IraSafonik/Google-search-trends/assets/32171563/2c78f13a-02c1-49e9-89ac-2072ce85ff65">

# Google Trends Analysis Project

## 💡 Project Overview
This project aims to analyze Google search trends worldwide, focusing on specific timeframes and regions. By leveraging the extensive dataset provided by Google Trends, I aim to identify the most popular search queries, understand regional search behavior, and provide actionable insights through visualizations.

## ☝️ Project Goals
- Analyze global Google search trends from July 1, 2024, to the present.
- Identify the top search queries by country and region.
- Visualize the distribution of search queries using maps and charts.
- Provide a comprehensive overview of search behavior trends across different regions.

## 💼 Tasks
1. Extract data from the `bigquery-public-data.google_trends.international_top_terms` dataset.
2. Filter and preprocess data to focus on the desired timeframes and regions.
3. Perform data analysis to identify top search queries.
4. Create visualizations to represent the data clearly and effectively.
5. Document findings and insights in a structured report.

## 🛠️ Tools and Technologies
- **Google BigQuery**: For querying the Google Trends dataset.
- **Looker Studio**: For creating interactive and dynamic visualizations.
- **SQL**: For data extraction and manipulation.
- **Markdown**: For documentation and reporting.
- **GitHub**: For version control and project management.

## 🗂️ Data Sources
- `bigquery-public-data.google_trends.international_top_terms`: The primary dataset used for analysis, containing international Google search trends data.

## 💻 Process and Steps

### 1️⃣ Step 1: Data Extraction
- Connect to the Google BigQuery dataset.
- Write SQL queries to extract data from the `bigquery-public-data.google_trends.international_top_terms` table for the specified timeframe (from July 1, 2024, to the present).
<img width="1126" alt="Знімок екрана 2024-06-24 о 21 34 58" src="https://github.com/IraSafonik/Google-search-trends/assets/32171563/40755790-7306-4e36-9676-aa2d179b3c79">

***Note: Why I chose rank = 1:** 
I chose rank = 1 in the query to specifically retrieve the top-ranked Google search queries globally. This ensures that the data returned represents the most popular search queries during the specified period (from June 1, 2024, onwards). 

### 2️⃣ Step 2: Data Preprocessing
- Filter the data to include only relevant fields (country, region, query, week, score).
- Clean the data to remove any inconsistencies or missing values.

### 3️⃣ Step 3: Data Analysis
- Aggregate the data to find the top search queries by country and region.
- Calculate the total number of queries for each region and country.

### 4️⃣ Step 4: Visualization
- Use Looker Studio to create visualizations such as tables, maps and cards.
- Design a dashboard to display the key findings and insights.
<img width="831" alt="Знімок екрана 2024-06-24 о 22 53 56" src="https://github.com/IraSafonik/Google-search-trends/assets/32171563/60138481-6944-450c-8092-9e73885dd791">

You could find dashboard - [here](https://lookerstudio.google.com/reporting/186d9873-7360-4e0c-afd9-c9b7b1e1cb69)

### 5️⃣ Step 5: Documentation
- Document the process, findings, and insights in a comprehensive report.
- Use Markdown to format the README and other documentation files.

### 6️⃣ Step 6: Review and Publish
- Review the entire project to ensure accuracy and completeness.
- Publish the results and visualizations on GitHub.

## 🌿 Results and Conclusion
The analysis provided valuable insights into global search trends from July 1, 2024, to the present. By identifying the top search queries and visualizing the distribution of searches across different regions, this project offers a comprehensive understanding of search behavior worldwide. The visualizations and findings can be used for further research, marketing strategies, and understanding regional interests.

---

*This project was completed by Ira Safonik. If you have any questions or feedback, feel free to reach out!*

