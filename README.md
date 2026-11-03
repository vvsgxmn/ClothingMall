# 基于SpringBoot+Vue的服装售卖商城

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

ClothingMall 是一款面向潮流服饰电商的服装售卖商城，支持多级分类浏览、颜色/尺码多规格 SKU、购物车结算、优惠券抵扣与钱包支付、物流发货与买家秀评价，并集成通义千问驱动的 AI 穿搭造型师；普通用户与管理员双端协同，适合毕设、课设与学习参考。

## 主要功能模块

- **用户认证模块**：支持普通用户与管理员统一登录注册，JWT 鉴权并按角色跳转商城前台/运营中台
- **商城前台模块**：首页画报轮播、分类入口与推荐单品、全部服饰筛选检索、商品详情选色选码加购
- **交易履约模块**：购物袋勾选结算、优惠券领取与抵扣、钱包余额支付、订单支付/发货/确认收货/取消
- **会员运营模块**：收藏心愿单、浏览足迹、收货地址、买家秀评价与个人中心资料维护
- **AI 穿搭造型师**：通义千问驱动的场合搭配与尺码建议对话，管理端可审计问答日志
- **管理中台模块**：ECharts 运营看板（含低库存预警与优惠券核销）、商品/分类/订单/评价/轮播/优惠券/用户管理

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E5%85%A8%E9%83%A8%E6%9C%8D%E9%A5%B0.png" alt="全部服饰" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E5%95%86%E5%93%81%E8%AF%A6%E6%83%85.png" alt="商品详情" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E8%B4%AD%E7%89%A9%E8%BD%A6.png" alt="购物车" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E4%B8%8B%E5%8D%95%E9%A1%B5%E9%9D%A2.png" alt="下单页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E8%AE%A2%E5%8D%95%E9%A1%B5%E9%9D%A2.png" alt="订单页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/AI%E7%A9%BF%E6%90%AD.png" alt="AI穿搭" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E7%AE%A1%E7%90%86%E5%91%98%E4%BB%AA%E8%A1%A8%E7%9B%98.png" alt="管理员仪表盘" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E5%95%86%E5%93%81%E7%AE%A1%E7%90%86.png" alt="商品管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/clothingmall/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->

## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）
