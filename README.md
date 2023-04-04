# Patika_PostgreSQL_odev1

## [Patika.dev](www.patika.dev)

## 1. film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.

`SELECT title, description FROM film`

## 2. film tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.

`SELECT * FROM film`<br>
`WHERE length > 60 AND length < 75;`

## 3. film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99 VE replacement_cost 12.99 VEYA 28.99 olma koşullarıyla sıralayınız. <br> 
![odev1_part1](https://user-images.githubusercontent.com/36984017/228911023-47bc675d-f251-4194-8ce5-aa570bfade49.png)
<br>

## 4. customer tablosunda bulunan first_name sütunundaki değeri 'Mary' olan müşterinin last_name sütunundaki değeri nedir?<br>

![odev1_part2](https://user-images.githubusercontent.com/36984017/228911234-5c87603c-1260-4ead-b051-9302dbae4203.png)

<br>

##  5. film tablosundaki uzunluğu(length) 50 ten büyük OLMAYIP aynı zamanda rental_rate değeri 2.99 veya 4.99 OLMAYAN verileri sıralayınız.

![odev1_part3](https://user-images.githubusercontent.com/36984017/228918394-78a6c297-29a9-4265-8df7-dd37d0ce2c25.png)
