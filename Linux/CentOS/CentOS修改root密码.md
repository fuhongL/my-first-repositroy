1.使用root用户登陆到ssh或者服务器

2.进入命令行界面

3.root用户下使用

    passwd root # 根据提示输入新密码，然后重复密码，最后提示已经成功修改密码
4.重新ssh链接测试

    ssh  [用户名]@[远程服务器的IP] -p [远程服务器的ssh端口，默认为22]
