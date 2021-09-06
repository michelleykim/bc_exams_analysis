# bc_exams_analysis
## STAT 201

Inequality of quality of education and achievement imbalance in public and private/independent schools students was seen in many different countries including the USA, Mexico, and China. Canada spends more than 5% of the federal budget on public education, recording one of the highest in the world. Private schools, in general, are thought to provide a better education than public schools. Due to the high tuition cost, independent schools may have better resources and more qualified teachers. Public schools may have larger class sizes, so students may have less support in their learning. So, we became curious if we can observe a similar phenomenon in Canada, particularly BC, where the students from independent schools showcase higher academic achievement than in public schools.

Question: Are English 12 marks higher in independent schools in BC compared to public schools?

Random variable: average mark per school (%)

Categorical variables: BC public school vs independent school

Location parameter: difference in mean (if average marks are higher in private vs public schools)

Scale parameter: standard deviation (can be used to find confidence interval and shows the spread of the data)

Our dataset is from the BC Ministry of Education and shows examination results from 2016-2020. The dataset contains several important columns for our analysis:

PUBLIC_OR_INDEPENDENT (type of school, independent/public)
EXAM_SUBJECT (includes 4 language course types, such as English 12)
MARK_TYPE (type of mark given, e.g. final marks or exam marks)
AVERAGE_PERCENT (the average percentage in a school)
We decided to look at final marks, which are the final marks for each course blending exam results and course results, to get the full picture of student scores. The only course types available were language courses, so we also focused on English 12 because it was the most commonly taken compulsory grade 12 course in BC, compared with other courses, such as Français 12, which is only offered in French Immersion schools.
