# Graduate Admission Analysis for UCLA

## Preface
For my first personal project, I decided to explore the [Graduate Admission](https://www.kaggle.com/mohansacharya/graduate-admissions) dataset from Kaggle. 

This was to get comfortable with common EDA techniques and employ typical machine learning algorithms to determine the chance of admission for each student.

## Objective
400 applicants have been surveyed as potential students for UCLA. The university weighs certain aspects of a student's education to determine their acceptance.

The objective is to explore what kind of data is provided, determine the most important factors that contribute to a student's chance of admission, and select the most accurate model to predict the probability of admission.

## Data Description
The dataset contains information about a student's:

- GRE Score
- TOEFL Score
- University Ratings
- Statement of Purpose Score
- Letter of Recomendation Score
- CGPA
- Whether the Student Has Done Any Research
- Chance of Admission (What We're Trying to Predict)

## Exploratory Data Analysis
Here I cleaned the data a little bit and explored which factors were the most important in determining a graduate's chance of admission.

Using the heatmap below it was clear that the scores achevied on the CGPA, TOEFL and GRE were the most important:

I then explored these 3 traits and how they were represented in the data.

## Machine Learning
As the project is about if a student gets admitted or not, it sounds like a classfication case. I compared the scores achieved from three different classifiers and selected the best one.

It seemed that Logistic Regression & Random Forests scored an accuracy of 96.25%. Therefore, either method could be used for this case.

## Conclusion
This was a great way to get started for my first project outside of coursework. It gave me some practice some exploratory analysis and simple machine learning techniques.

It's great to see what specific variables contribute to the chance of admission and how they are weighted against eachother.
