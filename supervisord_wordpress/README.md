### 使用 Docker 一键搭建一个 Wordpress 博客

#### 使用说明

+ 拉取项目到相应目录
+ 进入目录，执行 `docker build -t wordpress .`
+ 启动 Docker 容器 `docker run -d -p 80:80 wordpress`
+ 访问地址 http://ip, 初始登录需要重置密码，更新网站信息

