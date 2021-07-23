<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [Typecho](	https://github.com/typecho/typecho/tree/v1.1-17.10.30-release)

Typecho 是一个 PHP 博客平台，简单而强大。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Typecho&branch=master)
### 配置
- `MYSQL_HOST`：数据库地址
- `MYSQL_PORT`：数据库端口
- `MYSQL_USERNAME`: 客户端创建的数据库账号
- `MYSQL_PASSWORD`: 客户端创建的数据库账号密码
- `MYSQL_DATABASE`:数据库名
- `MYSQL_PREFIX`:数据库表前缀
- `SITE_URL`:站点url
- `TYPECHO_USERNAME`:管理员账号
- `TYPECHO_PASSWORD`:管理员密码
- `TYPECHO_MAIL`:管理员邮箱地址

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
