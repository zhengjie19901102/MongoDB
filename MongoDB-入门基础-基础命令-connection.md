## MongoDB-入门基础:基础命令:connection

环境配置与MySQL和Java配置方式相似。
找到安装目录下的bin目录下，然后配置到环境变量PATH中。

一般连接命令:
`mongod --dbpath 数据库库文件所在位置[/data] --port 端口号`

默认端口号:`27017`		不配置端口号则使用默认端口。

windows、Linux、Mac下配置服务方法查看MongoDB官网

mac下后台启动MongoDB服务可以通过如下命令:

`mongod --config 配置文件路径`  此时使用了配置文件中的端口号及数据库位置和日志所在位置等，并且默认是后台启动，不占用终端窗口。
