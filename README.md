# Student Performance Analysis

## Overview

This project provides an analysis of student performance based on various metrics including math, reading, and writing scores. The analysis includes statistical measures, probability calculations, distribution checks, and more.

## Dataset

The dataset used in this project is "students_performance.csv", which contains the following columns:

- Student ID: A unique identifier for each student.
- Gender: The gender of the student (Male/Female).
- Race/Ethnicity: The race or ethnicity of the student.
- Parental Level of Education: The highest level of education attained by the student's parents.
- Lunch: The type of lunch the student receives (Free/Reduced or Standard).
- Test Preparation Course: Whether the student completed a test preparation course (Completed/None).
- Math Score: The student's score in the math test.
- Reading Score: The student's score in the reading test.
- Writing Score: The student's score in the writing test.

## Analysis

### Basic Statistical Analysis

We calculated the mean and standard deviation for math, reading, and writing scores to understand their distributions.

### Probability Calculations

- Probability of Being Male or Having a Math Score Above 80
- Bayes' Theorem Application: Probability of being Male given a Math Score above 80.

### Normal Distribution

We checked the normality of Math Scores using QQ plots, histograms, and the Shapiro-Wilk test.

### Z-Score and Noise Removal

Calculated z-scores for Math Scores and removed outliers beyond 95% to clean the data.

### Visualizations

Generated box plots, histograms, scatter plots, and pie charts to visualize Math Scores before and after noise removal.

### Hypothesis Testing

- Two-Sample Test: Compared Math Scores between Male and Female students.
- ANOVA: Compared Math Scores across different ethnicities.

### Confidence Interval

Calculated a 95% confidence interval for the mean Math Score.
