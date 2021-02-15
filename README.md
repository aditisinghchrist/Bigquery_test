SELECT 
AVG(new_confirmed)
new_confirmed,
FROM `bigquery-public-data.covid19_open_data.covid19_open_data` LIMIT 10


SELECT country_name
date,
new_recovered,
new_tested,
new_deceased,
FROM `bigquery-public-data.covid19_open_data.covid19_open_data` LIMIT 10


SELECT region_name,
total_current_confirmed_cases,
new_total_confirmed_cases,
deaths,
FROM `bigquery-public-data.covid19_italy.data_by_region` LIMIT 10



SELECT
SUM(total_hospital_beds),
FROM `bigquery-public-data.covid19_aha.hospital_beds` LIMIT 10
