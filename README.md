SQL statements in the repo are data dump from MySql Workbench tool. This is a sample application for understanding DB operations.

Below are the sequence to insert data as there is a foreign key constraints.

insert into movies values(1,'title1','director1','2018');
insert into movierentals values(1,1/2/2018,1/4/2018);
insert into categories values (1,'category example 1', 'first remarks');
insert into members values(1,'name1','M',1/1/2018,'addr1','paddr1',12345,'some@example.com');
insert into payments values(1,1/5/2018,'desc1',123.45,99);
