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

https://user-images.githubusercontent.com/78714438/183733725-376d8bd9-5167-4a96-ba64-f22b62a82ebc.svg
