# School and community features associated with low income student success

Low income students face academic challenges that affect long-term employment and upward social mobility. Fortunately, some schools provide environments for low income students to thrive. In this project, I investigated features of California (CA) public high schools and their communities that may affect low income student performance. I focused on a school’s percentage of low income students that are college eligible (SPLICE). College eligibility here is defined as meeting the subject and grade requirements for the University of California or California State University systems. To obtain school-specific features, I acquired data from the CA public schools database and GreatSchools websites. This was supplemented with local characteristics from the census. Following data exploration and filtering, I built classification models to predict schools with exceptional SPLICE. Exceptional SPLICE is defined as a school achieving greater than one standard deviation above mean SPLICE across all CA high schools. A regularized logistic regression model outperformed random forest classification. Based on the logistic regression coefficients and two-sample hypothesis testing, I find that schools with exceptional SPLICE are more likely to:

1. Have a high percentage of non-low income students that are also college eligible.
2. Have a high percentage of low income students that scored proficiently in English and math (although interestingly English proficiency was a better predictor.)
3. House a smaller student population, but not necessarily have a smaller student-to-teacher ratio.
4. Be a charter school.
5. Staff a lower percentage of certified teachers.
6. Be located in the Bay Area or a Southern California coastal county compared to the rest of the state.

This study highlights policy implications, pointing to some unexpected areas of investigation for facilitating low income student success.

I wrote an article and posted it to [Medium](https://medium.com/@ben.lacar01/school-and-community-features-associated-with-low-income-student-success-42797cd6baad).

The initial version of this article will remain on my personal website [here](https://benslack19.github.io/projects/0_CA-SPLICE/). It includes more details, especially with the Methods.