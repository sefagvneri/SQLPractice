1. SELECT title, rating FROM film GROUP BY title, rating ORDER BY rating
2. SELECT replacement_cost, COUNT(title) FROM film GROUP BY replacement_cost HAVING COUNT(title) > 50 ORDER BY replacement_cost DESC
3. SELECT store_id, COUNT(*) FROM customer GROUP BY store_id
4.
