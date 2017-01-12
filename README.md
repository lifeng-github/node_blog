#### 安装Express

Express是Node.js上最流行的web开发框架，正如他的名字一样，通过使用他可以快速的开发一个web引用(window下面开发)

> \>npm install -g express-generator

#### 新建一个工程
我们使用脚手架来新建一个工程项目
> \>express -e blog

> \>cd blog && npm install

第一个指令是脚手架新建blog，blog的目录下面有一些配置。第二个指令是进入blog目录，去执行npm install，根据package.json来安装对应的依赖包

> \>SET DEBUG=blog:* & npm start

这样就启动了一个服务，3000端口号的web服务
