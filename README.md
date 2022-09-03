# MySQL - Manipulación y Consultas
## Desafio curso FullStack de Digital House

<a href="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/Desafio/diseñoTablas.pdf">IR AL PDF</a>

   
## Preview y Consultas del desafio finalizado
# PASO 1
### insert    into    genres(name,ranking,active)    values ('investigacion',13,1)
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/1.1.PNG">

### update    genres     set name = 'Investigacion Cientifica'   where id = 13 
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/1.2.PNG">
  
### delete from genres    where id = 13  
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/1.3.PNG">
  
### select * from movies
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/1.4.PNG">
  
### select first_name, last_name, rating    from actors
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/1.5.PNG">
  

### select title    from series   
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/1.6.PNG">
  
# PASO 2

### select first_name, last_name, rating    from actors    where rating > 7.5
[ ! ] se mostro el rating para demostrar que es correcta la instruccion   

<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/2.1.PNG">
  
  
### select title, rating, awards, rating    from movies    where rating > 7.5
[ ! ] se mostro el rating para demostrar que es correcta la instruccion
  
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/2.2.PNG">
  
  
### select title , rating    from movies    order by title    
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/2.3.PNG">
  
## PASO 3
  
### select title    from movies    limit 3
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/3.1.PNG">
  
  
### select *    from movies    order by rating desc    limit 5
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/3.2.PNG">
  

### select *    from movies    order by rating desc    limi 10    offset 5
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/3.3.PNG">
  

### select *    from actors    limit 10
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/3.4.PNG">
  

### select *    from actors    limit 10    offset 3
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/3.4A.PNG">
  
## PASO 4
  

### select title , rating    from movies    where title    like '%Harry Potter%'
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/4.1.PNG">
  
 
### select *    from actors    where first_name     like '%Sam'   
<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/4.2.PNG">
  

### select *    from movies    where release_date     between "2004-1-1" and "2008-1-1"

<img src="https://github.com/Kaiael24/DB_Modelos-Consultas/blob/master/images/4.3.PNG">
