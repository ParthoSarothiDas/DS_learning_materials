#  Exploratory Data Analysis on the Titanic Dataset

This project provides an in-depth Exploratory Data Analysis (EDA) of the **Titanic dataset**, a classic dataset often used in data science and machine learning. The dataset was loaded using `seaborn`'s built-in `load_dataset('titanic')` function.

##  Dataset Description

The Titanic dataset provides data on passengers who were aboard the RMS Titanic, which sank in 1912. It includes demographic details, ticket information, and survival outcomes.

### Key Features:
- `survived`: Survival (0 = No, 1 = Yes)
- `pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `sex`: Sex
- `age`: Age in years
- `sibsp`: # of siblings/spouses aboard
- `parch`: # of parents/children aboard
- `fare`: Passenger fare
- `embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- `class`, `who`, `deck`, `embark_town`, `alive`, `alone`: Additional derived or categorical features

## Objectives of EDA

- Understand the structure and distribution of the dataset
- Analyze survival rates across different groups (e.g., gender, class)
- Identify missing values and data quality issues
- Discover patterns and correlations between features

## Tools & Libraries Used

- Python
- Pandas
- Seaborn
- Matplotlib
- NumPy

## Key Analyses Performed

- **Data Overview**: Shape, types, missing values, and summary statistics
- **Missing Value Analysis**: Identification and visualization of null values
- **Categorical Analysis**: Count plots and pie charts for features like `sex`, `pclass`, and `embarked`
- **Numerical Analysis**: Distribution plots for `age`, `fare`, and others
- **Survival Analysis**: Grouped visualizations and cross-tabulations by `sex`, `pclass`, `age group`, etc.
- **Correlation Heatmap**: Visual exploration of numeric feature correlations


## Insights & Findings

- Women had significantly higher survival rates than men
- Passengers in 1st class had better survival rates than those in lower classes
- Younger passengers had a higher chance of survival
- There were several missing values in `age`, `deck`, and `embark_town`

## References

- [Seaborn Titanic Dataset](https://github.com/mwaskom/seaborn-data)
- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

---

## 🌐 Connect with Me  
🔗 **GitHub:** [ParthoSarothiDas](https://github.com/ParthoSarothiDas)  
🔗 **LinkedIn:** [Partho Sarothi Das](https://www.linkedin.com/in/partho-sarothi-das/)  
📧 **Email:** partho52@gmail.com  

---

