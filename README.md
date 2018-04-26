### 说明

本项目是个人博客搭建项目之一，本来打算放在一个项目里的，但是放在一个项目里代码会比较乱，所以分开多个项目来管理。关于整个博客项目的搭建以及介绍可以参考我的这篇博文。[传送门](https://juejin.im/post/5ae170e1f265da0b7527d0dc)



本项目为后台管理项目，其他项目地址：

[博客前端项目](https://github.com/keenjaan/blog)

[博客后端接口及文档](https://github.com/keenjaan/blog-api)

这三个项目完成了整个博客的构建，剩下的就是服务端部署，由于之前没有接触过服务端部署，所以什么东西都是现学，把服务器部署整个过程记录下来了。关于服务端配置仅供参考因为我也是新手。

[node项目部署——阿里云centos部署ftp](https://www.jianshu.com/p/7258a75798c4)

[node项目部署——阿里云cento部署node和nginx](https://www.jianshu.com/p/7aad651bdbb4)

[node项目部署——阿里云centos部署git服务](https://www.jianshu.com/p/d7713fbd3e5d)

[node项目部署——阿里云centos部署mongodb](https://www.jianshu.com/p/b5fd46aaec43)

项目已在服务器上正常跑起来了。

#### 项目说明

本项目是基于vue-cli的后台管理项目。ajax请求用的axios库， ui使用的element-ui。

主要有注册、登录、新建文章、编辑文章、新建分类、编辑分类、删除文章、删除分类、换肤等功能

#### 项目运行

```bash
# 克隆项目
$ git clone git@github.com:keenjaan/blog-admin.git

#进入blog-admin目录安装依赖
$ npm install # Or yarn install

# 启动热更新 at localhost:3333
$ npm run dev
```

#### 项目截图

![shot](./screenshots/5.png)

![shot](./screenshots/1.png)

![shot](./screenshots/2.png)

![shot](./screenshots/3.png)

![shot](./screenshots/4.png)