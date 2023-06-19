# DataScienceProject
1. Python version: 3.10.12 via google colab
2. Dependencies
	pandas
	sklearn
	matplotlib
	seaborn
	scipy
3. No additional setup required.
4. Process:
	Task1: Excel
		* Required Pivot table is added in the Pivot Table sheet of the EXCEL_TASK file.
		* The required column is added in the first sheet.
		* FILTER AND SORT BY INCOME sheet contains information with top 10 persons highest income and sorted by income.
		* Conditional Formating sheet contains some conditional formating on Income. Red for 0 income and Green for earning
		more than 50k.
		* Additional Pivot Tables contains some more pivot table and corresponding pivot charts are in the CHARTS sheet.
	Task2: Python
		* The data is extracted as explained in the instructions and imported in python.
		* ID column is omitted.
		* Data values are encoded manually.
		* Kmeans clustering performed based on divisions only. Considering the division only, the cluster results is not good.
		It only shows the divisions already have. 
		* Kmeans clustring performed with all the variables. This creates groups based on similar characteristics.
		The result is useful for customer segmentation process.
		* Grouping and aggregations have been perfomed on Income with Division, Age groups and Marital status.
		* Some visualizations has been added to visualize the insights.
		* Hypothesis testing has been added using ANOVA to observe if there any difference of Income in different Divisions.
		
