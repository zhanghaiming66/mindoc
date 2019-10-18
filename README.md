# Mindoc 简介

MinDoc 是一款针对IT团队开发的简单好用的文档管理系统。

可以用来储存日常接口文档，数据库字典，手册说明等文档。内置项目管理，用户管理，权限管理等功能，能够满足大部分中小团队的文档管理需求。

演示站点： http://doc.iminho.me

# 使用Docker部署
如果是Docker用户，可参考项目内置的Dockerfile文件编译镜像。
启动命令：
```shell
docker run -p 8181:8181  -d daocloud.io/lifei6671/mindoc:latest
```
默认程序会自动初始化一个超级管理员用户：admin 密码：123456 。请登录后重新设置密码。
