1.下载JDK

下载地址：https://www.oracle.com/java/technologies/javase-downloads.html

配置环境变量

2.下载neo4j

https://neo4j.com/download-center/ 

配置环境变量
![image](https://user-images.githubusercontent.com/52813902/124247204-38b42d00-db54-11eb-859f-878f7cb26110.png)

3.启动Neo4j程序

输入neo4j.bat console。如果看到以下界面，则表示neo4j已经开始运行。

![image](https://user-images.githubusercontent.com/52813902/124247308-57b2bf00-db54-11eb-91f1-3b8b9778925e.png)

浏览器输入http://localhost:7474/ ，看到以下界面，登录账号和密码均为neo4j，第一次需要改密码。
![image](https://user-images.githubusercontent.com/52813902/124247365-64371780-db54-11eb-95ed-8a4d0ae01b47.png)

4.把Neo4j安装/卸载为服务

bin\neo4j install-service/uninstall-service

启动/停止/重启/查询服务的状态：

bin\neo4j start/stop/restart/status



