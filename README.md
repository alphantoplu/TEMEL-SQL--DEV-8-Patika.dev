# TEMEL-SQL--DEV-8-Patika.dev
- 1-test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
- 2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
- 3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
- 4-Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
- CREATE TABLE employee (
    id integer,
    name varchar(50),
    birthday date,
    email varchar(100)
);
- insert into employee (id, name, birthday, email) values (1, 'Chelsey Liffey', '2016-12-19', 'cliffey0@csmonitor.com');
- insert into employee (id, name, birthday, email) values (2, 'Abey Leonard', '2018-01-07', 'aleonard1@wired.com');
- insert into employee (id, name, birthday, email) values (3, 'Mabelle Gaylord', '2021-10-13', 'mgaylord2@usda.gov');
- insert into employee (id, name, birthday, email) values (4, 'Raf Fentem', '2020-03-01', 'rfentem3@nba.com');
- insert into employee (id, name, birthday, email) values (5, 'Seymour Ireson', '2022-03-03', 'sireson4@yandex.ru');
- insert into employee (id, name, birthday, email) values (6, 'Ammamaria Whylie', '2021-12-05', 'awhylie5@gizmodo.com');
- insert into employee (id, name, birthday, email) values (7, 'Bennie Burnip', '2021-07-27', 'bburnip6@cisco.com');
- insert into employee (id, name, birthday, email) values (8, 'Jocelin Berringer', '2013-03-14', 'jberringer7@pcworld.com');
- insert into employee (id, name, birthday, email) values (9, 'Dionne Kintzel', '2019-07-12', 'dkintzel8@springer.com');
- insert into employee (id, name, birthday, email) values (10, 'Marla Kilmary', '2014-07-30', 'mkilmary9@lulu.com');
- insert into employee (id, name, birthday, email) values (11, 'Glyn Milland', '2013-02-16', 'gmillanda@businessinsider.com');
- insert into employee (id, name, birthday, email) values (12, 'Tully Chrispin', '2018-01-25', 'tchrispinb@loc.gov');
- insert into employee (id, name, birthday, email) values (13, 'Barton Garmston', '2021-03-16', 'bgarmstonc@mac.com');
- insert into employee (id, name, birthday, email) values (14, 'Dinnie Dighton', '2022-01-20', 'ddightond@ezinearticles.com');
- insert into employee (id, name, birthday, email) values (15, 'Giorgio Loughran', '2013-09-23', 'gloughrane@census.gov');
- insert into employee (id, name, birthday, email) values (16, 'Alameda Obray', '2016-12-12', 'aobrayf@wisc.edu');
- insert into employee (id, name, birthday, email) values (17, 'Coralyn Beeton', '2021-09-04', 'cbeetong@ucoz.com');
- insert into employee (id, name, birthday, email) values (18, 'Joann Le Gassick', '2016-03-12', 'jleh@go.com');
- insert into employee (id, name, birthday, email) values (19, 'Hyacinthia Gilbard', '2018-01-17', 'hgilbardi@nature.com');
- insert into employee (id, name, birthday, email) values (20, 'Bryana Seer', '2017-06-18', 'bseerj@moonfruit.com');
- insert into employee (id, name, birthday, email) values (21, 'Donalt Whetson', '2017-06-10', 'dwhetsonk@unblog.fr');
- insert into employee (id, name, birthday, email) values (22, 'Jannel Inglesant', '2021-04-29', 'jinglesantl@myspace.com');
- insert into employee (id, name, birthday, email) values (23, 'Royall Hastin', '2014-02-16', 'rhastinm@indiegogo.com');
- insert into employee (id, name, birthday, email) values (24, 'Bendix Gawthrope', '2020-12-16', 'bgawthropen@uiuc.edu');
- insert into employee (id, name, birthday, email) values (25, 'Iorgo Children', '2021-06-04', 'ichildreno@hostgator.com');
- insert into employee (id, name, birthday, email) values (26, 'Aliza Kiledal', '2019-04-04', 'akiledalp@answers.com');
- insert into employee (id, name, birthday, email) values (27, 'Jereme Devereux', '2012-03-29', 'jdevereuxq@4shared.com');
- insert into employee (id, name, birthday, email) values (28, 'Aubry Foggo', '2016-07-05', 'afoggor@nasa.gov');
- insert into employee (id, name, birthday, email) values (29, 'Alejandra Simnett', '2016-10-24', 'asimnetts@disqus.com');
- insert into employee (id, name, birthday, email) values (30, 'Abagail Laflin', '2022-01-17', 'alaflint@cisco.com');
- insert into employee (id, name, birthday, email) values (31, 'Terese Parkin', '2012-05-07', 'tparkinu@aol.com');
- insert into employee (id, name, birthday, email) values (32, 'Graeme Brinklow', '2020-02-25', 'gbrinklowv@chicagotribune.com');
- insert into employee (id, name, birthday, email) values (33, 'Dennet Ricco', '2012-05-21', 'driccow@yahoo.co.jp');
- insert into employee (id, name, birthday, email) values (34, 'Hamil Penk', '2019-08-15', 'hpenkx@4shared.com');
- insert into employee (id, name, birthday, email) values (35, 'Wernher Fittall', '2016-11-22', 'wfittally@vk.com');
- insert into employee (id, name, birthday, email) values (36, 'Vi Choudhury', '2012-03-07', 'vchoudhuryz@si.edu');
- insert into employee (id, name, birthday, email) values (37, 'Kat Goburn', '2017-08-15', 'kgoburn10@themeforest.net');
- insert into employee (id, name, birthday, email) values (38, 'Ronnica MacAirt', '2022-04-10', 'rmacairt11@hubpages.com');
- insert into employee (id, name, birthday, email) values (39, 'Armin Snelgar', '2016-06-19', 'asnelgar12@tuttocitta.it');
- insert into employee (id, name, birthday, email) values (40, 'Irwinn McAllister', '2014-09-02', 'imcallister13@people.com.cn');
- insert into employee (id, name, birthday, email) values (41, 'Marget Larkin', '2021-07-21', 'mlarkin14@si.edu');
- insert into employee (id, name, birthday, email) values (42, 'Drusie Sulley', '2021-01-09', 'dsulley15@seesaa.net');
- insert into employee (id, name, birthday, email) values (43, 'Hanna Thorneloe', '2021-01-01', 'hthorneloe16@mysql.com');
- insert into employee (id, name, birthday, email) values (44, 'Sharon Joriot', '2014-06-21', 'sjoriot17@boston.com');
- insert into employee (id, name, birthday, email) values (45, 'Binni Giannazzo', '2014-03-10', 'bgiannazzo18@topsy.com');
- insert into employee (id, name, birthday, email) values (46, 'Brier Phelan', '2021-11-24', 'bphelan19@economist.com');
- insert into employee (id, name, birthday, email) values (47, 'Kariotta Million', '2018-05-02', 'kmillion1a@forbes.com');
- insert into employee (id, name, birthday, email) values (48, 'Kareem Sutlieff', '2012-02-25', 'ksutlieff1b@storify.com');
- insert into employee (id, name, birthday, email) values (49, 'Conroy Wreakes', '2012-07-14', 'cwreakes1c@bing.com');
- insert into employee (id, name, birthday, email) values (50, 'Abel Olexa', '2014-04-28', 'aolexa1d@youku.com');

- UPDATE employee
SET name = 'Alphan Toplu'
WHERE id = 10;

- UPDATE employee
SET birthday = '1997-01-21'
WHERE id = 10;

- UPDATE employee
SET id = 99
WHERE name = 'Alphan Toplu';

- UPDATE employee
SET email = 'alphantoplu@gmail.com'
WHERE birthday = '1997-01-21';

- UPDATE employee
SET name = 'Ramazan Alphan Toplu'
WHERE name = 'Alphan Toplu';

- DELETE FROM employee
WHERE id = 33;

- DELETE FROM employee
WHERE birthday = '2012-02-25';

- DELETE FROM employee
WHERE name = 'Conroy Wreakes';

- DELETE FROM employee
WHERE id IN (3, 15, 20);

- DELETE FROM employee
WHERE email = 'aolexa1d@youku.com';
