写点可以复制粘贴的东西
{"msgid":1,"id":13,"password":"123456"}
{"msgid":1,"id":15,"password":"666666"}
{"msgid":3,"name":"li si", "password":"666666"}
{"msgid":5,"id":13,"from":"zhang san","to":15,"msg":"hello!"}

联合查询sql语句
select a.id,a.name,a.state from user a inner join friend b on b.friendid = a.id where b.userid=%d