# week5-assignment
要求三
![GITHUB]("database&table.png")
describe user;
![GITHUB]("describe_table.png")
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
![GITHUB]("insert.png")
select count(id) as NumOfUser from user;
select * from user order by time desc;
![GITHUB]("count&order.png")
select * from user where id between 2 and 4 order by time desc;
![GITHUB]("between&order.png")
select username from user where id=1;
select username,password from user where id=1;
![GITHUB]("select_username&password.png")
updata user set name='丁滿' where id=1;
delete from user;
![GITHUB]("update&delete.png")

