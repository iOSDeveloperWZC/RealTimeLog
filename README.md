# RealTimeLog
用于远程调试iOS APP的工具
TCP服务器搭建：
1、下载电脑端花生壳软件
2、创建映射，获取远程ip和端口
3、电脑端下载TCP服务器
4、将ip和端口填入 FCLog.share().openRealTime(true, host: "", port: )
5、开启第三部中的TCP服务，手机上传的日志即可全部被查看到

