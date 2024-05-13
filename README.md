# Problem Statement

This dashboard helps us to understand salary benchmarks by job title/region to help negotiate better pay.
Highlight popular programming languages for different data roles to guide learning.
Identify factors contributing to better work-life balance and job satisfaction.
Develop a roadmap for breaking into data roles, including education/training options.
Analyze demographic differences to promote diversity.
Recommend continuous learning resources and career progression paths.

This analysis can help:

People interested in data careers understand salary expectations, popular skills, and difficulty of getting into the field and get guidance on entering and advancing in data roles.

Helps,companies hiring data professionals learn,what data talents value in employers as work-life balance, growth opportunities and improve strategies to attract and keep top data talent.

Helps the data industry as a whole to identify areas that need improvement in resources for newcomers.
Focus on addressing challenges and meeting professionals needs.

### Steps followed 

- Step 1 : The dataset is a Excel file,Transform data into Power query editor .
- Step 2 : Check all the columns in the dataset it is observed that there are some empty columns that can be deleted straight away.
- Step 3 : Select the column "Browser" hit shift go over to the column "Referrer" and select remove columns in the Manage columns section in the File ribbon.
- Step 4 : By observing the column Q1 it has almost 50 title options, To clean this column,select the Q1 column and apply split column option in the file ribbon,split column->by delimiter->custom->type open parenthesis(-> left most delimiter and click ok.
- Step 5 : Its gonna create another column with the same column name , the contents of the column starts from the open parenthesis , now using remove columns in manage columns option we can delete this column which helps to filter the job titles from 50 to 7 titles.
- Step 6 :By following the same method we can clean the columns Q5,Q4,Q11
- Step 7 :To clean the column Q3 create a duplicate column for Q3 and split the duplicated column by digit to Non-digit , Now we have three columns one with only digits, one with K-digits , and the column with only k , we can directly delete the third column and for the 2nd column we can replace the 'k' and '-'  with empty space separetly.
- Step 8 : Now the data looks clean and ready for visualizations but we can always come back to the dat aand make the necessary chenages if required.
- Step 9 : Now open power Bi report and start creating the dashboard.
- Step 10: Add title to the dashboard using Textbox,A card visual was used to represent the count of Survey Takers.

![Numbers](https://github.com/sravyapaladugu/Project/assets/155795943/a88adec6-9f4c-4b07-815e-805aca20094d)

- Step 12 : Another card visual was created to represent the Average age of Survey Takers .

![Average age ](https://github.com/sravyapaladugu/Project/assets/155795943/586a47a2-b9dc-4c5d-82fa-c60e25a6c7b7)


- Step 13 : A stocked column chart was created to represent the Favouirte programming language with respect to the job title and the number of survey takers .

![Fav Language ](https://github.com/sravyapaladugu/Project/assets/155795943/ecf8c5b7-037e-4210-831f-9c6b7cd5f6f0)

- Step 14 : Used a Treemap to represent the country of survey takers .

![Country](https://github.com/sravyapaladugu/Project/assets/155795943/5dbae8b1-ca25-4952-9a55-690dee27ec42)

- Step 15 :A stacked Bar chart was used to represent the Average salary by Job Title 

![Average Salary ](https://github.com/sravyapaladugu/Project/assets/155795943/54cb92cf-351f-40ba-9758-b1a9a37e64e9)

Snapshot of Dashboard (Power BI Service)

![Dashboard](https://github.com/sravyapaladugu/Project/assets/155795943/1ea1033a-7045-4dc3-a5f3-c72c67597744)

Insights
A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

[1] Total Number of Surevy Takers = 638

[2] Average age of Surevy Takers = 29

[3] Favouirte programming Language by job title 

- Python is the most popular
- Followed by R, Other languages, C/C++, JavaScript, Java
- Morethan 50% of the data analysts selected python as their favourite programming language and over 15% of them selected 'R' and another 15% of them selected other languages and a little amount of them selected C/C++ as their favourite programming language.
























 
