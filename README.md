# Huawei Mate 40 Pro Install GSM

1、修改系统时间到2020/7月之前

2、下载Google套件, [https://github.com/mgeeker/huawei-mate40pro-gsm](https://github.com/mgeeker/huawei-mate40pro-gsm) 

3、解压 Backup.zip

4、系统恢复 （密码：a12345678）

5、恢复之后桌面上会多一个 “谷歌服务助手”

6、启动 谷歌服务助手，激活，开始下载（如果有下载异常，重新下载）

7、把系统时间改回来（自动设置打开）,再把网络打开

8、安装MicroG，打开，选择Add google account， 登录google account

9、选择设置帐户，查看添加帐号是否已经添加OK

10、删除MicroG，安装1-7。重要安装（Google Play，Google框架，Google 服务）

11、打开Google Play，会报错，多重试几次，再杀掉进程，重试

12、Google Play正常打开，但是会有很多Google 警告的推送

13、下载一个device id app，打开，复制GSF编号，打开 URL  [https://www.google.com/android/uncertified/](https://www.google.com/android/uncertified/)  添加刚刚复制的GSF

14、打开飞行模式，关机，开机

15、打开设置应用应用管理，搜索Google，显示系统进程，分别对Google服务框架、Google Play服务（第一次不删除数据），Google Play商店作以下操作：清除缓存、删除数据，强行停止。 重启手机

16、打开设置应用应用管理，搜索Google，选择Google Play服务，存储，清空缓存，管理空间，清除所有数据，返回，强行停止，重启手机

17、如果警告关不掉，很重复15-16，多试几次，总会成功的，一般情况下一次就会成功🙂