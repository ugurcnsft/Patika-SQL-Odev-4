1#SORU - film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.

1#CEVAP - SELECT DISTINCT replacement_cost FROM film;

1#<img width="960" alt="1" src="https://user-images.githubusercontent.com/129968939/230695401-5af0dd36-1052-4ea1-8bf8-c4dc8570147b.png">

2#SORU - film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?

2#CEVAP - SELECT COUNT (DISTINCT replacement_cost) FROM film;

2#<img width="960" alt="2" src="https://user-images.githubusercontent.com/129968939/230695474-bb1b8c03-0eca-416f-8915-2bb82ddc7d32.png">

3#SORU - film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?

3#CEVAP - SELECT COUNT (*) FROM film
WHERE title LIKE 'T%' AND rating = 'G';

3#<img width="960" alt="3" src="https://user-images.githubusercontent.com/129968939/230695690-a2a4eb4a-bb61-41b1-a9b0-16118ca2e827.png">

4#SORU - country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?

4#CEVAP - SELECT COUNT (*) FROM country
WHERE country LIKE '_____';

4#<img width="960" alt="4" src="https://user-images.githubusercontent.com/129968939/230696308-acecec62-dda2-4898-a1e6-8da66e6f0c49.png">

5#SORU - city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?

5#CEVAP - SELECT COUNT (*) FROM city
WHERE city ILIKE '%r';

5#<img width="960" alt="5" src="https://user-images.githubusercontent.com/129968939/230696396-bfd3cf2c-a516-489a-9cdd-eb361dc63de1.png">
