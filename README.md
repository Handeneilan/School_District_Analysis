# School_District_Analysis 

## Overview

The school board suspected evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered in the students_complete.csv file. They requsted from me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and repeat the analysis after I replace the math and reading scores. This way, they could see how these changes affected the overall analysis. To perform this analysis I used Anaconda & Jupyter Notebook with Python, Pandas Library and Numpy library.

## Results

* How is the district summary affected?
After we remove the data in the 9th grade of thomas high school, in the District Summary average math score went from 79.0 to 78.9, average reading score stayed the same at 81.9, % passing math went ftom 75.0 to 74.8, % passing reading went from 86.0 to 85.7 and % overall pssing is went from 65 to 64.9

Original District Summary

![original district total](https://user-images.githubusercontent.com/104239978/186304428-3ba6d42d-8844-4c49-b19b-70bdf99fa0a3.png)

Adjusted District Summary

![adjusted disctrict total](https://user-images.githubusercontent.com/104239978/186304446-83465b15-e873-4f86-8a74-8c530510375f.png)

* How is the school summary affected?

Removing the inacurate data effected Thomas High Schools performance. Thomas High School was in the list of top 5 schools before we adjusted the analysis. After the adjustment Thomas Hight School moved in to list of low 5 schools.

Top 5 school list

![top 5 school list](https://user-images.githubusercontent.com/104239978/186304552-9b0835a3-dafa-4acb-be72-c7395d0304ec.png)

Low 5 school list

![low 5 school list](https://user-images.githubusercontent.com/104239978/186304541-f8eea797-d33a-4f9b-9950-c8ae6d8e237e.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
After removing inacurate data in the 9th grade of Thomas High School, School summary has dirastically changed. % overall passing score went from 90.948012 to 65.076453 which definetely makes sense. 

Original School Summary

![School Summary original](https://user-images.githubusercontent.com/104239978/186304664-1910b205-2967-4f4c-98c7-bff844f3881b.png)

Adjusted School Summary

![School Summary adjusted](https://user-images.githubusercontent.com/104239978/186304691-14c9706f-7caf-40d3-906b-0a7998cbebc5.png)

* How does replacing the ninth-grade scores affect the Math and reading scores by grade, Scores by school spending, Scores by school size, Scores by school type? 

Math and Reading scores for Thomas High School replaced with NaN value.
![adjusted math scores](https://user-images.githubusercontent.com/104239978/186305447-89ad1b7e-c8da-4bf6-8e12-c280f8f2dd86.png)
![adjusted reading scores](https://user-images.githubusercontent.com/104239978/186305475-9c4d5e8e-101c-4989-8252-c5495b0beefb.png)

Replacing 9th grades scores did not effect the scores by school spending and scores by school sizing and score by school type.

Original spending summary
![original spending summary](https://user-images.githubusercontent.com/104239978/186305595-985149ea-27f5-49bf-a83a-cfb172052317.png)

Adjusted spending summary
![adjusted spending summary](https://user-images.githubusercontent.com/104239978/186305741-809c587a-1f51-46b5-bfb1-b635d66d1468.png)

Original size summary
![original size summary](https://user-images.githubusercontent.com/104239978/186305811-3d491c1f-8eef-403d-b5c3-e273e9e1adf4.png)

Adjusted size summary
![adjusted size summary](https://user-images.githubusercontent.com/104239978/186305836-9c900cb8-d6d3-45a2-bcfd-9891cdc8d997.png)

Original type summary
![original type summary](https://user-images.githubusercontent.com/104239978/186305880-256630d4-ba2b-424d-8c07-fbf0ad453362.png)

Adjusted type summary
![adjusted type summary](https://user-images.githubusercontent.com/104239978/186305901-c86c71eb-427e-4442-a2c9-63b7d56e1422.png)

## Summary
This analysis shows us that School board was right about their suspicion. As soon as we remove the 9th graders scores school ranking has changed. However this move did not effect anything else other than school ranking. 
