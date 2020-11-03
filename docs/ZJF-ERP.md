# ZJF-ERP

## 1.系统架构

> 采用SpringCloud脚手架[BladeX](http://bladex.staging.zhaojiafang.com/)

![](.\zjf\架构流程分析.png)

## 2.展示层

### 2.1 前台前端工程

> erp-web

### 2.2 后台前端工程

> erp-sys-web

## 3.服务层

### 3.1 网关

> [blade-gateway](http://gitlab.zhaojiafang.com/java/zjf-erp/tree/master/blade-gateway)

### 3.2 审单业务(订单管理系统)

> zjf-oms

### 3.3 交接相关业务(仓库管理系统)

> [zjf-wms](http://gitlab.zhaojiafang.com/java/zjf-wms.git)

### 3.4 支付系统

> [zjf-pay](http://gitlab.zhaojiafang.com/java/zjf-pay.git)

### 3.5 自发打印业务

> [zjf-erp-spd](http://gitlab.zhaojiafang.com/java/zjf-erp-spd.git)

### 3.6 ERP管理后台服务端项目

> [zjf-erp-system](http://gitlab.zhaojiafang.com/java/zjf-erp-system.git)

### 3.7 ZJF-ERP

> [zjf-erp](http://gitlab.zhaojiafang.com/java/zjf-erp.git)

#### 01 服务说明

| Service               | Remark     |
| --------------------- | ---------- |
| blade-gateway         | 网关       |
| blade-auth            | 授权       |
| blade-resource-client | 资源客户端 |

#### 02 启动顺序

## 4.第三方网关

> three-party-gateway

## 5.基础服务层

### 5.1 支付中心

> zjf-pay

### 5.2 用户中心

> blade-user

### 5.3 商品中心

> blade-goods

### 5.4 订单中心

> blade-order

### 5.5 物流中心

> blade-logistics

### 5.6 资源中心

> blade-resource

### 5.7 后台支撑

> blade-system

