# Big-Query-Assignment
Code No. 1 
SELECT age as Age,functional_weight as Importance, education_num as TotalEducationYear  FROM `bigquery-public-data.ml_datasets.census_adult_income`
where age > 30 
limit 5

Code No. 2 
SELECT AVG(hours_per_week)  FROM `bigquery-public-data.ml_datasets.census_adult_income` 
where age > 40
LIMIT 1000

Code NO. 3
SELECT count( hours_per_week) FROM `bigquery-public-data.ml_datasets.census_adult_income` 
where education_num > 5
LIMIT 10

Code No. 4
SELECT age as Age, functional_weight as FW,capital_gain as CG, hours_per_week as  HRW, capital_loss as CL   FROM `bigquery-public-data.ml_datasets.census_adult_income` 
where education_num > 5 and age > 30
order by age
LIMIT 10

Code No. 5
SELECT max(capital_gain)   FROM `bigquery-public-data.ml_datasets.census_adult_income` 
where age < 30 
LIMIT 5

Code No. 6
SELECT min(capital_gain)   FROM `bigquery-public-data.ml_datasets.census_adult_income` 
where age < 30 
LIMIT 5
