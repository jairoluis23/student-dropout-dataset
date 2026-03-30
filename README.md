# Student Dropout Synthetic Dataset

## Description
This dataset simulates student dropout prediction in a university.

## Variables

### Demographic
- age: 16–30
- gender: Male/Female
- origin: Urban/Rural

### Academic
- high_school_avg: 2.0 – 5.0
- admission_score: 200 – 400
- first_semester_grade: 1.0 – 5.0

### Financial
- socioeconomic_level: 1 – 6
- scholarship: Yes/No
- loan: Yes/No

### Target
- dropout: Yes/No

## Data Issues Introduced
- 5% missing values randomly added
- Outliers:
  - Grades up to 10
  - Scores up to 1000

## Purpose
To train machine learning models for dropout prediction.
