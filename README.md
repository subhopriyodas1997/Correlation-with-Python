# Correlation-with-Python

## Tools Used

![icons8-python-48](https://github.com/user-attachments/assets/ea93035b-65cb-4d87-846a-7a627c6b526f)

![icons8-project-jupyter-a-nonprofit-organization-created-to-open-source-software-24 (1)](https://github.com/user-attachments/assets/f5abb1b3-c462-419b-a5e2-a2b254a4848e)

## Introduction

To find the correlation for a movies data set with respect to the different numerical factors such as the Budget, IMDB Score, gross earnings and runtime.
## Methodology


	• We import relevant python libraries such as pandas, numpy, seaborn matplotlib and finally the data file.
	• We look at the data types.
	• We change data types to facilitate numerical calculations and avoid errors.
	• We remove duplicates.
	• We create a boxplot to check for outliers.
	• We create regression plots that help us create a hypothesis that there is indeed a correlation between gross earnings & budget.
	• We create a heatmap using seaborn to affirm our hypothesis and more easily spot all the highly positive correlated factors and the negative ones with the help of colour grading.
	• We unstack the factors from the heatmap and sort them in descending order only for values > 0.5 to shorten our list and easily focus on the most impactful factors.


## Findings


	• [Gross & Votes], [Gross & Budget], [Votes & Budget] have highest, second highest and third highest positive Correlation in the order they have been written in. 
	• Budget & Score have a negative correlation.
