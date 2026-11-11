
# Health Insurance Cost Analysis

**Analyzing Healthcare Insurance Charges, Customer Risk Profiles, and Cost Drivers Using Python and Statistical Analysis**

## Project Overview

This project focuses on analyzing health insurance data to understand the factors associated with insurance charges and identify potential customer risk profiles. Using Python, statistical analysis, and data visualization, the project explores relationships between policyholders' demographic characteristics, health indicators, smoking habits, and insurance costs.

The analysis aims to provide meaningful insights into healthcare cost patterns that can support insurance pricing strategies, risk assessment, customer segmentation, and data-driven business decisions.

## Business Objectives

The primary objectives of this project are to:

- Understand the structure, quality, and characteristics of the health insurance dataset.
- Examine demographic and health-related factors associated with insurance charges.
- Identify patterns and relationships between age, BMI, smoking status, region, and medical insurance costs.
- Perform descriptive and statistical analysis to evaluate differences between customer groups.
- Identify important cost-related patterns that can support insurance risk assessment and pricing decisions.
- Present findings through meaningful visualizations and statistical evidence.

## Dataset Overview

The dataset contains **1,338 policyholder records** with demographic, health-related, and insurance information.

Key variables include:

| Variable | Description |
|---|---|
| age | Age of the policyholder |
| sex | Gender of the policyholder |
| bmi | Body Mass Index |
| children | Number of dependent children |
| smoker | Smoking status |
| region | Geographic region |
| charges | Medical insurance charges |
| Level | Insurance plan level |
| Score | Health-related score |

The dataset provides a foundation for exploring how customer characteristics and health-related factors are associated with insurance costs.

## Tools & Technologies

- **Python** – Data analysis and statistical computing
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **SciPy** – Statistical hypothesis testing
- **Jupyter Notebook** – Analysis and documentation environment

## Project Workflow & Methodology

### 1. Data Loading and Inspection

- Imported the dataset using Pandas.
- Examined dataset dimensions, column information, and data types.
- Checked missing values and duplicate records.
- Reviewed categorical and numerical variables.

### 2. Data Preparation

- Converted relevant columns into appropriate data types.
- Identified and removed duplicate records.
- Prepared categorical variables for analysis.
- Reviewed the dataset for consistency and analytical readiness.

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand the distribution of variables and identify patterns across policyholders.

Key analysis areas included:

- Age and insurance charge distributions.
- Smoking status and customer distribution.
- Regional policyholder distribution.
- Relationship between age and insurance charges.
- Insurance charge comparisons across smoking groups.
- BMI and other health-related patterns.
- Comparisons of demographic and insurance characteristics.

### 4. Descriptive Statistical Analysis

Calculated statistical measures to understand the distribution and variability of important numerical variables.

Measures included:

- Mean and median
- Standard deviation and variance
- Minimum and maximum values
- Quartiles and percentiles
- Range and frequency distributions

Categorical variables were also analyzed using frequency counts and percentage distributions.

### 5. Statistical Hypothesis Testing

Applied statistical tests to evaluate differences in insurance charges across selected customer groups.

**Independent Samples Welch's t-test**

- Compared insurance charges between smokers and non-smokers.
- Evaluated whether the observed difference was statistically significant.
- Used Welch's t-test without assuming equal population variances.

**Kruskal-Wallis H-test**

- Compared insurance charges across different geographic regions.
- Evaluated whether statistically significant differences existed among regional groups.

## Key Findings & Business Insights

The analysis produced several important findings:

- The average policyholder age was approximately **39.21 years**.
- The average BMI was approximately **30.66**.
- Average insurance charges were approximately **13,270**.
- Non-smokers represented approximately **79.5%** of policyholders, while smokers represented **20.5%**.
- Age showed a positive relationship with insurance charges.
- BMI also demonstrated an association with insurance costs.
- Smoking status showed the strongest association with insurance charges among the examined factors.

### Statistical Test Results

| Statistical Test | Test Result | P-value | Conclusion |
|---|---:|---:|---|
| Welch's t-test (Smoker vs. Non-smoker) | 32.75 | 5.89e-103 | Statistically significant difference |
| Kruskal-Wallis (Across Regions) | 4.73 | 0.192 | No statistically significant difference observed |

**Interpretation:**

- The Welch's t-test indicates a statistically significant difference in insurance charges between smokers and non-smokers. In this dataset, smokers had considerably higher insurance charges.
- The Kruskal-Wallis test did not identify a statistically significant difference in insurance charges across geographic regions at the 5% significance level.

These findings represent statistical associations and group differences within the dataset; they do not establish causal relationships.

## Business Value

This analysis demonstrates how healthcare insurance data can be transformed into meaningful business insights.

The findings can help insurance organizations:

- Better understand customer risk profiles.
- Evaluate factors associated with higher insurance costs.
- Support data-informed insurance pricing strategies.
- Improve customer segmentation and risk assessment.
- Identify patterns that may support underwriting and business planning.
- Make more informed decisions using statistical evidence.

## Technical Skills Demonstrated

**Programming & Data Analysis:** Python, Pandas, NumPy

**Data Visualization:** Matplotlib, Seaborn, Exploratory Data Analysis

**Statistical Analysis:** Descriptive Statistics, Correlation Analysis, Welch's t-test, Kruskal-Wallis H-test, Hypothesis Testing

**Data Preparation:** Data Inspection, Data Type Conversion, Duplicate Handling, Categorical Data Analysis

**Analytical Skills:** Business Understanding, Pattern Identification, Data Interpretation, Statistical Reasoning, Business Insights

## Repository Structure

```text
Health-Insurance-Cost-Analysis/
│
├── README.md
├── BUSINESS Requirements.docx
├── Health Insurance Analysis Report.docx
├── Health Insurance Considerations and Dictionary.docx
│
├── 01_Dataset/
│   └── Health Insurance Dataset.csv
│
└── 02_Python_Analysis/
    └── Health Insurance Analysis.ipynb
```

## Project Files

| File | Description |
|---|---|
| [Business Requirements](BUSINESS%20Requirements.docx) | Business context, objectives, and analytical requirements |
| [Health Insurance Analysis Report](Health%20Insurance%20Analysis%20Report.docx) | Detailed analysis, statistical results, and findings |
| [Health Insurance Considerations and Dictionary](Health%20Insurance%20Considerations%20and%20Dictionary.docx) | Dataset documentation, variable definitions, and considerations |
| [Health Insurance Dataset.csv](01_Dataset/Health%20Insurance%20Dataset.csv) | Original dataset containing 1,338 policyholder records |
| [Health Insurance Analysis.ipynb](02_Python_Analysis/Health%20Insurance%20Analysis.ipynb) | Python notebook containing data preparation, EDA, visualizations, and statistical testing |

## About the Author

**Muhammad Jan**  
Data Analytics & Business Intelligence Specialist

- **GitHub:** [Muhammad-Jan](https://github.com/Muhammad-Jan)
- **LinkedIn:** [Muhammad Jan](YOUR-LINKEDIN-PROFILE-URL)

---

**Project Focus:** Healthcare Analytics | Insurance Cost Analysis | Exploratory Data Analysis | Statistical Hypothesis Testing | Business Intelligence
