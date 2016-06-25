shiyishi


modified-again
test-modified

## 简介

Node实现的博客系统，相关的实现细节和Node开发教程欢迎访问完全免费的配套[Node教程](http://course.tianmaying.com/node)！

## 安装 mongoDB、redis

## 获取代码

## 解决依赖

该项目使用npm管理依赖。在项目根路径，直接运行npm：

```bash
npm install
```

## 项目配置

创建配置文件`config.js`，我们提供了示例配置`config.js.example`，可以基于该示例创建自己的配置：

```bash
cp config.js.example config.js
vim config.js
```

## 启动服务

```bash
# 运行依赖服务：数据库、Redis
grunt server
```

## 构建并运行开发板

```bash
grunt
```

## 构建并运行生产版

```bash
# 构建
grunt dist

# 运行
npm start
```

访问 http://localhost:3000 ！

