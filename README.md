## yuqi.github.io
#[JohnsonYu的博客](http://yuqi17.github.io)
##关注NodeJS

![nodejs](http://p1.so.qhmsg.com/t0102b5e24bd906cbdb.png)

`
    var http = require("http");
    http.createServer(function(request, response){
    response.writeHead(200,{"Content-Type":"text/plain"});
    response.write("Hello World");
    response.end();
    }).listen(8888);
`

