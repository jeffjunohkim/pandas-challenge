# pandas-challenge

### README

# School District Analysis

This project analyzes the academic performance of schools within a district, with a focus on understanding the impact of various factors such as spending per student, school size, and school type. The analysis is based on several summary DataFrames that provide insights into different aspects of school performance.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Analysis](#analysis)
  - [District Summary](#district-summary)
  - [Spending Summary](#spending-summary)
  - [Size Summary](#size-summary)
  - [Type Summary](#type-summary)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)

## Overview

The objective of this analysis is to provide a comprehensive overview of school performance in the district. Key metrics such as average math and reading scores, and the percentage of students passing math and reading are calculated and analyzed. The impact of spending per student, school size, and school type on these metrics is examined.

## Dataset

The dataset includes the following files:
- `schools_complete.csv`
- `students_complete.csv`

These files are combined to create a comprehensive dataset containing information on school names, student names, grades, test scores, and school budgets.

## Analysis

### District Summary

The district-wide performance metrics provide a holistic view of the overall academic performance across all schools.

- **Total Schools**: 15
- **Total Students**: 39,170
- **Total Budget**: \$24,649,428.00
- **Average Math Score**: 79.00
- **Average Reading Score**: 81.88
- **% Passing Math**: 74.98%
- **% Passing Reading**: 85.81%
- **Overall Passing Rate**: 65.17%

### Spending Summary

The spending summary provides insights into how spending per student impacts academic performance.

| Spending Ranges (Per Student) | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | Overall Passing Rate |
|-------------------------------|--------------------|-----------------------|----------------|-------------------|----------------------|
| <$585                         | 83.46              | 83.93                 | 93.46          | 96.61             | 90.37                |
| $585-630                      | 81.90              | 83.16                 | 87.13          | 92.72             | 81.42                |
| $630-645                      | 78.52              | 81.62                 | 73.48          | 84.39             | 62.86                |
| $645-680                      | 77.00              | 81.03                 | 66.16          | 81.13             | 53.53                |

**Insights:**
- Higher spending per student does not necessarily correlate with better academic performance. 
- Schools with spending less than $585 per student have the highest overall passing rates.

### Size Summary

The size summary examines the impact of school size on academic performance.

| School Size         | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | Overall Passing Rate |
|---------------------|--------------------|-----------------------|----------------|-------------------|----------------------|
| Small (<1000)       | 83.82              | 83.93                 | 93.55          | 96.10             | 89.88                |
| Medium (1000-2000)  | 83.37              | 83.86                 | 93.60          | 96.79             | 90.62                |
| Large (2000-5000)   | 77.75              | 81.34                 | 69.96          | 82.77             | 58.29                |

**Insights:**
- Smaller schools tend to perform better academically across all metrics compared to larger schools.
- Large schools have significantly lower passing rates, suggesting that larger school sizes might negatively impact student performance.

### Type Summary

The type summary compares the performance of charter schools versus district schools.

| School Type | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | Overall Passing Rate |
|-------------|--------------------|-----------------------|----------------|-------------------|----------------------|
| Charter     | 83.47              | 83.90                 | 93.62          | 96.59             | 90.43                |
| District    | 76.96              | 80.97                 | 66.55          | 80.80             | 53.67                |

**Insights:**
- Charter schools significantly outperform district schools in all areas.
- The overall passing rate for charter schools is much higher (90.43%) compared to district schools (53.67%).

## Conclusion

This analysis highlights several important trends in school performance:

1. **Spending Efficiency**: Higher spending per student does not necessarily lead to better academic outcomes. Efficient use of resources is crucial.
2. **Impact of School Size**: Smaller schools tend to have better academic performance, suggesting the benefits of more personalized and focused educational environments.
3. **School Type**: Charter schools outperform district schools significantly, indicating potential benefits from the charter school model, such as greater flexibility and autonomy.

These insights can help stakeholders make informed decisions about resource allocation, school size management, and the adoption of best practices from high-performing charter schools.


