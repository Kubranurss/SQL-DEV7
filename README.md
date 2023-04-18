# SQL-DEV7
ÖDEV 7
SORU-1
select rating from film group by rating

SORU-2
select count(replacement_cost) from film 
group by replacement_cost 
having count(replacement_cost)>50

SORU-3
select store_id, count(store_id) from customer group by store_id

SORU-4
select country_id, count(country_id) from city 
group by country_id order by count(country_id) desc limit 1
