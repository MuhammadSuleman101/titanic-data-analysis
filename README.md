# titanic-data-analysis
This project analyzes the Titanic dataset to explore survival patterns based on factors like age, gender, passenger class, and more.
# 🚢 Titanic Data Analysis Project

## 📌 Project Overview
This project analyzes the Titanic dataset to explore passenger details such as age, gender, class, and survival statistics.  
The goal is to understand patterns and relationships in the data through **data cleaning, exploration, and visualization**.

---

## 📂 Dataset
We used the **Titanic dataset** from [Kaggle Titanic Dataset](https://www.kaggle.com/datasets).  
The dataset contains information about passengers including:
- Passenger ID
- Name
- Age
- Sex
- Passenger Class
- Fare
- Embarkation Port
- Survival Status

---

## 🛠 Tools & Libraries
- **Python** 🐍
- **pandas** – For data manipulation and cleaning
- **numpy** – For numerical operations
- **matplotlib** – For data visualization
- **seaborn** – For enhanced visualizations

---

## 📊 Key Steps in the Project
1. **Data Loading**  
   - Loaded the Titanic dataset using `pandas.read_csv()`.

2. **Data Cleaning**  
   - Handled missing values for `Age`, `Cabin`, and `Embarked` columns.
   - Removed duplicate rows (if any).

3. **Data Exploration**  
   - Checked dataset info and summary statistics.
   - Explored unique values for key columns.

4. **Visualization**  
   - Survival count plots.
   - Age distribution plots.
   - Survival rate by passenger class and gender.

---

## 📈 Sample Visualizations
### Survival Count Plot
Shows the number of passengers who survived and did not survive.

### Age Distribution
Histogram showing the distribution of passenger ages.

### Survival by Gender
Comparison of survival rates between male and female passengers.

---

## 📦 How to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/MuhammadSuleman101/titanic-project.git



  2.Install Dependencies

pip install pandas numpy matplotlib seaborn


  3.Run the Script

python titanic_analysis.py

titanic-project/
│
├── README.md          # Project documentation
├── titanic.csv        # Dataset
├── titanic_analysis.py # Python script for analysis
└── visuals/           # Saved plots and charts


Future Improvements
Add machine learning models to predict survival.
Create interactive dashboards.
Add more advanced visualizations.


