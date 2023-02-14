# SQL
SQL Portfolio
CREATE TABLE bikeshop ( ID integer primary KEY , color text,Brand text,  aisle  integer, price   integer) ;
insert into bikeshop values (1,"redbike","Giant" , 6,5);
insert into bikeshop values(2,"bluebike"," huffy" ,2,8);
insert into bikeshop values(3,"greenbike"," huffy" ,3,8);
insert into bikeshop values(4,"yellowbike"," huffy" ,5,8);
insert into bikeshop values(5,"purplebike"," huffy" ,3,8);
insert into bikeshop values(6,"orangebike"," huffy" ,14,8);
insert into bikeshop values(7,"blackbike"," huffy" ,4,8);
insert into bikeshop values(8,"whitebike"," huffy" ,7,8);
insert into bikeshop values(9,"greybike"," huffy" ,9,8);
insert into bikeshop values(12,"pinkbike"," huffy" ,10,8);
insert into bikeshop values(13,"violetbike"," huffy" ,11,8);
insert into bikeshop values(14,"scarletbike"," huffy" ,12,8);
insert into bikeshop values(15,"goldbike"," huffy" 
,13,8);

Select * from BIKESHOP order by aisle; 
select sum(price) from bikeshop;
select * from bikeshop where price <8 order by aisle;
