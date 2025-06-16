# Insurance Cost Analysis — Predicting Healthcare Charges

This project analyzes and models healthcare insurance costs using a publicly available dataset. The goal is to identify key factors influencing insurance charges, test relevant hypotheses, and build an interactive dashboard for business users.

# Dataset Content

The dataset contains 1,338 rows and 7 columns, sourced from a public CSV file (`insurance.csv`).  
Included variables are:
- Age
- Sex
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region
- Insurance charges

The dataset was chosen for its accessibility, manageable size, and relevance.

# Business Requirements

- Enable fast data exploration and visualization for users with varying expertise.
- Provide actionable insights on key drivers of insurance costs.
- Support flexible data ingestion from CSV files.
- Allow hypothesis testing relevant to business decision-making.

# Hypotheses and Validation

*Tested hypotheses:
- Smokers have significantly higher insurance charges than non-smokers.
- Increased BMI correlates with higher insurance costs.

*Validation methods:
- Statistical tests (t-test, correlation analysis).
- Visualization of distributions and relationships.
- Regression modeling with performance evaluation (R², MSE).

# Project Plan

*Main steps:
1. Data collection and ingestion from CSV.
2. Data cleaning: removing duplicates and handling missing values.
3. Data transformation: encoding categorical variables, feature engineering.
4. Exploratory data analysis and hypothesis testing.
5. Predictive modeling with linear regression.
6. Building an interactive dashboard with Power BI or Tableau.
7. Documentation and presentation of results.

#Methodology and Tools

- Python + Pandas for - data manipulation and transformation.
- Seaborn and Matplotlib - for visualizations.
- Scikit-learn - for regression modeling.
- Power BI / Tableau - for dashboard development.

Linear regression was chosen for interpretability, with plans to explore nonlinear models in the future.

# Visualizations and Business Alignment

- Boxplots to compare charges by smoking status.
- Bar charts to visualize regional cost differences.
- Scatterplots and heatmaps to explore variable correlations.

Visuals are designed for both technical and non-technical audiences, featuring clear labels and interactive filters.

#Analysis Techniques

- Descriptive statistics (mean, median, standard deviation).
- Inferential statistics (t-tests, Pearson correlation).
- Regression modeling and residual analysis.
- Limitations: linear models may miss nonlinear effects; future work will consider advanced models.

#Ethics and Privacy

- Dataset is anonymized and publicly available.
- Checked for demographic bias.
- Ensured fair model performance across subgroups.
- Compliant with data privacy regulations.

# Dashboard Design

Dashboard sections include:
- Overview: Key metrics with filters for age, region, and smoker status.
- Demographics: Distributions by gender, age, and BMI.
- Cost Analysis: Charges segmented by smoking and number of children.
- Model Insights: Predictions, residual plots, and user controls.

User-friendly design with clear titles, legends, explanations, and interactive filters.

#Known Issues and Limitations

- Occasional lag with very large datasets.
- Some filter combinations produce empty charts; planned fixes.
- Basic interactivity in the dashboard; future enhancements planned.
#Feedback and Learning

- Peer reviews enhanced usability.
- Ongoing learning in statistics, ETL, and visualization.
- Next steps include advanced ML models and cloud deployment.

# Deployment

The project is deployed on Heroku:
- **App URL:** [https://milos.herokuapp.com/](https://milos.herokuapp.com/)
- Python runtime specified in `runtime.txt`
- Deployment steps:
  1. Create Heroku app and connect GitHub repo.
  2. Automatic deployment and build monitoring.
  3. Use `.slugignore` to exclude large unused files.

# Libraries Used

- `pandas` for data wrangling and transformation  
- `numpy` for numerical operations  
- `matplotlib`, `seaborn` for data visualization  
- `scikit-learn` for machine learning  
- `jupyter` notebooks for development 
 
# License

This project is open-source under the MIT License.

# Author

Milos Visnjic  
GitHub: miloss11  

