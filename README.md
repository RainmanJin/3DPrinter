## Vue 重构 3D 打印云平台项目
3D打印云平台是全自动3D打印机集成系统中的重要一环，负责为用户提供在线打印等功能；前后端分离开发，前端使用Vue技术栈，后台使用Egg.js。

## 前端架构

| 项目分页   |        子路由        |                               功能点                               |
| :--------- | :------------------: | :----------------------------------------------------------------: |
| 首页       |          无          |                   介绍和用数据描述 3D 云打印平台                   |
| 在线建模   | 外链接、3D 涂鸦平台  |                       可以在线设计模型并下载                       |
| 在线打印   | 模型库页、模型详情页 | 上传文件预览、购物车管理打印队列、模型库查看模型并可以加入队列打印 |
| 关于我们   |          无          |             简单介绍 3D 打印云平台特色以及寻找商业合作             |
| 我的订单   |          无          |                    查看打印进度以及打印历史纪录                    |
| 登录、注册 |          无          |                           注册、登录认证                           |

## 模型预览图

一个展示 STL 模型的预览图，支持模型操作和模型点击事件，能调节缩放模型到合适大小并校正偏移。

![模型预览](./src/assets/images/module.gif "模型预览")

## 本地文件上传预览

![模型上传预览](./src/assets/images/preview.gif "模型上传预览")
