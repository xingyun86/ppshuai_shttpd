# ppshuai_shttpd
一个轻量级的Http服务器

SHTTPD - Simple HTTPD
Shttpd是另一个轻量级的web server，具有比thttpd更丰富的功能特性，支持CGI, SSL, cookie, MD5认证, 还能嵌入(embedded)到现有的软件里。最有意思的是不需要配置文件！由于shttpd可以嵌入其他软件，因此可以非常容易的开发嵌入式系统的web server，官方网站上称shttpd如果使用uclibc/dielibc(libc的简化子集)则开销将非常非常低。

特点：
    小巧、快速、不膨胀、无需安装、简单的40KB的exe文件，随意运行
    支持GET, POST, HEAD, PUT, DELETE 等方法
    支持CGI, SSL, SSI, MD5验证, resumed download, aliases, inetd模式运行
    标准日志格式
    非常简单整洁的嵌入式API
    dietlibc friendly. NOT that friendly to the uClibc (*)
    容易定制运行在任意平台：Windows, QNX, RTEMS, UNIX (*BSD, Solaris, Linux)
由于shttpd可以轻松嵌入其他程序里，因此shttpd是较为理想的web server开发原形，开发人员可以基于shttpd开发出自己的webserver！
下载地址：http://jaist.dl.sourceforge.net/sourceforge/shttpd/