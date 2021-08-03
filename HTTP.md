# HTTP

超文本协议
HTTP请求过程

url和uri
URL主要有6个部分
protocol+domain name+port+path to the file+parameters+anchor
http://www.example.com:80/path/to/file.html/?key1=value1#anchor1


动态页面和静态页面的区别

中端访问www.baidu.com的过程

DNS首先查询浏览器缓存，没有则查询操作系统缓存，还是没有则查询host文件，再没有，则查询本地DNS服务器（8.8.8.8或者114.114.114.114），8.8.8.8是google域名服务器，114.114.114.114是国内网络商提供的免费DNS服务器。
本地DNS域名服务器没有找到，则。。。

## 缓存管理
强制缓存、对比缓存
## 连接管理
可靠连接、非可靠连接
短链接、长连接
HTTP和TCP keepalive
对头阻塞问题


## 优质博客
https://zhuanlan.zhihu.com/p/376068455
https://halfrost.com/http2-http-frames-definitions/
