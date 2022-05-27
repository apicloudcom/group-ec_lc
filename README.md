# 项目介绍

## 功能描述

本模板为拼团商城APP，主要功能包括商品分类、商品详情、订单管理等页面。里面涉及到的所有页面都是由APICloud可视化工具中的高级组件进行拼接而成的静态页面，不涉及业务逻辑相关的操作。目的是为了实现在APICloud可视化工具设计界面中能够正常显示页面中的内容。

## 可视化界面显示效果截图

![png1](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/758d273b01c415828226993f445f6404.png)
![png2](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/f03172139f25afac4cca06d83d320d9f.png)
![png3](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/0270de10a8da8c8702f4c0ead19931fd.png)
![png4](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/f40b74748e6aae4bbf6bc58694d6e6cb.png)
![png5](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/f40b74748e6aae4bbf6bc58694d6e6cb.png)

## 源码文件目录结构说明

项目源码在widget目录下，该目录下的文件说明如下：

```
┌─component/ // 项目公共组件目录 
│ ├─hoc-aboutus-sgm.stml // [高级组件]关于我们
│ ├─hoc-activity-area-sgm.stml // [高级组件]活动专区
│ ├─hoc-address-list-sgm.stml // [高级组件]地址列表
│ ├─hoc-classify-list-sgm.stml // [高级组件]分类列表
│ ├─hoc-classify-tab-sgm.stml // [高级组件]分类切换菜单 
│ ├─hoc-commodity-card-sgm.stml // [高级组件]商品信息卡片
│ ├─hoc-commodity-swiper-sgm.stml // [高级组件]商品轮播图
│ ├─hoc-count-down-sgm.stml // [高级组件]倒计时
│ ├─hoc-detail-share-sgm.stml // [高级组件]分享选择列表
│ ├─hoc-edit-address-sgm.stml // [高级组件]地址编辑
│ ├─hoc-form-list-sgm.stml // [高级组件]信息展示列表
│ ├─hoc-goods-baseinfo-sgm.stml // [高级组件]商品详细信息
│ ├─hoc-goods-detail-btns-sgm.stml // [高级组件]商品详情付款按钮组
│ ├─hoc-goods-detail-sgm.stml // [高级组件]商品详情
│ ├─hoc-goods-spec-sgm.stml // [高级组件]商品规格信息
│ ├─hoc-login-sgm.stml // [高级组件]登录
│ ├─hoc-menu-list-sgm.stml // [高级组件]可操作列表
│ ├─hoc-nav-bar-sgm.stml // [高级组件]头部导航
│ ├─hoc-no-data-sgmstml // [高级组件]暂无数据
│ ├─hoc-order-address-sgm.stml // [高级组件]订单地址
│ ├─hoc-order-detail-status-sgm.stml // [高级组件]商品订单状态
│ ├─hoc-order-goods-list-sgm.stml // [高级组件]订单商品列表
│ ├─hoc-order-list-sgm.stml // [高级组件]订单列表
│ ├─hoc-orderbtn-group-sgm.stml // [高级组件]我的订单操作按钮组
│ ├─hoc-pay-address-sgm.stml // [高级组件]付款地址
│ ├─hoc-pay-footer-btn-sgm.stml // [高级组件]付款底部操作按钮
│ ├─hoc-pay-remark-sgm.stml // [高级组件]付款备注
│ ├─hoc-personal-data-sgm.stml // [高级组件]个人信息面板
│ ├─hoc-pin-rules-sgm.stml // [高级组件]拼团规则
│ ├─hoc-platform-deal-sgm.stml // [高级组件]平台协议，可传入富文本内容
│ ├─hoc-search-bar-sgm.stml // [高级组件]搜索框
│ ├─hoc-slide-bar-sgm.stml // [高级组件]侧边栏
│ ├─hoc-spell-succtip-sgm.stml // [高级组件]拼团成功提示
│ ├─hoc-swiper-sgm.stml // [高级组件]轮播图
│ ├─hoc-tab-bar-sgm.stml // [高级组件]底部导航栏
│ ├─hoc-tab-switch-sgm.stml // [高级组件]tab切换
│ ├─hoc-user-menu-od.stml // [高级组件]个人信息菜单列表
│ ├─hoc-user-panel-sgm.stml // [高级组件]个人信息操作面板
├─images/ // 图片素材图标资源目录 
├─pages/ // AVM页面目录 
│ ├─about/ 
│ │ └─about.stml // 关于我们页 
│ ├─address_list/ 
│ │ └─address_list.stml // 地址列表页 
│ ├─commodity_detail/ 
│ │ └─commodity_detail.stml // 商品详情页 
│ ├─edit_address/ 
│ │ └─edit_address.stml // 编辑地址页 
│ ├─login/ 
│ │ └─login.stml // 登录页 
│ ├─main/ 
│ │ └─main.stml // 主页 
│ ├─order/ 
│ │ └─order.stml // 订单列表页 
│ ├─order_detail/ 
│ │ └─order_detail.stml // 订单详情页 
│ ├─pay/ 
│ │ └─pay.stml // 付款页 
│ ├─personal_data/ 
│ │ └─personal_data.stml // 个人信息主页 
│ ├─sort/ 
│ │ └─sort.stml // 分类主页 
│ ├─sort_list/ 
│ │ └─sort_list.stml // 分类商品列表页 
├─script/ // JavaScript脚本目录 
│ │ └─coustant.js // 放常量的文件 
└─config.xml // 应用配置文件
└─config.json// 底部导航栏配置文件
```
## 怎么使用可视化工具进行开发

1. 下载最新版的[APICloud Studio 3](https://www.apicloud.com/studio3#downloadBtn)

2. 下载成功后，安装后打开，顶部菜单选择【项目】-【新建项目】，填写应用名称，选择相应模板，点【完成】按钮进行创建。

![png6](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/5ca67ec0d0af2caae978e0763cdd81f4.png)

3. 创建完项目后打开某一个页面，点击左上角图标可切换为可视化界面，可进行页面的设计，左侧栏可根据项目需求拖拽任意组件到画布中，右侧属性设置栏可对拖拽的组件进行设置。具体操作可查看 [可视化工具的使用视频](https://www.apicloud.com/video_play/20_1825)。

![png7](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/ad9a8bc01a3b69393052711af94739c2.png)
![png8](http://ae8b3ee28597856d3283.qiniucdn.apicloud-system.com/apicloud/ec850d72de638cb572c0eb7640ea0347.png)

## 技术支持

使用中若有任何疑问可到APICloud论坛 [AVM多端](https://developer.yonyou.com/forum-71-1.html) 专区发帖提问。官方技术支持和众多活跃开发者会第一时间为您提供技术支持。


## 项目源码

http://git.yonyou.com/APICloud-CF/group-ec_lc


