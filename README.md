# EVALUACION_PRACTICA_SQL EjERCICIO CLASE 30


select * from notes;
delete from notes 
where id = 13;
insert into notes (title,descripcion,category)
values ('investigacion','estudio',1);
select first_name, last_name, rating 
from actors
where rating >= 7.5;
select title 
from notes
limit 10;
select descripcion
from notes
order by descripcion desc
limit 5;



select * from users;
delete from genres 
where id = 2;
select name 
from users
limit 3;
select email 
from users
limit 8;


select * from categorys;
delete from genres 
where id = 3;
select name
from category
limit 10;
select name
from categorys
where title like 'a%';



## Preview del desafio finalizado


