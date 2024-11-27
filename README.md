# School District Analysis

## Overview

This project analyzes student performance across different schools in a fictional district. Using data from two CSV files (one containing school details and the other containing student data), the project computes a variety of metrics, such as:

- Total number of schools and students
- Average math and reading scores
- Passing rates in math, reading, and overall
- Performance by school type, size, and spending

The analysis is performed using Python and the `pandas` library, which allows for efficient data manipulation and aggregation.

## Files

- `schools_complete.csv`: Contains information about each school (e.g., name, type, budget).
- `students_complete.csv`: Contains information about each student (e.g., name, scores, grade, school name).

## Project Structure

```css
school_district_analysis/ 
├── Resources/ │ 
├── schools_complete.csv │ 
└── students_complete.csv 
├── school_district_analysis.py 
└── README.md
```

## Requirements

Make sure you have the required dependencies installed:

- `pandas`: Used for data manipulation.
- `pathlib`: Used for working with file paths.
  
You can install these dependencies using `pip`:
```bash
pip install pandas pathlib
```


## Setup and Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/msmith150/pandas-challenge.git
 ```

2. Ensure you have the CSV files in the `Resources/` folder.

3. Run the `PyCitySchools.py` script to see the analysis:

```bash
python PyCitySchools.py
```

    The script will output various results, including:
    - District summary
    - School summary (by type, size, etc.)
    - Performance by grade, school size, and spending
    - Top and bottom-performing schools

## Key Metrics

### District Summary

The district summary includes:
- Total number of schools
- Total number of students
- Total budget
- Average math and reading scores
- Percentages of students passing math, reading, and both subjects (overall passing rate)

### School Summary

The school summary provides insights on each school:
- School type (e.g., Charter, District)
- Total number of students
- Total school budget and per-student budget
- Average math and reading scores
- Percentages of students passing math, reading, and overall

### Performance by Grade

The math and reading scores for each grade (9th, 10th, 11th, and 12th) across all schools are calculated and displayed.

### Performance by School Spending

The analysis categorizes schools into spending ranges (e.g., < $585, $585-$630) and calculates the average math and reading scores, as well as the passing rates for each range.

### Performance by School Size

Schools are categorized into small (<1000 students), medium (1000-2000 students), and large (2000+ students). The analysis compares how the size of a school affects student performance in terms of math scores, reading scores, and passing rates.

### Performance by School Type

The analysis also compares schools based on their type (e.g., Charter vs. District). The average math scores, reading scores, and passing rates for each school type are calculated.

## Data Sources

This analysis uses two datasets:
1. `schools_complete.csv`: Contains details about each school, including name, type, and budget.
2. `students_complete.csv`: Contains student-specific data, such as name, grade, and scores in math and reading.

These datasets are fictional and provided for the purpose of analysis.

## Results

Here are the key findings based on the analysis:

### District Summary:
- **Total Schools**: 15
- **Total Students**: 39170
- **Total Budget**: $25,084,625
- **Average Math Score**: 78.9%
- **Average Reading Score**: 81.0%
- **% Passing Math**: 74.0%
- **% Passing Reading**: 85.0%
- **% Overall Passing Rate**: 65.0%

### Top Performing Schools:
- **School A**: 98% Overall Passing Rate
- **School B**: 96% Overall Passing Rate

### Bottom Performing Schools:
- **School Z**: 55% Overall Passing Rate
- **School Y**: 60% Overall Passing Rate

### Performance by School Size:
- **Small Schools** (under 1000 students) generally outperform larger schools in math and reading scores.
- **Medium Schools** (1000-2000 students) have moderate performance, while larger schools tend to have lower passing rates.

## Conclusion

This analysis reveals trends in student performance based on factors such as school size, funding, and school type. By breaking down the performance into different categories, we can identify both strengths and weaknesses in the district's educational system.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



