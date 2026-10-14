![](https://img.shields.io/badge/License-MIT-blue.svg)

![](https://img.shields.io/badge/Version-1.0.0-brightgreen.svg)

![](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

# 校园订餐外卖平台 (Campus Food Delivery Platform)

一款专为高校师生打造的轻量级校园订餐与外卖服务平台。基于微信小程序端与后台管理系统，提供从点餐、支付、社区交流到订单履约的全链路闭环体验，助力校园餐饮数字化升级。

本项目致力于解决校园内“吃饭难、选择少、沟通不便”的痛点，构建了一个集**在线点餐、社区互动、即时通讯**于一体的综合性服务平台。系统分为**用户端（微信小程序）****与****管理端（Web后台）**，支持商家入驻、学生点餐、骑手配送及管理员统筹，打造专属校园的美食生活圈。


#### 安装环境
**️ 注意**：请确保您的开发环境已安装以下依赖。

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 一定要把账户和密码记住

redis

Idea 编译器

WebStorm OR VScode 编译器

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok

---
## 核心特性

-  **全链路交易闭环**：从热销推荐、购物车结算到订单收货，提供丝滑的点餐体验。
-  **内置即时通讯**：支持用户与商家/客服在线实时沟通，售后无忧。
- ️ **校园专属社区**：集成美食论坛与公告系统，打造集点餐与社交于一体的校园生活圈。
-  **可视化数据看板**：后台订单仪表板实时追踪核心指标，让运营决策有据可依。
- ️ **全维度后台管理**：一站式管理餐品、商铺、帖子、评价与用户，轻松掌控平台全局。
-  **灵活地址管理**：支持多收货地址配置，完美适配校园内宿舍、教学楼等复杂配送场景。
-  **微信生态无缝接入**：小程序一键授权登录，极简操作，降低用户流失率。
---

## ️ 功能模块概览

### 用户端 (微信小程序)

| 模块 | 功能描述 |
| ------ |------ |
| **快捷登录** | 支持微信小程序一键授权注册/登录，无缝获取用户信息 |
| **智能点餐** | 支持商家/餐品搜索、分类浏览、热销推荐、公告查看 |
| **交易闭环** | 购物车管理、在线结算、我的订单、订单详情、确认收货 |
| **地址管理** | 支持多收货地址增删改查，默认地址设置 |
| **社区互动** | 校园美食论坛、发帖/回帖、公告信息查看 |
| **在线客服** | 内置即时通讯模块，支持用户与商家/客服在线实时沟通 |

### ️ 管理端 (Web 后台)

| 模块 | 功能描述 |
| ------ |------ |
| **数据看板** | 首页订单仪表板，实时展示今日订单、营业额、用户增长等核心指标 |
| **餐品管理** | 餐品上下架、信息编辑、餐品类型/标签管理 |
| **商铺管理** | 商家入驻审核、商铺信息维护、营业状态控制 |
| **订单管理** | 全生命周期订单追踪（待支付/制作中/配送中/已完成/退款） |
| **用户管理** | 用户列表、权限控制、账号状态管理 |
| **内容运营** | 公告发布、帖子审核/删除、用户评价管理 |
| **消息中心** | 系统消息推送、客服消息记录查看 |
| **地址库** | 全局收货地址数据查看与管理 |

---

## 项目结构

```text
pharmacy-dispensing-system/
├── backend/            # 后端 API 服务
│   ├── src/
│   │   ├── controllers/  # 控制器
│   │   ├── models/       # 数据模型
│   │   ├── routes/       # 路由
│   │   └── services/     # 业务逻辑
│   └── package.json
├── frontend/           # 前端 Web 应用
│   ├── src/
│   │   ├── views/      # 页面视图
│   │   ├── components/ # 公共组件
│   │   └── store/      # 状态管理
│   └── package.json
├── docs/               # 项目文档与 API 接口说明
├── LICENSE
└── README.md
```
---


#### 前台启动方式
安装所需文件 yarn install 
运行 yarn run dev

#### 默认后台账户密码
[管理员]
admin
123456

[用户]
小程序登录

#### 项目截图

|  |  |
|---------------------|---------------------|
| ![](./assets/image%20(1).png) | ![](./assets/image%20(2).png) |
| ![](./assets/image%20(3).png) | ![](./assets/image%20(4).png) |
| ![](./assets/image%20(5).png) | ![](./assets/image%20(6).png) |
| ![](./assets/image%20(7).png) | ![](./assets/image%20(8).png) |
| ![](./assets/image%20(9).png) | ![](./assets/image%20(10).png) |
| ![](./assets/image%20(11).png) | ![](./assets/image%20(12).png) |

| ![](./assets/app_image%20(1).png) | ![](./assets/app_image%20(2).png) |
| ![](./assets/app_image%20(3).png) | ![](./assets/app_image%20(4).png) |
| ![](./assets/app_image%20(5).png) | ![](./assets/app_image%20(6).png) |
| ![](./assets/app_image%20(7).png) | ![](./assets/app_image%20(8).png) |
| ![](./assets/app_image%20(9).png) | ![](./assets/app_image%20(10).png) |
| ![](./assets/app_image%20(11).png) | ![](./assets/app_image%20(12).png) |
| ![](./assets/app_image%20(13).png) | ![](./assets/app_image%20(14).png) |

#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.**黑奴价格**

> 项目部署调试不好包退！功能逻辑没讲明白包退！

<div align=center><img align="center" src="./assets/product_word.png" alt="fankekeke" /></div>

#### 其它资源
[2026年-答辩顺利通过-客户评价🀄](https://berserker287.github.io/2026/06/29/2026%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2025年-答辩顺利通过-客户评价🍜](https://berserker287.github.io/2025/06/18/2025%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)

#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)

<div align="center"><img align="center" src="./assets/chat_qr_code.png" alt="fankekeke" width=250 /></div>

<p><img align="center" src="./assets/wechat_group.png" alt="fankekeke" /></p>

**感谢查看**
