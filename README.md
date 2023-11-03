This research involved tracking tumor growth in 249 mice diagnosed with SCC tumors and treated with various drugs over 45 days. The focus was to evaluate Capomulin, a drug developed by Pymaceuticals, against other regimens. A comprehensive analysis of the study's outcomes was conducted as part of this project.

Workflow for the project included:

Data Preparation: Involved consolidating mouse_metadata with study_results into a singular DataFrame, identifying unique mouse IDs, filtering duplicates, and cleaning the dataset for analysis.

Summary Statistics Generation: A statistics summary DataFrame was created, listing mean, median, variance, standard deviation, and SEM of tumor volumes for each drug regimen.

Visualization with Bar and Pie Charts: Produced two identical bar charts showing the count of time points per drug regimen, using both Pandas and Matplotlib. Also, two identical pie charts were created to depict the gender distribution of the mice, again utilizing both Pandas and Matplotlib for implementation.

Quartile Calculations, Outlier Identification, and Box Plot Creation: Determined the final tumor volume for mice across the four most promising treatments, calculated quartiles and IQR, and identified outliers. A box plot visualizing the distribution of tumor volumes by treatment was then crafted, with outliers highlighted.

Line and Scatter Plot Construction: Developed a line plot of tumor volume over time for a single Capomulin-treated mouse and a scatter plot illustrating the relationship between tumor volume and mouse weight under Capomulin treatment.

Correlation and Regression Analysis: Calculated the correlation coefficient and developed a linear regression model to map the relationship between mouse weight and average tumor volume for Capomulin-treated mice, overlaying the regression model onto the scatter plot.

Techniques and Tools Used:

Jupyter Notebooks for scripting and analysis.
Groupby function for aggregating data.
For-loops for iterating over data sets.
Matplotlib for generating plots.
Pyplot for chart settings.
Linear Regression for statistical modeling.



