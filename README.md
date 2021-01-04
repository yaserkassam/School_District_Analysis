# School_District_Analysis
## Overview of the school district analysis: The purpose of this analysis is to find passing averages of schools in the district. We are helping a district in figuring out if certain instances affect a school pass math, reading, or the overall passing percentage.
## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
1.	How is the district summary affected?
-	District summary effect is in the total number of students that are actually counted because of the NaN scores to be 38,709 total student scores rather than the 39170
2.	How is the school summary affected?
-	The school summary is affected only when it comes to Thomas High School. Thomas High School number changes drastically going for % Passing Math, % Passing Reading, and % Passing Overall going from 66.9%, 69.7%, and 65.1% to 93.2%, 97%, and 90.6% respectively.

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High school preformance keeps them in the top 5 school preformances. If the ninth graders NaN scores were factored in it would have dropped them into the bottom 5. So they are showing high performance in % passing becuase the NaN counts are not bringing there scoring down.
## How does replacing the ninth-grade scores affect the following:
1.	Math and reading scores by grade
-	The math and reading scores are affected only for Thomas High school. The ninth-grade scores for both columns are now NaN so they have no value and will not be factored into the average.
2.	Scores by school spending
-	The scores by school spending are not affected by much because the number of ninth graders was not significant enough to alter the percentage.
3.	Scores by school size
-	The scores by school size also were not affected because the ninth graders scores that came invalid was only 461 total grades vs the 38,000+ that were still being calculated.
4.	Scores by school type
-	The scores for school type also were not affected possibly in the smallest % due to the total scores taken out, 461, will not affect the total of 38,000+ remaining values.
## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
There were four major changes that effected the updated school analysis. The first was the school counts because there were 461 less students the total school counts went down. The next was the % passing math scores for Thomas High School that changed to 93.2%. Next, was the % passing reading scores to 97%. Last was the % overall passing which changed to 90.6%.
