SELECT
date,
location_key,
country_code,
country_name,
subregion1_name,
subregion2_name,
aggregation_level,
population,
area_sq_km,
latitude,
longitude,
cumulative_confirmed,
new_confirmed
FROM `bigquery-public-data.covid19_open_data.covid19_open_data`
WHERE country_name= 'Indonesia'
ORDER BY 1 DESC 
