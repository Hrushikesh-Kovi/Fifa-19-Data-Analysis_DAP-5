# FIFA 19 Data Analysis (EDA Project)

## 1️⃣ Project Title
FIFA 19 Dataset – Exploratory Data Analysis

## 2️⃣ Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the FIFA 19 dataset.  
The goal of the project is to clean the dataset, explore player statistics, and uncover patterns related to player age, ratings, market value, and other football attributes.

Through data cleaning and visualization, the project highlights trends in player performance, career progression, and financial aspects of professional football.

## 3️⃣ Dataset Source
Kaggle Dataset:  
https://www.kaggle.com/code/tahirazam/fifa-eda

## 4️⃣ Workflow

### 1. Data Loading
- Imported the FIFA 19 dataset using Pandas.
- Inspected the dataset structure and column information.

### 2. Data Cleaning
- Dropped rows where **Club name was missing** to avoid inconsistent replacements.
- Filled missing values in **Value column** using the column mean.
- Replaced null values in:
  - `International_Reputation` using the **mode**
  - `Skill_Moves` using the **mode**
  - `Contract_Valid_Until` using the **mode**

### 3. Exploratory Data Analysis
- Analyzed player **age distribution**.
- Explored **Overall rating and Potential rating** distribution.
- Studied the relationship between **player market value and wages**.
- Examined **dominance of right-footed vs left-footed players**.
- Analyzed **performance trends across different ages**.
- Identified **top players based on overall rating**.

### 4. Data Visualization
Used visualization techniques to better understand patterns using:
- Histograms
- Count plots
- Scatter plots
- Comparative visualizations

## 5️⃣ Key Insights

- Most players are concentrated in their **early to mid-20s**, with the highest frequency around **age 25**.
- The most common **Overall rating is 66**, showing that most players fall in the average performance range.
- The average **Potential rating (≈71)** is higher than the **Overall rating (≈66)**, indicating future growth for many players.
- Players with **higher market value tend to earn higher wages**, although variation exists due to contracts and club finances.
- **Right-footed players dominate the dataset**, accounting for approximately **76.8% of all players**.
- Player performance generally **peaks around age 27–28** and gradually declines afterward.
- **International reputation peaks slightly later (~age 30)**, showing that fame often follows peak performance.
- Top players such as **Lionel Messi, Cristiano Ronaldo, and Neymar Jr** dominate the highest overall ratings, mostly in the **27+ age range**.

## 6️⃣ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 7️⃣ LinkedIn
Connect with me on LinkedIn:  
https://www.linkedin.com/in/kovihrushikesh/