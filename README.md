# PyCity Schools

## Overview of Project
Using pandas, an analysis of a school district's high schools was performed. This analysis consisted of two data sets, one
for schools and one for students. After merging the datasets and performing the analysis, academic dishonesty was reported
from one of the high schools, particularly their ninth grade. So the scores from Thomas High School"s ninth grade class needed
to be removed and the analysis need to be redone.

## Results
- The school district summary was not affected much by the removal of the THS ninth grade scores
    ![District summary comparison](https://user-images.githubusercontent.com/103155045/177909176-d9df6bf1-990c-4416-9f1f-58da87711a8e.png)

  - The school summary for show their scores for reading, math and overall passing percentage decrease slightly
    ![THS scores comparison](https://user-images.githubusercontent.com/103155045/177907883-60ecdb40-b7e6-41fe-8d15-0467f4936ca1.png)
    
- After replacing the scores THS still ranks 2nd in overall by overall passing percentage
     ![Top 5 Comparison](https://user-images.githubusercontent.com/103155045/177908440-45c7ebec-498a-4de6-97c1-4dd70eef5ded.png)
 
- For average math and reading score per grade THS ninth grade has NaN for both reading and math instead of 83.7 and 83.6
    ![scores by grade comparison](https://user-images.githubusercontent.com/103155045/177909056-25f5a367-426a-4ae2-966e-a1762c9abf75.png)

- Scores based on school spending was unaffected by the change
- Scores based on school size was unaffected by the change
- Scores based on school type was unaffected by the change



## Summary
The overall results of the school district analysis virtually remain the same, after removing the ninth grade scores
from Thomas High School. Replacing the scores with NaNs would affect THS scores substantially but by removing the NaNs
from the data before analysis it results in almost no change to the data.
