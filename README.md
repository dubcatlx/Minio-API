### 一、minio-demo
minio的Java API开发教程。


官方教程文档：https://docs.min.io/?ref=con


### 二、minio 安装
1.进入官网进行下载，只需下载服务端即可。
```
https://min.io/download
```


2.将下载`` minio.exe ``文件指定位置，我这里放在`` D:\Develop\Minio ``目录下。


3.在该目录下新建`` start.bat ``文件，文件内容如下：
```
minio.exe server D:\Develop\Minio\date
```
其中`` D:\Develop\Minio\date ``表示minio后续数据存放位置。


4.双击启动`` bat ``文件即可，控制台会自动显示访问地址以及默认的登录账号。
