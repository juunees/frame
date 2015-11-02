# frame

3. 	ЧИТАТЕЛИ-КHИГИ-ЗАКАЗЫ
ТАБЛИЦА  3_1. ЧИТАТЕЛИ
•	Номер читательского билета
•	ФИО
•	Место работы
•	Телефон
•	Адрес
•	Дата окончания действия читательского билета

ТАБЛИЦА  3_2. КHИГИ
•	Номер книги
•	Автор
•	Название
•	Год издания
•	Цена
•	Общее число заказов на книгу(Связать с таблицей Заказы)
•	Издательство

ТАБЛИЦА  3_3. ЗАКАЗЫ
•	Номер книги
•	Номер читателя
•	Куда (читальный зал N, абонемент)
•	Дата заказа

При создании базы данных предусмотреть:
    Описание таблиц должно включать использование (хотя бы по одному разу): NOT NULL, DEFAULT, PRIMARY KEY и CHECK Использование доменов при определении таблиц является желательным.  
    Описание межтабличных связей (можно использовать средства каскадного удаления и редактирования, но хотя бы для одной связи эти средства должны быть запрограммированы при помощи триггеров) 
    Подготовить SQL-script для загрузки данных в таблицы (не менее 10–ти строк в каждой таблице). 
    При помощи триггеров установить связь между полем «Число заказов на данную книгу» и Таблицей «Заказы»

Вариант 3_01.
1) 	Вывести сведения о читателях, заказывавших до заданной даты книги в читальный зал:        
•	ФИО
•	место работы
•	дата заказа.
2) 	Найти и вывести список ФИО читателей, удовлетворяющих условию: 
          каждый из них заказал на абонемент все книги заданного автора.
3) 	Найти и вывести  для каждого читателя: 
•	ФИО
•	место работы
•	сколько книг всего им заказано в читальный зал