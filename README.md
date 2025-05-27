# RealTimeLog
用于远程调试iOS APP的工具
TCP服务器搭建：
1、下载电脑端花生壳软件
2、创建映射，获取远程ip和端口
3、电脑端下载TCP服务器
4、将ip和端口填入 FCLog.share().openRealTime(true, host: "", port: )
5、开启第三部中的TCP服务，手机上传的日志即可全部被查看到

具体操作：![截屏2025-05-27 14 15 32](https://github.com/user-attachments/assets/aaa8b034-d62b-48fd-ab75-97584cbe946b)
![截屏2025-05-27 14 15 44](https://github.com/user-attachments/assets/08f25cd5-7790-43b4-9427-8685a24d4cb8)
![截屏2025-05-27 14 16 02](https://github.com/user-attachments/assets/50941dfa-a370-458e-b57f-e79fad6edba2)


SDK用法：
1、在确定有网络的情况下初始化SDK：
FCLog.share().openRealTime(true, host: "", port: )
2、写日志
FCLog.write()
