1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```sql
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```sql
insert into employee (id, name, birthday, email) values (1, 'Johanna', '1983-09-01', 'jsayles0@flickr.com');
insert into employee (id, name, birthday, email) values (2, 'Hesther', '1958-03-01', 'hohrtmann1@wikia.com');
insert into employee (id, name, birthday, email) values (3, 'Debera', '1957-12-24', 'dzuenelli2@joomla.org');
insert into employee (id, name, birthday, email) values (4, 'Tito', '1959-12-28', 'tespada3@jigsy.com');
insert into employee (id, name, birthday, email) values (5, 'Chiquia', '1977-05-13', 'cexrol4@deviantart.com');
insert into employee (id, name, birthday, email) values (6, 'Rosette', '2021-07-09', 'reingerfield5@disqus.com');
insert into employee (id, name, birthday, email) values (7, 'Almeda', '1965-06-02', 'asherborn6@wsj.com');
insert into employee (id, name, birthday, email) values (8, 'Magdalene', '1994-10-15', 'mkilfether7@typepad.com');
insert into employee (id, name, birthday, email) values (9, 'Margie', '2007-09-12', 'mhoulison8@yellowbook.com');
insert into employee (id, name, birthday, email) values (10, 'Fairlie', '1978-07-21', 'fwooldridge9@last.fm');
insert into employee (id, name, birthday, email) values (11, 'Paola', '1953-05-28', 'pjumonta@liveinternet.ru');
insert into employee (id, name, birthday, email) values (12, 'Isadore', '1994-08-28', 'iallonbyb@dmoz.org');
insert into employee (id, name, birthday, email) values (13, 'Gardner', '1988-07-30', 'gfussiec@tinyurl.com');
insert into employee (id, name, birthday, email) values (14, 'Ulick', '1974-11-06', 'ubluschked@unesco.org');
insert into employee (id, name, birthday, email) values (15, 'Griffie', '1993-10-23', 'ggiacubboe@wikimedia.org');
insert into employee (id, name, birthday, email) values (16, 'Shannen', '1997-09-05', 'shuncootf@hatena.ne.jp');
insert into employee (id, name, birthday, email) values (17, 'Kimberli', '1991-11-15', 'kswinfong@ycombinator.com');
insert into employee (id, name, birthday, email) values (18, 'Giorgi', '1972-06-11', 'glundieh@nifty.com');
insert into employee (id, name, birthday, email) values (19, 'Nowell', '1994-09-24', 'nsandwicki@wisc.edu');
insert into employee (id, name, birthday, email) values (20, 'Lek', '1998-03-04', 'lturleyj@statcounter.com');
insert into employee (id, name, birthday, email) values (21, 'Jaymie', '1998-07-14', 'jmcmenemyk@ebay.co.uk');
insert into employee (id, name, birthday, email) values (22, 'Thurstan', '2004-03-31', 'taxelbeel@pagesperso-orange.fr');
insert into employee (id, name, birthday, email) values (23, 'Waiter', '2003-10-29', 'wwestropem@blogs.com');
insert into employee (id, name, birthday, email) values (24, 'Flemming', '1966-03-25', 'fscandriten@admin.ch');
insert into employee (id, name, birthday, email) values (25, 'Alonso', '1980-11-30', 'agockeleno@clickbank.net');
insert into employee (id, name, birthday, email) values (26, 'Sibylle', '2017-04-11', 'ssibbonsp@github.com');
insert into employee (id, name, birthday, email) values (27, 'Orelia', '1993-10-21', 'oseniourq@washingtonpost.com');
insert into employee (id, name, birthday, email) values (28, 'Toma', '2001-03-10', 'teaggerr@live.com');
insert into employee (id, name, birthday, email) values (29, 'Oby', '2020-08-03', 'oprettymans@qq.com');
insert into employee (id, name, birthday, email) values (30, 'Meara', '2013-04-16', 'mflemmingt@house.gov');
insert into employee (id, name, birthday, email) values (31, 'Eolanda', '2015-06-04', 'esimonelliu@wufoo.com');
insert into employee (id, name, birthday, email) values (32, 'Leanora', '2019-04-29', 'lrottev@constantcontact.com');
insert into employee (id, name, birthday, email) values (33, 'Ingra', '2020-12-03', 'iwellfarew@digg.com');
insert into employee (id, name, birthday, email) values (34, 'Addison', '1973-04-10', 'asinniex@google.de');
insert into employee (id, name, birthday, email) values (35, 'Cazzie', '2016-09-26', 'cbranchy@zdnet.com');
insert into employee (id, name, birthday, email) values (36, 'Gretta', '1997-05-22', 'ggiriardelliz@senate.gov');
insert into employee (id, name, birthday, email) values (37, 'Curtis', '2019-02-02', 'clean10@tumblr.com');
insert into employee (id, name, birthday, email) values (38, 'Vlad', '1963-02-14', 'vussher11@webnode.com');
insert into employee (id, name, birthday, email) values (39, 'Meryl', '1999-11-24', 'mhacquoil12@ca.gov');
insert into employee (id, name, birthday, email) values (40, 'Bekki', '2020-08-26', 'bkilby13@simplemachines.org');
insert into employee (id, name, birthday, email) values (41, 'Marina', '1986-03-21', 'mormonde14@ted.com');
insert into employee (id, name, birthday, email) values (42, 'Ansell', '1984-11-20', 'asidworth15@java.com');
insert into employee (id, name, birthday, email) values (43, 'Bethany', '1976-06-14', 'bdrissell16@ebay.com');
insert into employee (id, name, birthday, email) values (44, 'Luca', '1994-11-03', 'ljeavons17@wordpress.org');
insert into employee (id, name, birthday, email) values (45, 'Edwina', '1997-11-05', 'edenford18@cargocollective.com');
insert into employee (id, name, birthday, email) values (46, 'Sela', '1977-07-23', 'sjaskiewicz19@t.co');
insert into employee (id, name, birthday, email) values (47, 'Flem', '2017-02-21', 'ftruckett1a@ftc.gov');
insert into employee (id, name, birthday, email) values (48, 'Toinette', '1951-12-18', 'tgreenaway1b@cdbaby.com');
insert into employee (id, name, birthday, email) values (49, 'Bail', '1989-06-23', 'boverstall1c@google.nl');
insert into employee (id, name, birthday, email) values (50, 'Ester', '1971-03-30', 'ewastell1d@booking.com');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
UPDATE employee
SET name = 'Ali'
WHERE id = 1;

UPDATE employee
SET name = 'Organization'
WHERE email LIKE '%.org';

UPDATE employee
SET email = 'rosette@rosette.com'
WHERE name = 'Rosette';

UPDATE employee
SET id = 51
WHERE birthday = '1994-10-15';

UPDATE employee
SET birthday = '1999-03-04'
WHERE id < 10;
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee
WHERE id = 1;

DELETE FROM employee
WHERE name LIKE 'O%';

DELETE FROM employee
WHERE email ILIKE '%.com';

DELETE FROM employee
WHERE birthday = '1980-11-30';

DELETE FROM employee
WHERE name = 'Addison';
```
