# 过程
1. 通过域名或网址来访问网站
2. 你的电脑连接到一个称为域名系统（DNS）的服务器网络。DNS有点类似于电话薄，它会将域名对应的IP地址告诉你的计算机。
3. DNS服务器返回的IP地址能让浏览器连接到web服务器。而Web服务器托管着要访问的网站。web服务器是一台始终联网的计算机。有ip地址。专门用于向用户发送网页。
4. web服务器将请求的页面发送到web浏览器中。
5. 浏览器接收后读取绘制网页。

## URL
统一资源定位符，用于定位网上的资源。
## 域名解析
域名是ip地址的昵称，方便人们记忆，一个域名对应一个ip，但是一个ip对应多个域名，例如网址http://jirengu.com/blog ，中的jirengu.com则是域名，也就是两条斜线中除了端口就是域名。
## 解析流程
>**浏览器缓存**：如果之前访问过该主机，浏览器会缓存DNS一段时间，这样就可以直接使用浏览器缓存的DNS，至于一段时间是多久没有要求。
>**系统缓存**：如果浏览器缓存里没有记录。浏览器会做系统的调用，获取系统中的缓存记录。
>**路由器缓存**：如果系统缓存同样没有命中，那就需要查路由器缓存了。
>ISP(互联网服务提供商)的DNS缓存：路由器缓存未命中会查询ISP，一般域名在这里就都可以找到了。
>递归搜索：从根域名开始递归查询，这个肯定就能查到了。

![解析流程图](http://upload-images.jianshu.io/upload_images/4588809-ed3100f75f314a6b.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



附：借鉴《HTML&CSS设计与构建网站》和饥人谷的教程
