# Chicago Urban Data Analysis

### Exploring Education, Crime, and Socioeconomic Conditions Using SQL and Python

## 📌 Project Overview

This portfolio project explores Chicago's public school performance, community socioeconomic conditions, and reported crime incidents using SQL and Python.

The project consists of two complementary analyses that demonstrate how structured datasets can be queried, summarized, and interpreted to identify patterns and generate actionable recommendations.

The analysis uses historical public datasets and prepared subsets. Findings are descriptive and should not be interpreted as causal relationships or current citywide conditions.

## 🎯 Project Objectives

- Analyze school attendance, safety scores, and college enrollment across Chicago Public Schools.
- Identify community areas experiencing high poverty and socioeconomic hardship.
- Explore crime categories and the geographic distribution of recorded incidents.
- Compare school safety scores across school types.
- Apply SQL techniques to extract, aggregate, filter, and interpret data.
- Communicate findings and recommendations to support data-informed decision-making.

## 🛠️ Tools and Technologies

- **SQL:** Data querying, filtering, aggregation, grouping, and subqueries.
- **Python:** Database connectivity and data preparation.
- **Pandas:** Loading and managing structured datasets.
- **SQLite:** Relational database management.
- **Jupyter Notebook:** Interactive SQL analysis and documentation.

## 📂 Project Notebooks

### Project 1 — Chicago Public Schools SQL Analysis

[View Chicago Public Schools SQL Analysis](notebooks/Chicago_Public_Schools_SQL_Analysis.ipynb)

**Focus:** School attendance, safety scores, college enrollment, and community-level comparisons.

**Key Findings**

- The dataset contains 566 schools, including 462 elementary schools.
- The highest recorded safety score is 99, achieved by multiple schools.
- Eight schools have attendance rates below 70%.
- John Charles Haines Elementary School recorded the highest attendance rate among the top ten schools returned by the query, at 98.40%.
- Oakland recorded the lowest summed college enrollment value (140), followed by Fuller Park (531) and Burnside (549).
- North Center had a hardship index of 6 and was associated with the school with the highest college enrollment in the relevant query.

**Recommendations**

- Investigate factors associated with low attendance at the eight identified schools.
- Examine schools with low safety scores to identify areas requiring further assessment.
- Normalize enrollment comparisons by school counts or appropriate denominators.
- Address missing attendance values and ensure percentage fields are correctly converted for numerical analysis.

**Conclusion**

This analysis highlights differences in school attendance, safety scores, and enrollment across Chicago Public Schools. SQL filtering, aggregation, sorting, and subqueries helped identify patterns and areas requiring further investigation.

The project also demonstrates the importance of data cleaning, appropriate comparison measures, and contextual information when interpreting educational data.

### Project 2 — Chicago Census, Crime, and Schools SQL Analysis

[View Chicago Census, Crime, and Schools SQL Analysis](notebooks/Chicago_Census_Crime_Schools_SQL_Analysis_With_Data_Sources.ipynb)

**Focus:** Community poverty, hardship, school safety, and reported crime incidents.

**Key Findings**

- The supplied datasets contain 78 census records, 566 school records, and 533 crime records.
- Riverdale had the highest recorded hardship index.
- Riverdale also recorded the highest percentage of households below the poverty line (56.5%) in the census data.
- Austin (community area 25) had the highest number of crime records in the supplied crime subset.
- Six distinct crime categories appeared in school-related locations, including battery, assault, and criminal damage.
- Average recorded safety scores were approximately 49.52 for elementary schools, 49.62 for high schools, and 48.00 for middle schools.

**Recommendations**

- Investigate socioeconomic needs in communities with high poverty and hardship indicators.
- Examine school safety score distributions and missing values before making comparisons.
- Analyze school-related crime using more complete, time-aligned incident records.
- Use population-adjusted crime rates rather than raw incident counts when comparing communities.

**Conclusion**

This analysis demonstrates how SQL can be used to investigate socioeconomic indicators, school safety, and reported crime patterns across related datasets.

Filtering, aggregation, grouping, and nested queries helped identify communities with notable socioeconomic conditions and summarize school and crime records.

However, the crime dataset is a limited subset, and the results cannot establish current citywide crime rates or causal relationships. More comprehensive and consistently timed datasets would support stronger comparisons and recommendations.

## 📊 Data Sources

The datasets are derived from City of Chicago public data and distributed as prepared educational subsets through IBM Skills Network.

**Chicago Census Data**

[Download Chicago Census Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCensusData.csv)

**Chicago Public Schools Data**

[Download Chicago Public Schools Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv)

**Chicago Crime Data**

[Download Chicago Crime Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCrimeData.csv)

*Note: These three CSV links correspond to Project 2. Project 1 uses a separate Chicago Public Schools dataset.*

## 💡 Overall Key Takeaways

- **SQL proficiency:** Demonstrated practical SQL skills using filtering, aggregation, grouping, sorting, and subqueries.
- **Analytical thinking:** Identified patterns across education, crime, and socioeconomic datasets.
- **Data interpretation:** Distinguished descriptive findings from causal explanations and recognized the limitations of incomplete datasets.
- **Problem-solving:** Translated analytical questions into SQL queries and meaningful results.
- **Communication:** Presented technical findings through concise explanations, recommendations, and conclusions.

## 📝 Overall Conclusion

These projects demonstrate the practical application of SQL and Python to analyze real-world public datasets.

The first project examines differences in school attendance, safety, and enrollment, while the second expands the analysis to community poverty, hardship, and crime records.

Together, they highlight the value of relational databases, SQL querying, and analytical reasoning in transforming raw data into interpretable information.

The projects also reinforce an essential principle of data analytics: meaningful insights depend not only on accurate queries but also on data quality, appropriate comparisons, and careful interpretation of results.

## 📚 Acknowledgment

Underlying public datasets are provided by the City of Chicago. Prepared datasets and original educational exercises were made available through IBM Skills Network.
