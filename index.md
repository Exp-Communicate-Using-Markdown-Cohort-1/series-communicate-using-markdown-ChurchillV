# My First `<h1>` header in Markdown
### This is an `<h3>` header
##### How about a little `<h5>` ? 

#### Image Exercice
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


### Code Snippet exercise
Creating a server in NodeJS and rendering on port 9000
```
var http = require('http');

http.createServer( function(request, response) {
  response.writeHead(200, {"Content-type" : "text/plain"});
  response.write("Github Education rocks!!");
  response.end();
}).listen(9000, () => console.log("Server is up and running"));
```

### List of things I'm going to do once I complete this github education course:
- [ ] Make amazing `ReadMe` pages for my future projects
- [ ] Build a real time chat application with Node JS and SocketIO
- [x] Eat, Sleep, Code
