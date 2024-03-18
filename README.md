Problem Statement - Talent Hunt Examination Case Study
Business Context
A research institute conducts a Talent Hunt Examination every year to hire people who can work on various research projects in the field of Mathematics, Physics, Chemistry and Computer Science. A2Z institute provides a preparatory program to help the aspirants prepare for the Talent Hunt Exams. The institute has a good record of helping many students clear the exams. Before the application for the next batch starts, the institute wants to attract more aspirants to their program. For this, the institute wants to assure the aspiring students of the quality of results obtained by students enrolled in their program in recent years.

However, one challenge in estimating an average score is that every year the exam’s difficulty level varies a little, and the distribution of scores also changes accordingly. However, it is known that the standard deviation of the scores of the students of the institute is 10. The institute keeps a track of the scores of various subjects for its alumni who attempted the exams previously. A dataset constituted of a simple random sample of scores of 600 aspirants from the last three years is prepared by the institute.

Objective
The institute wants to get a more robust measure of the average scores secured by the students that accounts for the variability in scores across different years. This will help them get a better picture of the overall performance of the students and the information can also be used for marketing purposes.

A renowned critic has recently taken to social media to mention that the institute's preparation material for Physics and Mathematics do not have the required rigor and that students, on average, failed to clear the cut-off of 82 in these subjects last year. The institute wants to verify the validity of the critic's claim and then respond to him. The goal is to determine whether there is significant evidence to support the claim that the average scores in Physics and Mathematics are lower than the specified cut-off.

In light of the recent increase in revenue of the institute, an investor believes that the increase is driven by an increasing amount of students clearing their exams in Computer Science and Chemistry in the last year. The institute wants to check if the investor's belief in factually correct and share an update. The aim is to assess whether there is significant evidence to support the claim that the average scores in Computer Science and Chemistry are higher than the cut-off score of 85.

Solution Approach
To provide a more reliable estimate of the average scores: We will construct a 95% confidence interval for the mean scores of students in Physics, Mathematics, Computer Science, and Chemistry who have enrolled in the institute's program. This approach offers a comprehensive range of scores, providing a robust estimate.
Critic's Claim: To investigate the critic's claim that the mean scores of students in Physics and Mathematics are less than the previous year's cut-off of 82, we will perform a hypothesis test at a significance level of 5%. The null hypothesis will assume that the mean scores are equal to or greater than 82, and the alternative hypothesis will suggest that the mean scores are less than 82.
Investor's Claim: To assess the investor's claim that the mean scores of students in Computer Science and Chemistry are higher than or equal to the most recent cut-off of 85, we will conduct a hypothesis test at a significance level of 5%. The null hypothesis will assume that the mean scores are equal to or less than 85, and the alternative hypothesis will suggest that the mean scores are greater than 85. These tests will provide statistical evidence to validate or refute both the critic's and investor's perspectives, contributing to a comprehensive evaluation of the institute's performance.
 

Data Description
The dataset provided (talent_hunt_scores.csv) contains the scores of four subjects of 600 aspirants enrolled in the institute's programs in the last three years. Each row in the dataset corresponds to a different student, and the values in each column indicate the respective performance scores of that student in the specified academic program.

Computer_Science: This column contains numerical values representing the performance scores of students in the Computer Science program.

Chemistry: This column contains numerical values representing the performance scores of students in the Chemistry program.

Mathematics: This column contains numerical values representing the performance scores of students in the Mathematics program.

Physics: This column contains numerical values representing the performance scores of students in the Physics program.
