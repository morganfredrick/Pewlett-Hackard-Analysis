# Pewlett-Hackard-Analysis
## Overview 
The purpose of this project is to perform analysis on a large-scale of employee data for a company with over 300,000 employees by creating two tables: one to determine the number of retiring employees and their position titles, with the other identifying employees who are eiligible to participate in a mentorship program. The company Pewlett Hackard is reviewing staffing metrics and is in need of assistance managing the data that will help organize this information. 

## Results
Within the first table, we included information such as employee number, first and last name, position title, and start and end date. This first table determines the number of retiring employees and their position titles:

![image](https://user-images.githubusercontent.com/104293158/176594055-1c67a858-b13f-494e-88aa-8e77322bb74f.png)

<sup> The full table can be viewed here: [retiring_titles.csv](https://github.com/morganfredrick/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv) </sup>

In the second, we added employee number, first and last name, birth date, start and end date, and position title. This second table identifies employees who are eligible for the mentorship program:

![image](https://user-images.githubusercontent.com/104293158/176594494-8122780c-ae6e-4b33-afc6-0c8645829881.png)

<sup> The full table can be viewed here: [mentorship_eligibility.csv](https://github.com/morganfredrick/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv) </sup>


From these tables, we can see that there are four key takeaways:
- Of the 300,024 employees within the company, 90,398 (30.13%) are eligible for retirement. Senior Engineer and Senior Staff hold the largest share of employees likely preparing for retirement, almost two-thirds of all the retirees.
- As a result, Senior Engineer and Senior Staff positions have the greatest priority when it comes to deciding which roles the company would like to fill.
- Among those that are retiring, there are 1,549 employees that qualify for the mentorship program.
- There are more people retiring than there are potential mentors, which means that the company would have to create an efficient program that can cover the disparity between the number of people retiring and the number of people who can be trained to fill these positions.

## Summary
To determine how many roles will need to be filled as the "silver tsunami" begins to make an impact, we can create a graph to categorize the retirees into age groups. For each year, the company can hire (internally or externally) the amount of people that would be retiring, assuming that the retirement age is 65. Currently, we have a list of people who were born between 1952 and 1955. Therefore, we would have a different hiring quota for each of the following four years.

Based on the current projection of potential mentors and the amount of people retiring, over 90,000, the company does not have enough retirees to mentor the next generation of employees. Moving forward, the company can prioritize how many younger employees need to be trained to fill the retired positions each year. With the deficit of eligible mentors, it would also be beneficial if we created a query where the company can plan how many mentees a mentor can take on to fulfill the retired roles for an efficient mentorship program. 
