数字化平台-模板项目-Z000-WEB
===============
当前最新版本： 2.1.0（发布时间：2026-5-10）

[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)]()
[![](https://img.shields.io/badge/Author-河北尚智得-orange.svg)](https://www.szdsoft.cn/about)
[![](https://img.shields.io/badge/version-2.1.0-brightgreen.svg)](https://github.com/szdsdp/z000-web)

## 简介

数字化平台-模板项目是基于尚智得数字化平台开发的企业应用的基础模板项目。该模板项目的开发目的是让企业快速构建自己的业务应用系统，将模板项目源码下载到本地，按照项目里的功能模板开发自己的实际业务功能即可。
模板项目包括功能：数据报表、主数据维护、流程单据，以及SAP常用的主数据模块、采购模块、生产模块、销售模块、费用模块等。
> 业务应用基于 Spring Boot + Spring Cloud + Nacos + Redis + RocketMQ 等微服务架构开发，前端基于 Vue + Element-Plus UI
> 等实现，支持多种数据库Mysql、Oracle、达梦等，也可自选前后端技术框架，数字化平台提供的组件库与业务应用可快速无缝融合，业务应用开发完全基于原生，利于员工成长，企业自主可控。

## 技术支持

使用中遇到问题或者BUG可以在Github上提 [Issues](https://github.com/szdsdp/z000-web/issues)

官方支持： https://www.szdsoft.cn/platform/onlineApi/overview

## 源码下载

- 后台源码 ：https://github.com/szdsdp/z000
- 前端源码 ：https://github.com/szdsdp/z000-web
- 手机端源码 ：https://github.com/szdsdp/z000-app

## 开发环境搭建

- [开发说明](https://szdsoft.cn/platform/online-api/overview)
- [快速启动](https://szdsoft.cn/platform/online-api/quickStart/localDev)

## 技术文档

- 官方文档：[https://szdsoft.cn/platform/online-api/overview](https://szdsoft.cn/platform/online-api/overview)
- 官方网站：[https://www.szdsoft.cn](https://www.szdsoft.cn)
- 在线演示：[https://sdp.szdsoft.cn:81/login](https://sdp.szdsoft.cn:81/login) 

> 演示系统的登录账号密码：admin/2025

## 安装与使用

- 下载代码

```bash
git clone https://github.com/szdsdp/z000-web.git
```

- 安装依赖

```bash
npm install
```

- 启动项目

```bash
npm run serve
```

- build

```bash
npm run build
```

## 入门必备

本项目需要一定前端基础知识，请确保掌握 Vue 的基础知识，以便能处理一些常见的问题。
建议在开发前先学一下以下内容，提前了解和学习这些知识，会对项目理解非常有帮助:

* [SDP数字化平台文档](https://szdsoft.cn/platform/online-api/overview)
* [Vue 文档](https://cn.vuejs.org/)
* [Element-Plus-UI](https://element-plus.org/zh-CN/)