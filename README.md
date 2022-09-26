# Project 1: Standardized Test Analysis

### Problem Statement

Students often stress and worry due to uncertainty of the SAT scores they need to achieve for their preferred school and field of study. The project seeks to provide insights on what scores the students will need; allowing them to set and understand their goals better.

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|intended_college_major|object|2019 SAT Scores by Intended College Major|The field a student intends to major in| 
|test_takers| float|2019 SAT Scores by Intended College Major|The amount of test takers of the SAT for the major|
|percentage_of_students_of_all_majors|float|2019 SAT Scores by Intended College Major:|This percentage shows how popular a field is, the total percentage of all test takers for the intended college major|
|total_sat_score|integer|2019 SAT Scores by Intended College Major|The total SAT score the testtaker achieved (combination of reading/writing and math scores)|
|reading_and_writing_score|integer|2019 SAT Scores by Intended College Major|The score the student achieved on the reading/writing section of the SAT|
|math_score|integer|2019 SAT Scores by Intended College Major|The score the student achieved for the math section of the SAT|
|name_of_school|object|Ranges of Accepted ACT & SAT Student Scores by Colleges|The name of the university/college in the USA|
|number_of_applicants|integer|Ranges of Accepted ACT & SAT Student Scores by Colleges|The number of students that have applied to the school in the year|
|rate_of_acceptance|float|Ranges of Accepted ACT & SAT Student Scores by Colleges|The rate at which students are accepted (where 1.0 is 100% and 0.04 is 4%)|
|sat_score_25th_percentile|float|Ranges of Accepted ACT & SAT Student Scores by Colleges|The 25th percentile of the range of SAT scores that were accepted for student's admission into the program|
|sat_score_75th_percentile|float|Ranges of Accepted ACT & SAT Student Scores by Colleges|The 75th percentile of the range of SAT scores that were accepted for student's admission into the program|
|median_sat_score|float|Ranges of Accepted ACT & SAT Student Scores by Colleges|The median of the accepted SAT scores, half of the accepted marks were above this score and half of the accepted scores were below this score|
|act_score_25th_percentile|float|Ranges of Accepted ACT & SAT Student Scores by Colleges|The 25th percentile of the range of ACT scores that were accepted for student's admission into the program|
|act_score_75th_percentile|float|Ranges of Accepted ACT & SAT Student Scores by Colleges|The 75th percentile of the range of ACT scores that were accepted for student's admission into the program|
|median_act_score|float|Ranges of Accepted ACT & SAT Student Scores by Colleges|The median of the accepted ACT scores, half of the accepted marks were above this score and half of the accepted scores were below this score|

### Conclusions

In conclusion, the data analysis provides insights on the SAT scores the students should aim to achieve in order to gain acceptance into their preferred choice of university. This data is beneficial as it helps them set goals better. The two data sets studied were SAT scores by intended college major and accepted SAT score ranges by US colleges. 

Choosing an major and college is an excruciating decision; a decision that affects the next course of their life. This data allows them to understand which fields are the most competitive and which schools are the most popular. Knowing this allows them to know what marks they need to achieve for their preferred field and college, and if they have their scores, it helps them know what colleges they should apply for.

### Recommendations
Firstly, students should be advised to not significantly priortize the prestige of a university, rather they should be advised to prioritize the ranking of the program. Research shows that the prestige of the university does not significantly correlate to the quality of education. Though students may have a dream university based on its prestige, this dream can lead to them being significantly dissapointed as success rate of acceptance decreases as prestige increases. In addition, the benefits may not outweigh the cons. While prestige provides a recognizable name, these schools are also significantly more expensive and may not live up to their expectations.

Furthermore, students need to apply to a range of schools which vary in their accepted SAT score levels. While having a dream college they aim for is important, it is also necessary that they apply for 'safety' schools; schools that will accept them earlier on in the year. This will reduce stress as they will be certain of attending college next year even if it not their first choice. Students can use this data to understand what schools are likely to accept them and which are not. This will save them time, money and dissapointment.

Finally, students should take both the SATs and ACTs, they should submit whichever one is the most highest. The data shows both the accepted ranges for ACT and SAT, using these ranges, students can know which score is best to submit.