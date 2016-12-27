# Linux命令

### 1、关机重启

```shell
sysnc					 #将数据有内存同步到硬盘
shutdown 				 #关机指令，你可以man shutdown帮助文档
shutdown -h 10 			 #10分钟之后关机
shutdown -h now 		 #立马关机
shutdown -h 20:25  		 #系统会在今天20:25关机
shutdown -h +10 		 #10分钟后关机
shutdown -r now 		 #系统立马重启
shutdown -r +10			 #系统十分钟后重启
reboot					 #就是重启，等同于shutdown -r now
halt					 #关闭系统 等同于shutdown -h now 和 poweroff
init 0					 #关机
init 6					 #重启
```

### 2、