# 校园网连接不上解决办法
使用必读
- 使用环境：在江安有校园网信号但是连接不上校园网的时候
- 说明 [1 - 254]表示从1到254之间任取一个整数
- 使用方法，打开scunet的wifi高级设置，将ip设置从DHCP改为静态，然后按下表填入对应的设置，点击保存

|地点|修改ip|路由器ip(默认网关)|前缀长度|子网掩码|
|---|----|------------------|-------|------|
|综c|10.132.[36-39].[1-254]|10.132.39.254|22|255.255.252.0|
|文科楼3区|10.132.[20-23].[1-254]|10.132.23.254|22|	255.255.252.0|
|一教|10.132.[0-15].[1-254]|10.132.15.254|20|255.255.240.0|
|图书馆|10.132.[28-31].[1-254]|10.132.31.254|22|255.255.252.0|

- dns设置
    - 首选 202.115.32.39
    - 202.115.32.36
- 注意事项：去了其他可以连上校园网的地方记得把ip设置切回DHCP
