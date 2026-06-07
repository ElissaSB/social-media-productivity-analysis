# Social Media Productivity Analysis

## Overview

This project investigates the relationship between social media usage, productivity, stress, and lifestyle factors using statistical and exploratory data analysis techniques.

The analysis was conducted as part of a Statistics for Data Science project and applies multiple statistical methods to understand how behavioral and lifestyle variables influence productivity.

The project includes data preprocessing, exploratory data analysis (EDA), hypothesis testing, regression modeling, principal component analysis (PCA), and clustering techniques.

---

## Research Question

How does social media usage relate to individual productivity and stress levels?

This project examines whether factors such as:

- Daily social media usage
- Stress levels
- Sleep duration
- Coffee consumption
- Burnout frequency

can explain variations in productivity.

---

## Dataset

Source: Social Media vs Productivity Dataset (Kaggle)

The dataset contains approximately 30,000 observations describing behavioral patterns, social media usage, lifestyle habits, and productivity indicators.

After data cleaning and preprocessing, the final analytical dataset contained more than 21,000 observations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- SciPy
- Statsmodels
- Jupyter Notebook / Google Colab

---

## Statistical Methods Applied

### 1. Data Preprocessing

- Missing value handling
- Variable selection
- Data cleaning
- Outlier inspection

### 2. Exploratory Data Analysis (EDA)

- Summary statistics
- Histograms
- Boxplots
- Correlation matrix analysis

### 3. Hypothesis Testing

Welch Two-Sample t-Test:

- Null Hypothesis (H₀):
  Mean productivity is equal between genders.

- Alternative Hypothesis (H₁):
  Mean productivity differs between genders.

### 4. Regression Analysis

#### Simple Linear Regression

Investigated:

- Social Media Usage → Productivity
- Job Satisfaction → Productivity

#### Multiple Linear Regression

Predictors:

- Social media usage
- Sleep hours
- Coffee intake
- Burnout days
- Stress level

Target variable:

- Productivity score

### 5. Unsupervised Learning

#### Principal Component Analysis (PCA)

Used to reduce dimensionality and visualize behavioral patterns.

#### K-Means Clustering

Applied to identify behavioral groups among participants.

---

## Key Findings

### Social Media Usage and Productivity

The analysis found no statistically significant linear relationship between social media usage and productivity.

### Job Satisfaction and Productivity

Job satisfaction showed a strong positive relationship with productivity.

### Gender Differences

No statistically significant difference in productivity was found between male and female participants.

### Clustering Insights

Clustering revealed distinct behavioral profiles that were not visible through regression analysis alone.

---

## Project Structure

```text
social-media-productivity-analysis/
│
├── data/
│   └── social_media_productivity.csv
│
├── code/
│   ├── analysis.py
│   └── analysis.ipynb
│
├── reports/
│   └── Elissa_Sbeity_Statistics_Project.pdf
│
├── images/
│   ├── correlation_matrix.png
│   ├── regression_plot.png
│   └── clustering_plot.png
│
├── README.md
└── requirements.txt
```

---

## Sample Visualizations

The project includes:

- Variable distributions
- Correlation matrix heatmap
- Regression plots
- PCA visualization
- K-Means clustering visualization

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/social-media-productivity-analysis.git
```

### Navigate to Project

```bash
cd social-media-productivity-analysis
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run Analysis

```bash
python analysis.py
```

---

## Learning Outcomes

This project demonstrates skills in:

- Statistical analysis
- Data cleaning
- Exploratory data analysis
- Hypothesis testing
- Regression modeling
- Machine learning
- Data visualization
- Research reporting

---

## Author

**Elissa Sbeity**

B.Sc. Computer Science  
M.S. Data Science Student

---

## License

This project is intended for educational and portfolio purposes.
