# School_District_Analysis

## Overview:
Py City schools has asked us to compare school and student data for their school district. The data is robust, with student data points that include their name, average math and reading scores, and grade level along with school information such as budget, total students, and type. This has allowed us to determine the percentage of students passing and how that connects with other elements such as the dollars spent per student or school type.
Unfortunately, some data turned out to be corrupt; specifically the Thomas High school 9th grade scores. Consequently, we needed to pull those grades out of the calculations and redo the report. 

## Results:
Removing the scores of 9th graders at Thomas High School did not have a major impact on the District summary data. There were 461 ninth grade students at Thomas High School out of an entire student data set of 39,170 students. 

Within the Thomas High School reading and math score averages, the final numbers only changed by tenths of a percent. One critical thing to note though is this is only true if the 9th grade scores are not factored into the data. If the school had been forced to count the scores as 0s or incompletes, they would have dropped from the top 5 schools to the bottom 5 schools of the district. 

**Before Removing Thomas 9th Graders**
![1 Top and Bottom Schools Before removing Thomas9th](https://user-images.githubusercontent.com/80495032/114327422-0374e180-9b07-11eb-83c4-e8633840a8ba.jpg)

**After Removing Thomas 9th Graders**
![2 Top and Bottom Schools after removing Thomas9th](https://user-images.githubusercontent.com/80495032/114327469-2acbae80-9b07-11eb-9eb5-8efccd329545.jpg)


##How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade: No change other than the result for Thomas HighSchool 9th graders now being Nan
![Before and After Scores by Grade](https://user-images.githubusercontent.com/80495032/114327182-002d2600-9b06-11eb-90f0-bcf9e0771eed.jpg)

Scores by school spending: No significant change

Scores by school size: No significant change

Scores by school type: No significant change


## Summary: 
Overall, pulling these student's data had a minor impact on the overall data story. Roughly, 1.2% of scores were cut in doing this. 

## Challenges:
There’s plenty to summarize from this data, but not much when it comes to changes from dropping 471 students. Honestly, I’m a little frustrated with the assignment as I would love to dig into talking through and analyzing all the data we came up with instead of comparing minutely small changes from one iteration to the next. I’m going back to my module work and finding virtually no changes. I’m also frustrated there’s not a simpler way of exporting/displaying dataframes than having to take screenshots to then crop and file and name. Maybe I am missing something. 
