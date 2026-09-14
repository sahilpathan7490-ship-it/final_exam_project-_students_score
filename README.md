# final_exam_project-_students_score
Student Scores Statistical Data Analysis

## Project Overview

This project is a practical statistical analysis of a student performance dataset created for the Practical Exam – Set A. The analysis is performed in Python using Google Colab.

The dataset contains **5,000 student records** and the following 7 variables:

- `Student_ID`
- `Age`
- `Math_Score`
- `Science_Score`
- `English_Score`
- `Hours_Studied`
- `Pass_Fail` (0 = Fail, 1 = Pass)

## Objectives

The project covers the practical questions given in the exam:

1. Calculate mean, median and mode of Math Score.
2. Calculate range, variance and standard deviation of Science Score.
3. Find the probability of students passing.
4. Create a contingency table between Pass/Fail and Hours Studied > 5.
5. Calculate conditional probability P(Pass | Hours Studied > 5).
6. Plot a histogram and normal curve for Math Score.
7. Calculate skewness and kurtosis for Science Score.
8. Create a Q-Q plot for English Score.
9. Represent the first five Math and Science scores as vectors.
10. Calculate the dot product of the two vectors.
11. Calculate L1 and L2 norms of the Math Score vector.
12. Calculate the angle between the two vectors.

## Tools and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- SciPy
- Matplotlib

## Dataset Inspection

- Records: **5,000**
- Columns: **8**
- Dataset shape: **(5000, 8)**
- Student IDs are unique in the dataset.
- The analysis uses the supplied CSV file directly.

## Results

### 1. Math Score – Central Tendency

| Measure | Result |
|---|---:|
| Mean | 68.18 |
| Median | 68 |
| Mode | 72 |

The three measures describe the typical level of Math performance. The mean and median are very close, suggesting that the centre of the Math Score distribution is fairly stable.

### 2. Science Score – Dispersion

| Measure | Result |
|---|---:|
| Minimum | 18 |
| Maximum | 100 |
| Range | 82 |
| Variance | 171.75 |
| Standard Deviation | 13.11 |

### 3. Probability of Passing

- Total students: **5,000**
- Passed students: **4,971**
- Probability of passing: **0.9942 (99.42%)**

The dataset shows a very high observed passing probability.

### 4. Contingency Table – Pass/Fail vs Hours Studied > 5

| Pass_Fail | Hours ≤ 5 | Hours > 5 |
|---|---:|---:|
| 0 (Fail) | 28 | 1 |
| 1 (Pass) | 2043 | 2928 |

### 5. Conditional Probability

**P(Pass | Hours_Studied > 5) = 0.9997 (99.97%)**

This means that, among students who studied for more than 5 hours, approximately 99.97% passed.

### 6. Science Score – Skewness and Kurtosis
- Skewness: **0.0199**
- Kurtosis: **-0.0591**

The skewness is close to zero, so the Science Score distribution is approximately symmetric. The slightly negative kurtosis indicates relatively light tails compared with a normal distribution.

### 7. Linear Algebra Results
First five Math scores:
`[73, 72, 54, 95, 79]`
First five Science scores:
`[69, 62, 79, 58, 53]`
- Dot product: **23464**
- L1 norm of Math vector: **373.00**
- L2 norm of Math vector: **169.40**
- Angle between Math and Science vectors: **17.17°**

The relatively small angle indicates that the two score vectors point in broadly similar directions for the first five students.

## Visualizations
The project includes:
- Histogram of Math Scores with a normal curve
- Q-Q plot of English Scores
- Statistical interpretation of Science Score skewness and kurtosis

## Project Structure
Student-Scores-Statistical-Analysis/
├── students_scores_final exam_dataset.csv
├── final_exam_project2.ipynb
├── Statistics_Data_Analysis_Documentation.docx
└── README.md
## Conclusion

This project applies descriptive statistics, probability, distribution analysis, visualization and basic linear algebra to student academic data. The results provide a compact statistical view of student scores, study habits and pass/fail outcomes while also demonstrating practical Python programming skills.

## Author

**Sahil Pathan**

