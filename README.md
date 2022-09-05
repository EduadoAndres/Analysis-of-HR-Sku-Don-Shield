# Analysis-of-HR-Sku-Don-Shield

Analysis of HR Sku-Don Shield
It is sought to visualize indicators of Collaborators, Salaries and Performance with the use of a Human Resources Report of the (fictitious) SKU-DON company. This report needs to be shared to users via a web link. It is required to analyze:

Analysis by employee (Table).
Total employees (Count).
Average Age, Salary and Performance.
Total costs for Salaries, Relationship-Salary age.
Max-Min performance evaluation by boss.
There is a dataset Data + Employees, it has 3 tables Employees, Evaluation and Salary

With few transformations in Power Query the tables are loaded

![image](https://user-images.githubusercontent.com/112581327/188506315-8546d0a7-7047-4e2b-b476-10df63ea4a78.png)


transformations

![image](https://user-images.githubusercontent.com/112581327/188506400-b5a91223-36f0-44af-a4c2-7823a1227886.png)
Table 2 - Salaries

![image](https://user-images.githubusercontent.com/112581327/188506496-7f73f57a-07b1-4c69-a2c7-15e193340e87.png)
transformations

![image](https://user-images.githubusercontent.com/112581327/188506541-1c5bffea-15cb-431e-8cff-a2cc808565df.png)
Table 3 - Evaluations
![image](https://user-images.githubusercontent.com/112581327/188506643-af760cff-4a19-44a1-8345-9948a963a1df.png)
transformations

Calculations with DAX
3 columns calculated with DAX are generated, one for each table:

Age Range

![image](https://user-images.githubusercontent.com/112581327/188506900-ae89de95-177a-444b-93c2-fb579a4138d4.png)
Salary range
![image](https://user-images.githubusercontent.com/112581327/188506980-cad5bdfd-c6c8-45bb-a4f0-7251a8a70b2e.png)
Rating Range
![image](https://user-images.githubusercontent.com/112581327/188507017-321fade2-4349-4c1e-bce9-9f097bf1785b.png)

A table called _Medidas is also created, where 4 measures are created:
![image](https://user-images.githubusercontent.com/112581327/188507073-724db8ac-aff8-4d9f-a04f-bae59afd3aea.png)

reports
With these 3 tables, 3 reports are made
Report 1 - Employee Analysis
It is composed of 4 Cards and 7 Visualizations:

cards
Total Employees.
Average age.
Average salary.
Average evaluation.
visualizations
Donut chart, detailing the proportion of employees by Gender.
Map, detailing the number of employees by State.
Bar graph, Age Range.
Bar chart, Salary Range.
Bar graph, Evaluation Range.
Column chart, detailing the number of employees by Department.
Table, with the detail of all employees.

![image](https://user-images.githubusercontent.com/112581327/188507176-ac706d90-d5e5-489e-ae75-02948438eecb.png)

Report 2 - Salary Analysis
It is made up of 3 Cards and 5 Visualizations:

cards
Total Employees.
Total Salary.
Average salary.
visualizations
Donut chart, detailing the proportion of employees by Salary and Gender.
Map, detailing the Total Salary by State.
Dispersion graph, evaluating the relationship between the age of the employees and the Salary.
Column graph, with details of the Average Salary by Department.
Table, with the detail of all employees.

![image](https://user-images.githubusercontent.com/112581327/188507256-c5d3f5a2-ee38-43e6-8e9c-f3c617051638.png)

Report 2 - Performance Analysis
It is composed of 4 Cards and 5 Visualizations:

cards
Total Employees.
Maximum Evaluation.
Minimum Evaluation.
Average evaluation.
visualizations
Map, detailing Assessments by State.
Bar graph, evaluating the average performance of employees by direct Manager.
Column graph, with detail of the average Evaluation by Gender.
Column graph, with detail of the average Evaluation by Department.
Table, with the detail of all employees.

![image](https://user-images.githubusercontent.com/112581327/188507332-ba69ef07-539b-498d-8edf-3f4cf3eafbf1.png)

