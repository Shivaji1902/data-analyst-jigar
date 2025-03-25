# data-analyst-jigar
# Exploratory Data Analysis
- Project Description: Exploratory Data Analysis (EDA) on Operating Power Water System
- Project Title: Cooling tower permit issued: An Exploratory Data Analysis
- Project Objective: The main goal of this project is to perform an exploratory data analysis (EDA) on the Vancouver city dataset to find the total issued permit for cooling water system. By analyzing various features such as system status, mechanical system type, we try to analyse the effect of that things on permit.
- Dataset: The operating power water system data from Vancouver City open data set, including some details such as:
    *	Operating permit numbers: unique number assign to each customer 
    *	Address: Residential address
    * Permit status: issued or not issued
    * Mechanical stsyem type: System type (such as Rainwater Harvesting/Alternative Water Systems, Cooling tower)
    * System report date: Date reported by city of Vancouver
    * System status: Active or Inactive
- Methodology:
   - Data Collection and Preparation:
        - Load the operating power water system data from Vancouver City data, directly in S3 storage
        - Perform initial data cleaning, which includes handling missing values, correcting data types, and renaming columns for clarity, remove unnacessary columns.
   - Data Profiling:
        - It generally deals with data quality of the dataset conccerning missing, and duplicate values. 
   - Data Cleaning:
        - 
o	Create visualizations to illustrate key insights:
	Histograms and Boxplots: Analyze the distribution of continuous variables like Age and Fare.
	Bar Charts: Showcase survival rates across different categories (e.g., Sex, Pclass).
	Heatmaps: Visualize correlations between numerical variables.
4-	Survival Analysis:
o	Compare survival rates:
	By gender: Determine if there is a significant difference in survival rates between male and female passengers.
	By class: Analyze how passenger class affected survival chances.
	By age group: Create age bins to assess survival across different age demographics.
5-	Insights and Findings:
o	Summarize the findings based on data visualizations and statistical analyses, highlighting notable trends and patterns (e.g., women and children had higher survival rates, first-class passengers had a significant survival advantage).
6-	Conclusion:
o	Discuss the implications of the findings and suggest further analyses or data-driven decisions that could be explored, such as building predictive models to classify survival based on passenger features.
Tools and Technologies:
•	Python (Pandas, NumPy, Matplotlib, Seaborn
Deliverables:
•	A comprehensive Jupyter Notebook containing all steps of the analysis, including code, visualizations, and narrative explanations of findings.
•	A presentation summarizing key insights and visualizations for stakeholders or peers.
This EDA project not only demonstrates your analytical and programming skills but also highlights your ability to derive meaningful insights from data, making it a valuable addition to your data analyst portfolio.
