# SQL
SQL Portfolio
Creating a biike shop database

CREATE TABLE bikeshop ( ID integer primary KEY , color text,Brand text,  aisle  integer, price   integer) ;

insert into bikeshop values (1,"redbike","Giant" , 6,5.00);
insert into bikeshop values(2,"bluebike"," huffy" ,2,8.00);
insert into bikeshop values(3,"greenbike"," huffy" ,3,7.00);
insert into bikeshop values(4,"yellowbike"," huffy" ,5,6.00);
insert into bikeshop values(5,"purplebike"," roadrage" ,3,8.00);
insert into bikeshop values(6,"orangebike"," huffy" ,14,8.00);
insert into bikeshop values(7,"blackbike"," GiaNT" ,4,8.00);
insert into bikeshop values(8,"whitebike"," huffy" ,7,8.00);
insert into bikeshop values(9,"greybike"," roadrage" ,9,8.00);
insert into bikeshop values(12,"pinkbike"," huffy" ,10,8.00);
insert into bikeshop values(13,"violetbike"," huffy" ,11,8.00);
insert into bikeshop values(14,"scarletbike"," huffy" ,12,8.00);
insert into bikeshop values(15,"goldbike"," huffy" 
,13,8);

--display the database ordered by asile 
Select * from BIKESHOP order by aisle; 

--display the database total price of the bikeshop
select sum(price) from bikeshop;

--display every price in the bike shop greater than 8.00 and order by asile 
select * from bikeshop where price <8 order by aisle;
