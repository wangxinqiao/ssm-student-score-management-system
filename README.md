# SSM学生成绩信息管理系统

## 项目介绍
````
本项目分为管理员、教师、学生三种角色，
管理员角色包含以下功能：
公告管理,写公告,学生增删改查,教师增删改查,查看成绩报表,管理员首页,课程表增删改查等功能。

教师角色包含以下功能：
修改密码,按照条件查询,查看学生信息,管理课程,登陆页面等功能。

学生角色包含以下功能：
查看成绩信息,查看课程信息,选课操作等功能。

由于本程序规模不大，可供课程设计，毕业设计学习演示之用
````
演示地址：[ **点此查看** ](http://www.csbishe.cn:15000/ssm_stumanager/)
管理员账号/密码：admin/admin
学生角色账号/密码： 20160310529/123456
教师角色账号/密码：1560310/123456

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=248)

## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.数据库：MySql 5.7版本；

6.是否Maven项目：否；
````

## 技术栈
````
1. 后端：Spring+SpringMVC+Mybatis
2. 前端：HTML+LayUI
````

## 使用说明
````
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；
3. 将项目中application.yml配置文件中的数据库配置改为自己的配置;
4. 运行项目，输入localhost:8080/ 登录
````

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235436_a04d3b40_9600135.jpeg "登陆页面.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235450_6bb16104_9600135.jpeg "按照条件查询.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235459_9e89b394_9600135.jpeg "查看成绩报表.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235508_c1c964ae_9600135.jpeg "查看成绩信息.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235518_3bca2a04_9600135.jpeg "查看课程信息.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235531_72e4f5bb_9600135.jpeg "查看学生信息.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235541_5cd75ed3_9600135.jpeg "公告管理.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235552_676786be_9600135.jpeg "管理课程.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235604_619f25f0_9600135.jpeg "管理员首页.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235613_878ffefa_9600135.jpeg "教师增删改查.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235623_e48da70a_9600135.jpeg "课程表增删改查.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235633_79fb2d2e_9600135.jpeg "写公告.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235646_c1cba60a_9600135.jpeg "修改密码.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235654_d9fe07b4_9600135.jpeg "选课操作.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0818/235702_0d8efe1a_9600135.jpeg "学生增删改查.jpeg")
