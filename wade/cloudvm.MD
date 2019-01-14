## Cloud 新建流程 
>点击确认后会跳转到列表页面，页面显示状态为创建中，创建时间在10分钟左右新建所需字段项目名称：demo1126（可修改）
***

 
用户信息 | 信息
---------| -------------
用户名    | wade.wang@azurespl.partner.onmschina.cn
密码     | Wdd@1234cn
订阅号    |39f20a71-2c7b-4e2e-82d0-24c440fa4a0a
地域     | Chinaeast2
***


![GitHub set up](https://raw.githubusercontent.com/wang415/markdownimages/master/wade/WX20190114-135126.png)@w=410h=200


![](https://raw.githubusercontent.com/wang415/markdownimages/master/wade/WX20190114-135207.png)@w=410h=300

主机信息 | 信息
---------| -------------
名称      | hostname10（可修改）
密码      | dNxFDpAA3E62
类型       | Standrd_A2
系统类型    | Centos
系统版本    | 7.4
磁盘类型    | Standard_LRS
磁盘大小    | 20
数量       | 1
地址       | 10.20.0.0/24

> 不能创建 10.0.XX.0/24
***
负载均衡 | 信息
---------| -------------
名称     |  lbname10（可修改）
类型     |  public
负载端口  |    80
数据库 | 信息
---------| -------------
名称      | sqlname10（可修改）
数据库类型 |GP_Gen5_2
存储大小 |102400
数量    |   1
数据库密码| dNxFDpAA3E62

>删除流程
       点击删除按钮（没有二次确认），页面右上角弹出提示，页面显示状态变更为删除中，删除时间在6分钟左右，成功后页面显示为删除成功
