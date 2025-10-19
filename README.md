# College Event Feedback Analysis

## Project Overview
This project analyzes student feedback from the Student Satisfaction Survey dataset, treating courses as "events" (e.g., workshops). It includes data cleaning (handling "3.00 / 60.00" format and fixing column name issues), rating analysis, NLP on question text, visualizations, and recommendations.

## Dataset
- Source: Student Satisfaction Survey (Kaggle or similar).
- Rows: 580
- Key Columns: Questions, Weightage 1-5 (rating counts), Average/Percentage (e.g., "3.00 / 60.00"), Course Name (note: 'Course Name ' with trailing space).

## Requirements
- Python 3+
- Libraries: pandas, numpy, matplotlib, seaborn, textblob, wordcloud

Install via: `pip install pandas numpy matplotlib seaborn textblob wordcloud`

## How to Run
1. Place `student_satisfaction_survey.csv` in the same folder.
2. Launch Jupyter: `jupyter notebook`
3. Open `College_Event_Feedback_Analysis.ipynb` and run all cells.

## Key Files
- `College_Event_Feedback_Analysis.ipynb`: Main notebook with code, visualizations, and report.
- `student_satisfaction_survey.csv`: Input data.

## Insights
- Top-rated courses: [Add from `course_stats.head(3)`, e.g., "Course X: 4.5"].
- Common issues: [Add from `question_stats.head(5)` or word cloud, e.g., "Questions about timing scored low"].
- Recommendations: Improve low-rated areas, replicate top courses, collect free-text comments.

## Author
[Your Name] – Future Interns Project
