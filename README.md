# Data-Science-Internship
Complete Data Science Internship Portfolio — Python, Data Analysis, Visualization, Statistics, Hypothesis Testing &amp; Machine Learning.
# Data Science Internship Portfolio — Weeks 1–5

## 📌 Internship Overview

Welcome to my **Data Science Internship Portfolio**, documenting my learning, implementation, and project work completed across **Weeks 1 to 5** of my internship.

During this internship, I worked through a progressive data science workflow, beginning with **data acquisition and cleaning**, moving into **exploratory data analysis and visualization**, followed by **statistical hypothesis testing**, and finally **machine learning model development and evaluation**.

The projects demonstrate practical use of Python and widely used data science libraries to transform raw datasets into meaningful insights and predictive results.

### Internship Journey

```text
Data Acquisition
       ↓
Data Cleaning & Preprocessing
       ↓
Exploratory Data Analysis
       ↓
Data Visualization & Storytelling
       ↓
Statistical Analysis & Hypothesis Testing
       ↓
Machine Learning
       ↓
Model Evaluation & Interpretation
       ↓
Final Integrated Report
```

---

## 🎯 Internship Objectives

The major objectives of this internship were to:

* Develop practical skills in **Python-based data science**.
* Understand the complete data analysis lifecycle.
* Learn effective **data cleaning and preprocessing** techniques.
* Perform **Exploratory Data Analysis (EDA)** on real-world datasets.
* Create meaningful and informative data visualizations.
* Communicate analytical findings through **data storytelling**.
* Apply statistical methods to test research hypotheses.
* Understand statistical significance and practical significance.
* Develop and evaluate machine learning models.
* Analyze model performance using appropriate evaluation metrics.
* Understand model errors, limitations, and generalization.
* Practice responsible interpretation of data-driven results.
* Maintain reproducible project work through **GitHub**.

---

# 🛠️ Technologies & Tools

### Programming Language

* **Python**

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Statistical Analysis

* Welch's Independent-Samples t-Test
* Descriptive Statistics
* Confidence Intervals
* Cohen's d
* Hypothesis Testing

### Machine Learning

* Scikit-learn
* Logistic Regression
* StandardScaler
* Train-Test Split
* Confusion Matrix
* ROC-AUC
* Precision
* Recall
* F1-Score

### Development & Version Control

* Jupyter Notebook
* Python
* Git
* GitHub

---

# 📅 Week 1 — Data Acquisition, Cleaning & Exploratory Data Analysis

## 🚢 Titanic Data Analysis

**Dataset:** Titanic Dataset
**Records:** 891
**Variables:** 12

### Objective

The first week focused on understanding the fundamentals of data science through **data acquisition, data cleaning, exploratory data analysis, and visualization**.

The Titanic dataset was analyzed to understand passenger characteristics and survival patterns.

### Key Activities

* Loaded the Titanic dataset using Pandas.
* Inspected dataset structure and data types.
* Identified missing values.
* Checked for duplicate records.
* Handled missing values in:

  * `Age`
  * `Embarked`
* Removed the `Cabin` variable because of extensive missing data.
* Performed exploratory analysis.
* Examined survival patterns across passenger classes.
* Analyzed relationships between variables.

### Key Findings

* The dataset contained **891 observations and 12 variables**.
* `Age` contained 177 missing values.
* `Cabin` contained extensive missing values.
* `Embarked` contained 2 missing values.
* Survival varied across passenger classes.
* The dataset contained more non-survivors than survivors.
* The relationship between Age and Fare did not show a strong simple linear pattern from the exploratory scatterplot.

### Skills Demonstrated

* Data loading
* Data inspection
* Missing-value handling
* Data cleaning
* Exploratory Data Analysis
* Basic visualization
* Analytical interpretation

### 🔗 Project Repository

