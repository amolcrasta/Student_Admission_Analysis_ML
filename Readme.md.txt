# Student Admission Analysis

## Project Overview

This project analyzes student admission data to understand patterns influencing admission decisions across Indian states.

The objective was to:
- Identify key academic and demographic factors affecting admission
- Analyze entrance exam trends
- Evaluate scholarship and category-based impacts
- Build predictive machine learning models for admission classification

This dataset represents a realistic simulation of the Indian college admission landscape.


## Problem Statement

- Understand student admission patterns using historical data  
- Identify major factors influencing admission decisions  
- Support academic and institutional decision-making  

---

## Dataset Description

The dataset includes students from **26 Indian states** with diverse academic backgrounds.

### Key Variables:
- Category
- State
- Preferred Stream
- Entrance Exam (JEE, NEET, CET)
- Entrance Score
- Board Percentage
- Extracurricular Score
- Admission Probability
- Admission Status
- Scholarship Eligibility

The dataset is synthetically generated but modeled to resemble real-world Indian admission patterns.

---

## Data Cleaning & Preparation

- Performed initial inspection using `df.info()`
- Verified data types and null values
- No missing values detected
- Identified required and non-required columns
- Created additional bin columns for visualization:
  - Board Percentage (bin width = 10)
  - Entrance Score (bin width = 100)

### Feature Encoding:
- Label Encoding:
  - Admission Status
  - Scholarship Eligibility
- One-Hot Encoding:
  - Entrance Exam
  - Category
  - Preferred Stream

---

## Exploratory Data Analysis (EDA)

### 1. Admission Status per State
- Certain states show higher admission rates
- Suggests academic preparedness and awareness differences

### 2. State vs Entrance Exam Participation
- Exam popularity varies regionally
- Coaching and awareness impact exam selection

### 3. Entrance Exam vs Admission Status
- CET shows relatively higher admission success
- JEE & NEET are more competitive

### 4. Preferred Stream vs Admission
- Popular streams are highly competitive
- Some streams have seat vacancies

### 5. Board Percentage vs Admission
- Higher board percentages correlate with higher admission rates
- Cut-off pressure likely to increase over time

### 6. Extracurricular Score vs Admission
- Holistic profiles improve admission chances
- Institutions value non-academic achievements

### 7. Category vs Exam vs Admission
- Admission varies by category and exam combination
- Reflects reservation policy structure

### 8. Scholarship Eligibility vs Admission
- Scholarship-eligible students show stronger admission outcomes
- Financial support influences enrollment

### 9. Entrance Score vs Board Percentage
- Positive relationship observed
- Strong academic consistency across metrics

---

## Machine Learning Models Implemented

To predict admission status:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)

### ML Workflow:
- Feature Selection
- Data Scaling
- Train-Test Split
- Model Training
- Evaluation
- Testing on new data
- Model comparison

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Visualization techniques
- Jupyter Notebook

---

## Key Insights

- Board percentage and entrance score are strong predictors
- Scholarship eligibility positively impacts admission
- Entrance exam selection significantly affects outcomes
- Holistic student profiles improve admission chances
- Category-based cut-offs influence patterns

---

## Business Recommendations

- Normalize scores across entrance exams
- Expand scholarship programs
- Review weightage between board & entrance scores
- Promote lesser-known academic streams
- Increase outreach in low-admission states

## Project Impact

This project demonstrates:

- End-to-end data analysis workflow
- Business-oriented interpretation of insights
- Feature engineering and encoding
- Multiple ML model implementation
- Analytical storytelling using structured visualization

---

Author: **Amol Crasta**  
Location: India  
Date: December 2025
