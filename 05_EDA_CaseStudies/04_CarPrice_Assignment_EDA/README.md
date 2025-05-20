#  Exploratory Data Analysis on Car Price Dataset

This project presents an Exploratory Data Analysis (EDA) of the **Car Price Assignment dataset**, which contains detailed specifications of cars and their corresponding prices. The goal is to understand which features most significantly affect car prices and to prepare the dataset for predictive modeling.

##  Dataset Description

- **File Name**: `CarPrice_Assignment.csv`
- **Total Records**: 205  
- **Features**: 26
- **Target Variable**: `price` (continuous)

### Sample Features:
- `car_ID`: Unique ID of each car
- `symboling`: Risk factor associated with the car (from -3 to 3)
- `CarName`: Brand and model
- `fueltype`: Gas or Diesel
- `aspiration`: Standard or Turbo
- `carbody`: Sedan, Hatchback, etc.
- `drivewheel`: FWD, RWD, etc.
- `enginelocation`: Front or rear
- `wheelbase`, `curbweight`, `enginesize`, `horsepower`, `citympg`, etc.
- `price`: Target variable (numeric)

 **Source**: UCI Machine Learning Repository / provided assignment dataset

##  Basic Info

- All features are either numeric or categorical
- No missing values in most standard versions of this dataset
- Some preprocessing may be required for `CarName` to extract the brand

##  EDA Objectives

- Understand the structure and quality of the dataset
- Identify distributions and potential outliers
- Analyze feature correlation with car price
- Explore differences in price by categorical variables like fuel type, car body, and brand
- Prepare insights for feature engineering and model development

##  Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

##  Key Analyses Performed

- **Data Overview**: Shape, types, and descriptive statistics
- **Missing Value & Duplicate Check**
- **Univariate Analysis**: Distribution plots for numeric features like `price`, `horsepower`, `curbweight`
- **Categorical Analysis**: Bar plots and count plots for variables like `fueltype`, `carbody`, `drivewheel`
- **Bivariate Analysis**: 
  - Scatterplots (e.g., `enginesize` vs `price`)
  - Boxplots (e.g., `carbody` vs `price`)
- **Correlation Heatmap**: Analyze how numerical features correlate with price
- **Brand-Level Insights**: Extracted brand from `CarName` and analyzed average prices per brand


##  Key Insights

- `enginesize`, `curbweight`, and `horsepower` show strong positive correlation with `price`
- Cars with `turbo` aspiration and `diesel` fueltype tend to be priced higher
- Brand names play a significant role in determining price, beyond just specs
- Some cars share similar specs but vary widely in price due to branding

---

## 🌐 Connect with Me  
🔗 **GitHub:** [ParthoSarothiDas](https://github.com/ParthoSarothiDas)  
🔗 **LinkedIn:** [Partho Sarothi Das](https://www.linkedin.com/in/partho-sarothi-das/)  
📧 **Email:** partho52@gmail.com  

---

