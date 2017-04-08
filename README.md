# APICloud-App-Templates
基于[APICloud](http://www.apicloud.com)平台开发的应用案例模版源码合集，收集一些优秀的基于 APICloud 技术开发的应用模板，欢迎更多的开发者共享优质模板。

更多实际应用案例可以到[APICloud开发案例](http://www.apicloud.com/cases)查看，体验一下使用APICloud开发的App的功能、性能和体验。

1. [仿每日优鲜应用模版](https://github.com/apicloudcom/APICloud-7Days-Online-Training-Tutorials/tree/master/missfresh/widget)：

- 模仿每日优鲜APP 2.0.2版本开发，包含APP源码、编译后的Android安装包（iOS的需要自己编译）、UI架构设计、服务端接口文档等
- 应用数据存放在APICloud数据云上，在APP中使用标准的api.ajax与服务端数据通信
- 界面布局采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能包括：定位、城市切换，商品列表、下拉刷新、上拉加载、商品详情、购物车、登陆、注册、个人中心、本地存储、图片缓存、百度地图、推送、版本管理等
- 用到的UI模块包括：输入框模块[UIInput](http://docs.apicloud.com/Client-API/UI-Layout/UIInput)、多级选择器模块[UIActionSelector](http://docs.apicloud.com/Client-API/UI-Layout/UIActionSelector)、轮播图模块[UIScrollPicture](http://docs.apicloud.com/Client-API/UI-Layout/UIScrollPicture)
- 其他扩展模块包括：百度地图模块[bMap](http://docs.apicloud.com/Client-API/Open-SDK/bMap)、个推推送模块[pushGeTui](http://docs.apicloud.com/Client-API/Open-SDK/pushGeTui)、版本管理及热更新模块[mam](http://docs.apicloud.com/Client-API/Cloud-Service/mam)、本地数据库模块[db](http://docs.apicloud.com/Client-API/Func-Ext/db)

2. [仿大众点评应用模板](https://github.com/apicloudcom/APICloud-App-Templates/tree/master/dianping/widget)

- 模仿大众点评APP 6.0.1版本开发，包含APP源码和编译后的Android安装包（iOS的需要自己编译）
- 应用数据存放在APICloud数据云上，在APP中使用标准的api.ajax与服务端数据通信
- 界面布局采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能包括：欢迎页、定位、城市列表，商户列表、下拉刷新、上拉加载、商户详情、登陆、注册、个人中心、推送消息列表、二维码扫描、语音识别、图片缓存、百度地图等
- 用到的UI模块包括：输入框模块[UIInput](http://docs.apicloud.com/Client-API/UI-Layout/UIInput)、轮播图模块[UIScrollPicture](http://docs.apicloud.com/Client-API/UI-Layout/UIScrollPicture)、城市列表模块[UICityList](http://docs.apicloud.com/Client-API/UI-Layout/UICityList)
- 其他扩展模块包括：百度地图模块[bMap](http://docs.apicloud.com/Client-API/Open-SDK/bMap)、二维码扫描模块[FNScanner](http://docs.apicloud.com/Client-API/Func-Ext/FNScanner)、语音识别模块[SpeechRecognizer](http://docs.apicloud.com/Client-API/Open-SDK/speechRecognizer)、本地数据库模块[db](http://docs.apicloud.com/Client-API/Func-Ext/db)等

3. [仿今日头条应用模板](https://github.com/apicloudcom/APICloud-App-Templates/tree/master/toutiao/widget)

- 模仿今日头条APP 5.4.5版本开发，包含APP源码和编译后的Android安装包（iOS的需要自己编译）
- 应用数据存放在APICloud数据云上，在APP中使用标准的api.ajax与服务端数据通信
- 界面布局采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能包括：广告页、分类导航、新闻列表、评论列表、下拉刷新、上拉加载、新闻详情、视频播放、图片浏览、登陆、注册、个人中心、第三方登陆、推送消息、版本管理等
- 用到的UI模块包括：输入框模块[UIInput](http://docs.apicloud.com/Client-API/UI-Layout/UIInput)、对话框模块[dialogBox](http://docs.apicloud.com/Client-API/UI-Layout/dialogBox)、底部导航模块[navigationBar](http://docs.apicloud.com/Client-API/Nav-Menu/navigationBar)
- 其他扩展模块包括：视频播放模块[videoPlayer](http://docs.apicloud.com/Client-API/Func-Ext/videoPlayer)、图文浏览模块[photoBrowserTouTiao](http://docs.apicloud.com/Client-API/UI-Layout/photoBrowserTouTiao)、QQ登录模块[qq](http://docs.apicloud.com/Client-API/Open-SDK/qq)、本地数据库模块[db](http://docs.apicloud.com/Client-API/Func-Ext/db)等

4. [仿天猫商城应用模版](https://github.com/apicloudcom/Tmall-Source)
- 模仿天猫商城APP开发，包含APP源码和编译后的Android安装包（iOS的需要自己编译）
- 界面布局采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能包括：搜索、轮播广告页、分类导航、商品列表、资讯列表、店铺、商品详情、购物车、消息、登陆、注册、个人中心等
- 用到的功能模块包括：二维码扫描模块[FNScanner](http://docs.apicloud.com/Client-API/Func-Ext/FNScanner)、科大讯飞语音识别的sdk[speechRecognizer](http://docs.apicloud.com/Client-API/Open-SDK/speechRecognizer)
5. [脉脉应用模版](https://github.com/apicloudcom/maimai)
- 模仿脉脉APP开发，包含APP源码和编译后的Android安装包（iOS的需要自己编译）
- 界面布局采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能包括：搜索、资讯列表、资讯详情、分类导航条、联系人列表、消息中心、个人中心等
- 用到的UI模块包括：数据列表模块[UIListView](http://docs.apicloud.com/Client-API/UI-Layout/UIListView)、通讯录模块[contact](http://docs.apicloud.com/Client-API/Device-Access/contact)
- 用到的功能模块包括：微信分享模块[weiXin](http://docs.apicloud.com/Client-API/Open-SDK/weiXin)、新浪微博分享模块[weibo](http://docs.apicloud.com/Client-API/Open-SDK/weibo)科大讯飞语音识别的sdk[speechRecognizer](http://docs.apicloud.com/Client-API/Open-SDK/speechRecognizer)、二维码扫描模块[FNScanner](http://docs.apicloud.com/Client-API/Func-Ext/FNScanner)等
6. [仿途牛应用模版](https://github.com/apicloudcom/Tuniu-Source)
- 模仿途牛APP开发，包含APP源码和编译后的Android安装包（iOS的需要自己编译）
- 应用数据存放在APICloud数据云上，在APP中使用标准的api.ajax与服务端数据通信
- 界面布局采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能包括：轮播广告页、侧边栏、搜索、城市列表、顶部筛选栏、电话拨打、分类导航、旅游产品列表、产品详情、注册等
- 用到的UI模块包括：轮播图模块[UIScrollPicture](http://docs.apicloud.com/Client-API/UI-Layout/UIScrollPicture)、城市列表模块[UICityList](http://docs.apicloud.com/Client-API/UI-Layout/UICityList)
7. [仿返利网应用模版](https://github.com/apicloudcom/Fanli-Source)
- 模仿返利网APP开发，包含APP源码和编译后的Android安装包（iOS的需要自己编译）
- 界面布局：采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能：瀑布流布局首页、搜索栏、轮播图、webView页面、水平滚动分段标题栏、列表页、“我的”页、“更多”页等各种不同布局页面
- 程序亮点：采用openGroup方法实现APP引导页，采用flexbox方式实现首页类瀑布流式布局的开发;
- 开发建议：程序开发时使用Swipe.js框架实现滚动轮播图，如无特殊需求，建议开发者在开发轮播图时，采用[UIScrollPicture](http://docs.apicloud.com/Client-API/UI-Layout/UIScrollPicture) 模块实现轮播图功能轮播图模块来开发实现。

8. [仿搜狐视频应用模版](https://github.com/apicloudcom/Sohu-Source)
- 模仿搜狐视频APP开发，包含APP源码和编译后的Android安装包（iOS的需要自己编译）
- 界面布局：采用APICloud 5大UI组件：Widget、Layout、Window、Frame和UIModules
- 主要功能：“首页”“热点”“片库”、视频详情页等不同页面的布局及轮播图、搜索栏、播放器等功能／样式
- 程序亮点："离线"页面使用api.openFrameGroup方式实现页面的滑动切换，并关联了样式的同步改变；4个主页面采用frame+frameGroup混合组成，开发者可参考程序在frame和frameGroup之间如何进行页面切换处理的;
- 开发建议：大部分页面仅为静态页面展示，缺少对应的处理逻辑，开发者仅参考下作者的页面布局，页面切换等开发方法即可。
9. [仿饿了么应用模版](https://github.com/apicloudcom/Eleme-Source)

10. [仿网易新闻应用模板](https://github.com/apicloudcom/163news-Source)

11. [仿玩转晋城应用模板](https://github.com/apicloudcom/Jincheng-Source)

12. [仿糗事百科应用模板](https://github.com/apicloudcom/Qiushibaike-Source)

13. [仿网易云音乐应用模版](https://github.com/apicloudcom/163music-Source)

14. [仿QQ电影票应用模板](https://github.com/apicloudcom/QQFilm-Source)
