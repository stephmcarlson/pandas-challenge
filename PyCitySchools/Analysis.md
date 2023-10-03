# pandas-challenge

15 schools were analyzed in this data set with a total enrollment of just over 39,000 students. The schools have a total budget of approximately $24.5M leading to an average of approximately $629 per enrolled student.

The average math score for the district, comprised of the 15 schools, came in just shy of 79 which is slightly under the average reading score of approximately 82. Even though the average scores are quite close in value, only about 75% of students passed math while 85% passed reading. Unfortunately, only 65% of students were able to pass both subjects.

Within the data set, the best performing schools as rated by % Passing Overall were all Charter schools, while the worst performing schools were all District schools. 

When reviewing the % Passing Overall between these types of schools, Charter vs. District, there is a large difference with Charter schools having approximately 90% of the student population passing both subjects compared to the District schools were only 53.7% of the students passed both Math and Reading. This difference is substantially impacted by the Math portion of the test. 

While District schools Average Math Score and Reading Score do not seem vastly different, 77 in Math and 81 in Reading, the % Passing Math for these schools was only approximately 67% vs. approximately 81% of students passing reading. One potential explanation could be that the Average Math score had more variability with high side outliers skewing the Average score up but leading to only 67% of students passing math. The lower % Passing Math is also the variable pulling down the % Passing Overall to be 53.7% when looking at both together.

Interestingly, when analyzing the data based on Per Student Spending, higher spending levels have an inverse relationship to the % of students passing overall. This is again due to the School Type since Charter schools receive less funding on average than a District school.

Finally when analyzing by School Size, schools with up to 2,000 students have similar overall passing rates, around 90%, however "large" schools with between 2,000 and 5,000 students have a substantially reduced passing rate of only 58%. Again this is driven by the composition of these schools being District schools as all District schools are "large" in size. 

While we only have one point of data, a "large" Charter school performs similar to the average for Charter schools, suggesting school size cannot entirely explain the difference between test scores in District vs. Charter schools. Expanding the data set to include another set of schools with variability in the size of the "District" schools could lead to interesting analysis on how the size of a school impacts these test scores, however based on the provided data, type of school is the driving factor of these differences.
