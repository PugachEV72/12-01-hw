# Домашнее задание к занятию 12.1. «Базы данных» - Пугач Евгений.


---

### Задание 1

## `Ответ:`

1. Сотрудник (  
   идентификатор, первичный ключ, serial,  
   фамилия varchar(50),  
   имя varchar(50),  
   отчество varchar(50),  
   дата_найма date,  
   идентификатор_структурного_подразделения, внешний ключ, integer,  
   идентификатор_должности, внешний ключ, integer,  
   идентификатор_проекта, внешний ключ, integer,  
   идентификатор_филиала, внешний ключ, integer).

2. Должность (  
   идентификатор, первичный ключ, serial,  
   должность varchar(100),  
   размер оклада numeric).

3. Проект (  
   идентификатор, первичный ключ, serial,  
   заказчик varchar(100),  
   комментарий text,  
   идентификатор_адреса, внешний ключ, integer) - может быть NULL.

4. Структурное подразделение (  
   идентификатор, первичный ключ, serial,  
   наименование varchar(100),  
   идентификатор_типа_подразделения, внешний ключ, integer).

5. Тип подразделения (  
   идентификатор, первичный ключ, serial,  
   наименование varchar(100)).

6. Адрес (  
   идентификатор, первичный ключ, serial,  
   населенный_пункт varchar(50),  
   улица varchar(50),  
   дом varchar(50),  
   квартира smallint) - может быть NULL.

7. Филиал (  
   идентификатор, первичный ключ, serial,  
   наименование varchar(50),  
   идентификатор_адреса, внешний ключ, integer).

---

