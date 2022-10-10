### Copy and Paste the following MYSQL commands to make a dummy database for this Project :


create database if not exists onlinebookstore;

use onlinebookstore;

create table if not exists books(barcode varchar(100) primary key, name varchar(100), author varchar(100), price int, quantity int);

create table if not exists users(username varchar(100) primary key,password varchar(100), firstname varchar(100),lastname varchar(100),address text, phone varchar(100),mailid varchar(100),usertype int);

insert into if not exists books values('10101','Programming in C','James k Wick',500,5);

insert into if not exists books values('10102','Learn Java','Scott Mayers',150,13);

insert into if not exists books values('10103','Database Knowledge','Charles Pettzoid',124,360);

insert into if not exists books values('10104','Let us c++','Steve Macclen',90,111);

insert into if not exists books values('10105','Success Key','Shashi Raj',5000,15);
INSERT INTO 'books'  VALUES ('100001', 'Harry Potter and the Half-Blood Prince (Harry Potter  #6)', 'J.K. Rowling', 652, 454);
INSERT INTO 'books'  VALUES ('100002', 'Harry Potter and the Order of the Phoenix (Harry Potter  #5)', 'J.K. Rowling', 870, 250);
INSERT INTO 'books'  VALUES ('100003', 'Harry Potter and the Chamber of Secrets (Harry Potter  #2)', 'J.K. Rowling', 352, 396);
INSERT INTO 'books'  VALUES ('100004', 'Harry Potter and the Prisoner of Azkaban (Harry Potter  #3)', 'J.K. Rowling', 435, 586);
INSERT INTO 'books'  VALUES ('100005', 'Harry Potter Boxed Set  Books 1-5 (Harry Potter  #1-5)', 'J.K. Rowling', 2690, 594);
INSERT INTO 'books'  VALUES ('100007', 'Harry Potter Collection (Harry Potter  #1-6)', 'J.K. Rowling', 3342, 1338);
INSERT INTO 'books'  VALUES ('100008', 'The Ultimate Hitchhikers Guide: Five Complete Novels and One Story ', 'Douglas Adams', 815, 644);
INSERT INTO 'books'  VALUES ('100009', 'The Ultimate Hitchhikers Guide ', 'Douglas Adams', 815, 376);
INSERT INTO 'books'  VALUES ('100010', 'The Hitchhikers Guide to the Galaxy', 'Douglas Adams', 215, 1485);
INSERT INTO 'books'  VALUES ('100013', 'A Short History of Nearly Everything', 'Bill Bryson', 544, 1264);
INSERT INTO 'books'  VALUES ('100014', 'Bill Bryson African Diary', 'Bill Bryson', 55, 1134);
INSERT INTO 'books'  VALUES ('100015', 'Brysons Dictionary of Troublesome Words: A Writers Guide to Getting It Right', 'Bill Bryson',256, 1043);
INSERT INTO 'books'  VALUES ('100016', 'In a Sunburned Country', 'Bill Bryson', '335', '1049');
INSERT INTO 'books'  VALUES ('100017', 'I m a Stranger Here Myself: Notes on Returning to America After Twenty Years Away', 'Bill Bryson', 304, 915);
INSERT INTO 'books'  VALUES ('100018', 'The Lost Continent: Travels in Small Town America', 'Bill Bryson', 299, 550);
INSERT INTO 'books'  VALUES ('100019', 'Neither Here nor There: Travels in Europe', 'Bill Bryson', 254, 608);
INSERT INTO 'books'  VALUES ('100020', 'Notes from a Small Island', 'Bill Bryson', 324, 317);
INSERT INTO 'books'  VALUES ('100021', 'The Mother Tongue: English and How It Got That Way', 'Bill Bryson', 270, 1468);
INSERT INTO 'books'  VALUES ('100022', 'J.R.R. Tolkien 4-Book Boxed Set: The Hobbit and The Lord of the Rings', 'J.R.R. Tolkien', 1728, 499);
INSERT INTO 'books'  VALUES ('100023', 'The Lord of the Rings (The Lord of the Rings  #1-3)', 'J.R.R. Tolkien', 1184, 529);
INSERT INTO 'books'  VALUES ('100024', 'The Fellowship of the Ring (The Lord of the Rings  #1)', 'J.R.R. Tolkien', 398, 1064);
INSERT INTO 'books'  VALUES ('100025', 'The Lord of the Rings (The Lord of the Rings  #1-3)', 'J.R.R. Tolkien/Alan  Lee', 1216, 929);
INSERT INTO 'books'  VALUES ('100026', 'The Lord of the Rings: Weapons and Warfare', 'Chris   Smith/Christopher  Lee/Richard Taylor', 218, 676);
INSERT INTO 'books'  VALUES ('100027', 'The Lord of the Rings: Complete Visual Companion', 'Jude Fisher', 224, 567);
insert into users values('User','Password','First','User','My Home','42502216225','User@gmail.com',2);

insert into users values('Admin','Admin','Mr.','Admin','Haldia WB','9584552224521','admin@gmail.com',1);

insert into users values('shashi','shashi','Shashi','Raj','Bihar','1236547089','shashi@gmail.com',2);

commit;
