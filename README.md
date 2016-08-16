
#[JohnsonYu的博客](http://yuqi17.github.io)

##本blog主要作用:
1.用最精炼的语言描述一种技术或思想的核心部分.
2.平时学习的笔记,用于备忘.
3.不断更新,以适应更先进的技术和思想.
***
##关注NodeJS
![nodejs](http://p1.so.qhmsg.com/t0102b5e24bd906cbdb.png)
***
     
     var http = require("http");
     http.createServer(function(request, response){
         response.writeHead(200,{"Content-Type":"text/plain"});
         response.write("Hello World");
         response.end();
    }).listen(8888);

