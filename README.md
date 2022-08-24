# School_District_Analysis 

## Overview

The school board suspected evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered in the students_complete.csv file. They requsted from me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and repeat the analysis after I replace the math and reading scores. This way, they could see how these changes affected the overall analysis. To perform this analysis I used Anaconda & Jupyter Notebook with Python, Pandas Library and Numpy library.

## Results

* How is the district summary affected?
After we remove the data in the 9th grade of thomas high school, in the District Summary average math score went from 79.0 to 78.9, average reading score stayed the same at 81.9, % passing math went ftom 75.0 to 74.8, % passing reading went from 86.0 to 85.7 and % overall pssing is went from 65 to 64.9

Original District Summary




Adjusted District Summary


* How is the school summary affected?

Removing the inacurate data effected Thomas High Schools performance. Thomas High School was in the list of top 5 schools before we adjusted the analysis. After the adjustment Thomas Hight School moved in to list of low 5 schools.

Top 5 school list


Low 5 school list


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
After removing inacurate data in the 9th grade of Thomas High School, School summary has dirastically changed. % overall passing score went from 90.948012 to 65.076453 which definetely makes sense. 

Original School Summary











Adjusted School Summary


* How does replacing the ninth-grade scores affect the Math and reading scores by grade, Scores by school spending, Scores by school size, Scores by school type? 
Math and Reading scores for Thomas High School replaced with NaN value.

																																																																																																															
Replacing 9th grades scores did not effect the scores by school spending and scores by school sizing and score by school type.

Original spending summary

Adjusted spending summary


Original size summary


Adjusted size summary


Original type summary


Adjusted type summary



## Summary
This analysis shows us that School board was right about their suspicion. As soon as we remove the 9th graders scores school ranking has changed. However this move did not effect anything else other than school ranking. 