**[Titanic Data Analysis](https://github.com/suhasphate2023/Titanic-Data-Analysis)**

---

# 📊 Week 2 — Advanced Data Visualization & Storytelling

## 🦠 COVID-19 Patient Outcomes Analysis

**Dataset:** COVID-19 Patient Dataset
**Records:** 1,048,575
**Variables:** 22

### Objective

Week 2 focused on **advanced data visualization and storytelling** using a large COVID-19 patient dataset.

The objective was to move beyond individual charts and create a logical visual narrative connecting **demographics, clinical characteristics, risk factors, and disease severity**.

### Key Activities

* Loaded and explored a large healthcare dataset.
* Examined demographic variables.
* Identified coded unknown values such as `97`, `98`, and `99`.
* Treated unknown codes appropriately during correlation analysis.
* Created age groups.
* Analyzed ICU-related patterns.
* Examined pneumonia status.
* Investigated clinical risk factors.
* Analyzed sex distribution.
* Examined the relationship between intubation and ICU status.
* Created a sequence of visualizations to communicate a data story.

### Visualizations Created

* Age distribution
* Age-group distribution
* ICU status across age groups
* Pneumonia status
* Risk-factor correlation heatmap
* Sex distribution
* Intubation vs ICU analysis

### Visual Story

```text
Patient Demographics
        ↓
Age & Sex Distribution
        ↓
Clinical Characteristics
        ↓
Risk Factors
        ↓
Disease Severity
        ↓
ICU / Intubation
```

### Key Insights

The analysis demonstrated how demographic and clinical variables can be explored to identify patterns associated with disease severity and healthcare interventions.

The project also emphasized that **observational associations should not automatically be interpreted as causal relationships**.

### Skills Demonstrated

* Large dataset handling
* Data preprocessing
* Feature grouping
* Advanced visualization
* Correlation analysis
* Healthcare data interpretation
* Data storytelling
* Responsible interpretation

### 🔗 Project Repository

**[COVID-19 Patient Outcomes — Advanced Data Visualization & Storytelling](https://github.com/suhasphate2023/COVID-19-Patient-Outcomes-Advanced-Data-Visualization-and-Storytelling)**

---

# 📈 Week 3 — Statistical Analysis & Hypothesis Testing

## 📚 Test Preparation and Mathematics Scores

### Research Question

> Is completing test preparation associated with a significant difference in Mathematics scores?

### Hypotheses

**Null Hypothesis (H₀):**

There is no significant difference in Mathematics scores between students who completed test preparation and those who did not.

**Alternative Hypothesis (H₁):**

There is a significant difference in Mathematics scores between the two groups.

**Significance Level:** α = 0.05

### Methodology

The analysis involved:

* Converting Mathematics scores to numeric format.
* Removing missing observations.
* Separating students into two independent groups:

  * Completed test preparation
  * No test preparation
* Calculating descriptive statistics.
* Applying **Welch's independent-samples t-test**.
* Calculating the mean difference.
* Constructing a 95% confidence interval.
* Calculating **Cohen's d** to evaluate effect size.

### Results

| Metric                       |           Result |
| ---------------------------- | ---------------: |
| Completed preparation — N    |           10,573 |
| Completed preparation — Mean |            69.76 |
| Completed preparation — SD   |            14.95 |
| No preparation — N           |           20,068 |
| No preparation — Mean        |            65.16 |
| No preparation — SD          |            15.10 |
| Mean Difference              |           4.5991 |
| t-statistic                  |          25.5092 |
| p-value                      | 1.89495 × 10⁻¹⁴¹ |
| 95% Confidence Interval      | [4.2457, 4.9525] |
| Cohen's d                    |           0.3056 |

### Conclusion

The extremely small p-value provides strong evidence against the null hypothesis at the 0.05 significance level.

Therefore, the analysis found a **statistically significant difference** in Mathematics scores between students who completed test preparation and those who did not.

However, the analysis is observational, so the result should be interpreted as an **association rather than proof of causation**.

### Skills Demonstrated

* Research question formulation
* Hypothesis development
* Descriptive statistics
* Statistical testing
* Welch's t-test
* Confidence intervals
* Effect-size analysis
* Statistical interpretation
* Responsible communication of results

### 🔗 Project Repository

**[Statistical Analysis & Hypothesis Testing](https://github.com/suhasphate2023/Statistical-Analysis-Hypothesis-Testing)**

---

# 🤖 Week 4 — Machine Learning Model Development & Evaluation

## 🌸 Iris Flower Classification

**Dataset:** Iris Dataset
**Observations:** 150
**Classes:** 3
**Features:** 4

### Objective

Week 4 introduced supervised machine learning through a multiclass classification problem.

The objective was to build a model capable of classifying Iris flowers into their respective species using four numerical flower measurements.

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target

* Setosa
* Versicolor
* Virginica

### Methodology

```text
Iris Dataset
     ↓
Data Inspection
     ↓
Feature / Target Separation
     ↓
Stratified 80/20 Train-Test Split
     ↓
Feature Standardization
     ↓
Logistic Regression
     ↓
Model Prediction
     ↓
Performance Evaluation
```

### Model

**Algorithm:** Logistic Regression

**Maximum Iterations:** 1000

Feature scaling was performed using `StandardScaler`, with the scaler fitted only on the training data before transforming the training and testing sets.

### Model Performance

| Metric            | Result |
| ----------------- | -----: |
| Training Accuracy | 95.83% |
| Testing Accuracy  | 93.33% |
| Precision         | 93.33% |
| Recall            | 93.33% |
| F1-Score          | 93.33% |
| Weighted ROC-AUC  | 99.67% |
| Test Errors       | 2 / 30 |

### Error Analysis

The model classified all **Setosa** observations correctly.

The two incorrect predictions occurred between:

* Versicolor
* Virginica

This reflects the greater similarity and overlap between these two classes compared with Setosa.

### Generalization

The difference between training and testing accuracy was approximately **2.50 percentage points**, suggesting good generalization without a strong indication of overfitting.

### Skills Demonstrated

* Supervised machine learning
* Classification
* Train-test splitting
* Stratification
* Feature scaling
* Logistic Regression
* Model evaluation
* Confusion-matrix analysis
* ROC-AUC analysis
* Error analysis
* Generalization assessment

### 🔗 Project Repository

**[Machine Learning — Iris Classification](https://github.com/suhasphate2023/Machine-Learning-Iris-Classification)**

---

# 📝 Week 5 — Comprehensive Final Report

Week 5 consolidated the learning and practical work completed during Weeks 1–4 into a comprehensive final report.

The final report demonstrates progression through the major stages of a data science workflow:

| Week   | Focus                        | Main Outcome                                          |
| ------ | ---------------------------- | ----------------------------------------------------- |
| Week 1 | Data Cleaning & EDA          | Titanic survival analysis                             |
| Week 2 | Visualization & Storytelling | COVID-19 patient outcome visualization                |
| Week 3 | Statistical Analysis         | Hypothesis testing and significance analysis          |
| Week 4 | Machine Learning             | Iris classification using Logistic Regression         |
| Week 5 | Final Integration            | Comprehensive portfolio and strategic recommendations |

### Week 5 Focus Areas

* Integration of previous project work
* Cross-project analysis
* Methodology review
* Results interpretation
* Strategic recommendations
* Business and research impact
* Limitations
* Future work
* Reproducibility
* Technical documentation

---

# 🔗 Project Repositories

| Week   | Project                                   | Repository                                                                                                                    |
| ------ | ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Week 1 | Titanic Data Analysis                     | [GitHub Repository](https://github.com/suhasphate2023/Titanic-Data-Analysis)                                                  |
| Week 2 | COVID-19 Visualization & Storytelling     | [GitHub Repository](https://github.com/suhasphate2023/COVID-19-Patient-Outcomes-Advanced-Data-Visualization-and-Storytelling) |
| Week 3 | Statistical Analysis & Hypothesis Testing | [GitHub Repository](https://github.com/suhasphate2023/Statistical-Analysis-Hypothesis-Testing)                                |
| Week 4 | Machine Learning — Iris Classification    | [GitHub Repository](https://github.com/suhasphate2023/Machine-Learning-Iris-Classification)                                   |

---

# 💡 Key Learning Outcomes

Through these projects, I developed an understanding of how different data science techniques complement each other.

### 1. Data Preparation

Learned how to inspect datasets, identify missing values, handle data-quality issues, and prepare data for analysis.

### 2. Exploratory Analysis

Developed the ability to investigate distributions, relationships, patterns, and potential insights before applying advanced techniques.

### 3. Data Visualization

Learned to select appropriate visualizations and organize them into a meaningful narrative rather than presenting charts independently.

### 4. Statistical Reasoning

Learned to formulate hypotheses, select appropriate statistical tests, interpret p-values and confidence intervals, and distinguish statistical significance from causality.

### 5. Machine Learning

Developed practical understanding of classification, preprocessing, model training, evaluation, and error analysis.

### 6. Responsible Interpretation

Learned that analytical results must be interpreted within the limitations of the dataset, methodology, and assumptions.

### 7. Reproducibility

Used Python and GitHub-based project organization to maintain a transparent and reviewable technical workflow.

---

# 🧠 Skills Demonstrated

## Technical Skills

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Git
* GitHub
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* Hypothesis Testing
* Machine Learning
* Classification
* Model Evaluation

## Analytical Skills

* Problem formulation
* Research-question development
* Data interpretation
* Statistical reasoning
* Pattern identification
* Error analysis
* Model assessment
* Critical thinking
* Evidence-based conclusions

## Professional Skills

* Technical documentation
* Data storytelling
* Report writing
* Result communication
* Reproducibility
* Research interpretation
* Strategic recommendation development

---

# 📊 Overall Project Impact

The four projects collectively demonstrate a progression from **raw data to actionable analytical understanding**.

The internship provided practical experience in:

```text
Raw Data
   ↓
Clean Data
   ↓
Exploration
   ↓
Visualization
   ↓
Statistical Evidence
   ↓
Predictive Modeling
   ↓
Evaluation
   ↓
Interpretation
   ↓
Recommendations
```

This progression helped establish a foundation for applying data science methods to real-world analytical and predictive problems.

---

# 🚀 Future Work

Potential improvements and extensions include:

* Perform cross-validation for machine learning models.
* Compare Logistic Regression with other classification algorithms.
* Apply hyperparameter tuning.
* Explore feature engineering and feature selection.
* Conduct deeper statistical analysis.
* Investigate additional variables and interactions.
* Use larger and more diverse datasets.
* Improve visualization interactivity.
* Develop dashboards for analytical reporting.
* Build end-to-end machine learning pipelines.
* Add automated testing and reproducibility checks.
* Deploy selected models as practical applications.

---

# ⚠️ Limitations

The projects have several methodological limitations.

* Some analyses use observational datasets, so associations should not automatically be interpreted as causal relationships.
* Dataset quality and representativeness can affect conclusions.
* Missing and unknown values may influence analytical results.
* The Iris dataset is relatively small and clean compared with many real-world datasets.
* Logistic Regression may not capture all nonlinear relationships.
* Model performance may change when applied to new or substantially different data.
* Statistical significance does not necessarily imply a large practical effect.
* Additional validation and benchmarking would strengthen future analyses.

---

# 📂 Portfolio Structure

A recommended GitHub portfolio structure is:

```text
Data-Science-Internship/
│
├── README.md
│
├── Week-1-Titanic/
│   ├── Dataset
│   ├── Notebook
│   ├── Visualizations
│   └── Report
│
├── Week-2-COVID19/
│   ├── Dataset
│   ├── Notebook
│   ├── Visualizations
│   └── Report
│
├── Week-3-Statistical-Analysis/
│   ├── Dataset
│   ├── Notebook
│   ├── Statistical-Analysis
│   └── Report
│
├── Week-4-Machine-Learning/
│   ├── Dataset
│   ├── Notebook
│   ├── Model
│   ├── Evaluation
│   └── Report
│
└──Week-5-Final-Report/
    └── Final-Report.docx
```

---

# 🏆 Conclusion

This internship portfolio represents my practical journey through the core stages of data science.

Starting with **data cleaning and exploratory analysis**, I progressed to **advanced visualization and storytelling**, then applied **statistical hypothesis testing**, and finally developed and evaluated a **machine learning classification model**.

The projects strengthened my technical knowledge of Python and data science libraries while also improving my ability to interpret results, communicate insights, evaluate limitations, and approach analytical problems systematically.

The four GitHub repositories provide the technical project work associated with the internship and demonstrate the progression of my practical skills across data analysis, statistics, visualization, and machine learning.

---

## 👨‍💻 Author

**Suhas Phate**

### Data Science Internship Portfolio

**Projects:** Data Analysis • Visualization • Statistics • Machine Learning

---

⭐ **Thank you for visiting my Data Science Internship Portfolio!**
