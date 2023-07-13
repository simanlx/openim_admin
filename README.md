# Open-IM-Server

Open-IM-Admin

配置数据库

#类不能使用帕斯卡命名或者驼峰命名,若不用，则不设置相应的结构体，自然不会读取

secret: token111

api: 0.0.0.0:44444

mysql:
    dbAddress: 127.0.0.1:13306, 127.0.0.1:13306 ]
    dbUserName: root
    dbPassword: 123456
    dbChatName: eChat
    dbMsgName: eMsg
    dbMsgTableNum: 10
    dbMaxOpenConns: 20
    dbMaxIdleConns: 10
    dbMaxLifeTime: 120

前端 https://github.com/simanlx/openim-admin-template.git
