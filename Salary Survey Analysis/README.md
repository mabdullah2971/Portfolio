# Salary Survey Analysis
* **Skills:** Data Cleaning, Data Visualization. <br>
* **Tools:** Python and its libraries - Pandas, NumPy, Matplotlib, Seaborn.

Performed data analysis on the `SalarySurvey2021.csv` dataset which contains the responses of the [Ask A Manager Salary Survey 2021](https://www.askamanager.org/2021/04/how-much-money-do-you-make-4.html).

## Objectives:
1. Which industries pay the most?
2. How does salary increase given years of experience?
3. How much do salaries differ by gender?
4. How does education level correlate with salary?
5. How does race correlate with salary?

## Code Files:
[`data_cleaning.ipynb`](https://github.com/mabdullah2971/Portfolio/blob/main/Salary%20Survey%20Analysis/data_cleaning.ipynb)
[`data_analysis.ipynb`](https://github.com/mabdullah2971/Portfolio/blob/main/Salary%20Survey%20Analysis/data_analysis.ipynb)

The dataset underwent cleaning and preprocessing before analysis. The data cleaning involved extensive code, so I separated the 
cleaning process into its own file. This allowed me to keep the analysis code clean and focused on the actual analysis 
without the data preparation details. The code files include the explanations behind the methods used to meet the stated objectives.

## Results:

### 1. Which industry pays the most?
![avg_sal_per_industry.png](https://github.com/mabdullah2971/Portfolio/blob/main/Salary%20Survey%20Analysis/img/avg_sal_per_industry.png) <br>
The bar chart shows industries ranked by their average annual salaries, with Computing & Tech at the top earning the most and Social Work at the bottom earning the least.

### 2. How does salary increase given years of experience?
![avg_sal_vs_exp.png](https://github.com/mabdullah2971/Portfolio/blob/main/Salary%20Survey%20Analysis/img/avg_sal_vs_exp.png) <br>
We can see that as experience increases, annual salary also increases upto 21-30 years. After that, it seems that the annual salary decreases slightly. Possible reasons for this could include a saturation of skills, changing job roles, or market dynamics, where older workers may be replaced by younger, lower-cost employees.

### 3. How much do salaries differ by gender?
![avg_sal_vs_gender.png](https://github.com/mabdullah2971/Portfolio/blob/main/Salary%20Survey%20Analysis/img/avg_sal_vs_gender.png) <br>
The interquartile range for 'Men' starts at a higher salary compared to 'Women' and 'Non-binary' individuals. This suggests that 'Men' typically have higher earnings, while 'Non-binary' individuals tend to have the lowest earnings.

When investigating further, it is found that in the top 10 highest paying industries, the percentage of -
* men is 14.15%
* women is 38.86%
* non-binary people is 1.28%

The boxplot showing that men earn the most could be due to the following reasons -
* There could be seniority differences within the same industries. If men tend to hold more senior/higher paying roles than women within the same industries, that would lead to higher overall pay.
* There may be differences in the number of hours worked between men and women. For example, if women are more likely to work part-time, their overall earnings would be lower.
* The industries women dominate in the top 10 may have a wider distribution of salaries, bringing down the median earnings compared to men.
* There could be pay discrimination affecting women's earnings across industries, beyond just representation differences.

### 4. How does education level correlate with salary?
![avg_sal_vs_edu.png](https://github.com/mabdullah2971/Portfolio/blob/main/Salary%20Survey%20Analysis/img/avg_sal_vs_edu.png) <br>
The bar chart reveals a subtle upward trend in average annual salaries as education levels advance. This observation aligns with the computed correlation coefficient of approximately 0.056, signifying a weak positive linear relationship between educational attainment and income.

### 4. How does race correlate with salary?
![avg_sal_vs_race.png](https://github.com/mabdullah2971/Portfolio/blob/main/Salary%20Survey%20Analysis/img/avg_sal_vs_race.png) <br>
A correlation coefficient of -0.466 indicates a moderate negative correlation. This means that as you move from one race category to another, you are likely to see changes in average annual salary, with some races having lower average salaries than others. However, it's important to remember that correlation does not imply causation. This correlation does not indicate a causal relationship between race and salary but rather suggests an association or pattern in the data.

To fully understand the relationship between race and salary, you would need to consider other factors, such as education, experience, location, and industry. Additionally, addressing issues related to potential bias and discrimination in employment is crucial when interpreting such correlations, as various external factors can influence salary disparities among different racial categories.
