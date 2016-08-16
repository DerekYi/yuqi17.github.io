
#[JohnsonYu的博客](http://yuqi17.github.io)
##关注NodeJS
**本blog主要作用:**
-用最精炼的语言描述一种技术或思想的核心部分.
-平时学习的笔记,用于备忘.
-不断更新,以适应更先进的技术和思想.
***
![nodejs](http://p1.so.qhmsg.com/t0102b5e24bd906cbdb.png)
***
     
     var http = require("http");
     
     http.createServer(function(request, response){
         response.writeHead(200,{"Content-Type":"text/plain"});
         response.write("Hello World");
         response.end();
    }).listen(8888);`

