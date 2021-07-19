# Module 4 Challenge

## Overview of PyCitySchools

The school board has notified that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. For this, it is necessary to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, and describe how these changes affected the overall analysis.

## Results

- How is the district summary affected?

The average math and reading scores decreased -0.07% and -0.02%, respectively.
The percentage of students passing both subjects was affected by -0.4%.

![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/District%20Summary.PNG)

- How is the school summary affected?

When comparing Thomas High School results, it is clear the same negative impact that was had by replacing the ninth grade grades.

![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/School%20Summary.PNG)

Had we just replaced the scores with NaNs and rerun the Dataframe without making the necessary adjustment at Thomas High School, the impact on the school's results would have been greatly affected:

![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/Before%20to%20replace.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Although ratings were impacted, Thomas High School remains in second place in the top five highest performing schools:

![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/High%20Performing%20Schools.PNG)

- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
    When viewing grades by grade, it is clear that grades are replaced by NaNs.

    ![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/Math%20scores%20by%20grade.PNG)

    ![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/Reading%20scores%20by%20grade.PNG)

- Scores by school spending
    The impact is in the 630-644 range, which is where we have Thomas High School located.

    ![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/Spending%20ranges.PNG)

- Scores by school size
    The number of students remained the same; what was affected was the grade point average as well as the % of students who passed math and reading, although the impact was minimal.

    ![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/School%20size.PNG)

- Scores by school type
    The impact is only in the type of charter school. 

    ![img](https://github.com/CarmenU18/Module-4-Challenge/blob/main/Resources/School%20type.PNG)

## Summary

The four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs

- Recalculate the math and reading grade point average without considering ninth grade.
- Recalculate % Passing Math and Reading score for Thomas High School.
- Recalculate the average grade point average of students who passed both subjects, as well as the percentage of students who passed.
- Replace the new calculations in the summary DataFrame.

