# NSUnetwork
成都东软学院校园网自动连接/防止断链
# 如何获取“一次性密钥” ？
![PixPin_2024-10-22_17-29-30](https://github.com/user-attachments/assets/f5e1629a-0cda-4909-90c0-92561b342692)
# 如何编辑配置文件 ？
![PixPin_2024-10-22_17-32-07](https://github.com/user-attachments/assets/0ba88549-ad55-4d7f-9628-976ee488cd4f)
## data文件的参数：
```py
    "username" : '学号',             #填写自己登录校园网的学号
    "password" : '一次性密钥',       #网页登录后cookie中获取
    "testtime" : 5,                 #检测网络连接状况时差（单位s）
    "timeout" : 5,                  #超时连接失败失败（单位s）
    "outInFirstRequest" : False,    #第一次请求就连接成功是否退出程序
    "autoOutOtherIp" : True,        #自动踢出其他正在连接的IP
    "networkName" : "学生-移动-100M" #自动连接的网络名称
```
## 效果图
![PixPin_2024-10-22_17-23-45](https://github.com/user-attachments/assets/38b1c0a5-4a4c-4a04-9b59-4d61a7f07caf)

made by 24级新生
