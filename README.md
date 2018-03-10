# Popularity and Substance Use among Adolescents

Public health researchers have long been concerned about the effect of peer pressure and social networks on adolescents’ use of alcohol, tobacco, and drugs. The National Survey of Adolescent Health (Add Health) provides an important opportunity to study such effects because it contains data on both substance use and students’ social networks. Students were asked to nominate their closest friends within the same school. We can use this information to construct a measure of poplarity by counting the number of friend nominations each student received. We will use Add Health data to address the following research questions:

1. How does smoking and alcohol use affect a student’s popularity, as measured by the number of friend nominations received?
2. How does substance use (alcohol and tobacco) affect the relationship between sports participation and popularity?

For both questions, you should consider control variables for student race, gender, academic performance, and extra-curricular activities.

The Add Health data we will use are provided in the `input` directory as a RData file. The README in that directory also contains further information about the survey and the variables that we will use. 

## Performing the analysis and producing the report

You can use either a separate script or an R Markdown file to perform your analysis, but the ultimate report should be written up using an R Markdown file. This R Markdown file should be knitted to a PDF file which you will upload to the Canvas site. You should also be sure to commit and push your final code and results back to GitHub. I will be evaluating both your written work and the analysis itself.

The report will typically be around 5-7 pages including figures and tables. The report should have the following format:

- **Introduction**: state the research question (in your own words). This is also a good place to indicate why this is an interesting research question. Use your sociological imagination here. 
- **Data and methods**: describe the data (where it came from, how variables were constructed, how big the sample is, etc.). You may use the report provided on each dataset to help craft this description, but **you must describe it in your own words**. You should include graphical presentations of the distribution of the dependent variable and the critical independent variable(s). 
- **Results**: Report what you found. Typically, this will involve a figure or multiple figures showing the key relationship (e.g. scatterplot, comparative boxplots, etc) and a table of regression model results. Be sure to interpret your results in straightforward concrete terms. Your results table(s) should include measures of statistical significance such as the standard error and an asterisks if the p-value was less than 0.05. Round all values in the table(s) to three decimal places. 
- **Conclusions**: Summarize the findings and discuss any weaknesses or ideas for future research.

All tables and figures should be well captioned and self-explanatory. I should be able to understand what the table or figure is reporting without reading the report itself. 