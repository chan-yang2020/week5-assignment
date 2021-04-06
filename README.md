# week5-assignment
要求三
describe user;
insert into user(name, username, password) values ('a','ply','ply');
insert into user(name, username, password) values ('b','ply1','ply1');
insert into user(name, username, password) values ('c','ply2','ply2');
insert into user(name, username, password) values ('d','ply3','ply3');
insert into user(name, username, password) values ('e','ply4','ply4');
insert into user(name, username, password) values ('f','ply5','ply5');
insert into user(name, username, password) values ('g','ply6','ply6');
insert into user(name, username, password) values ('h','ply7','ply7');
insert into user(name, username, password) values ('i','ply8','ply8');
select * from user;
select count(id) as NumOfUser from user;
select * from user order by time desc;
select * from user where id between 2 and 4 order by time desc;
select username from user where id=1;
select username,password from user where id=1;
updata user set name='丁滿' where id=1;
delete from user;

![image](https://chan-yang2020.github.io/week5-assignment/describe_table.png)
![image](https://chan-yang2020.github.io/week5-assignment/database&table.png)
![image](https://chan-yang2020.github.io/week5-assignment/insert.png)
![image](https://chan-yang2020.github.io/week5-assignment/count&order.png)
![image](https://chan-yang2020.github.io/week5-assignment/between&order.png)
![image](https://chan-yang2020.github.io/week5-assignment/select_username&password.png)
![image](https://chan-yang2020.github.io/week5-assignment/update&delete.png)

