# School_District_Analysis
## Overview
The school board beleives the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

### Resources
- Data Source: students_complete.csv
- Software Python 3.6.1, Jupyter Notebook

## Results
Average math scores of all schools by grade with ninth graders from Thomas High Schools removed and showing as nan.

![Average Math Scores by Grade](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/average_math_grade.PNG)

Average reading score of all schools by grade with ninth graders from Thomas High Schools removed and showing as nan.

![Average Reading Scores by Grade](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/average_reading_grade.PNG)

In the oriognal analysis the overall passing percentage of Thomas High School is 91%.

![Overall Passing Percentage Without Ninth Grade](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/THS_without_ninth.PNG)

In the original analysis Thomas High School ranked 2nd among all schools.  Here are the top 5 schools.

![Top 5 schools](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/Top_5_schools.PNG)

Once all the ninth grade data is removed the overall passing percentage of Thomas High School drops to 65%.

![Overall Passing Percentage Without Ninth Grade](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/THS_with_ninth.PNG)

With ninth grade removed from Thomas High School they would be ranked towards the bottom.  Here are the bottom 5 schools from the orginal analysis.

![Bottom 5 schools](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/Bottom_5_schools.PNG)

Average passing scores by school spending.

![Average passing scores by school spending](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/average_scores_school_spending.PNG)

Average passing scores by school size.

![Average passing scores by school size](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/average_scores_school_size.PNG)

Average passing scores by school type.

![Average passing scores by school type](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/average_scores_school_type.PNG)

The orginal average passing scores across all schools.

![average passing scores](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/average_passing_scores.PNG)


The new average passing scores across all schools saw very little shift.

![new average passing scores](https://github.com/joeapodaca/School_District_Analysis/blob/main/Resources/new_average_passing_scores.PNG)




### Summary
The ninth grades scores are helping the overall passing percentage by a huge amount.  The overall passing percenatge drops from 91% to 65% when ninth grade is removed.
The spending per student shows that spending more money per student does not increase the overall passing percentage.  The overall passing percantege acutally goes down as per student spending increases.
The school size seems make a big difference with the large schools having the lowest overall passing percentage.
The charter schools perform the best with an overall passing of 90% compared to the district with only 54%.


