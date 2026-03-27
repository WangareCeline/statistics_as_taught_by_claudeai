# statistics_as_taught_by_claudeai
Iris Petal Length Statistical Analysis  
This repository contains a Python-based workflow for performing exploratory data analysis (EDA) and hypothesis testing on the classic Iris dataset. The goal is to determine if petal length varies significantly across the three species (Setosa, Versicolor, and Virginica).

Project Overview  
The analysis follows a rigorous statistical pipeline:

Data Loading: Importing the Iris dataset via sklearn.

Assumption Testing: Evaluating normality (Shapiro-Wilk) and homogeneity of variance (Levene’s Test).

Hypothesis Testing: Executing the Kruskal-Wallis H-test to compare species.

Post-hoc Analysis: Performing a Tukey HSD test to identify specific differences between groups.

Visualization: Generating boxplots to visualize distributions.

Prerequisites  
Ensure you have Python 3.8+ installed. You will need the following libraries:

pandas  
numpy  
scikit-learn  
scipy  
statsmodels  
matplotlib  

Installation
Clone this repository and install the required packages:

Bash  
pip install pandas numpy scikit-learn scipy statsmodels matplotlib   

How to Run    
The analysis code is saved as phase_4_final_project.ipynb  
For this file I used vs code.  
To run the script using your vs code:    
- Ensure the Kernel is Set   
In the top-right corner of your VS Code editor, make sure you have selected a Python Kernel (it should show your Python version, e.g., Python 3.10.x). If it says "Select Kernel," click it and pick your installed Python environment then run it.

Results Summary  
The analysis confirms that petal length is a statistically significant differentiator for Iris species ($p < 0.05$).Setosa: Smallest petals with the least variance.Versicolor: Medium-sized petals.Virginica: Largest petals.Post-hoc testing (Tukey HSD) shows that all pairs of species are significantly different from each other.
