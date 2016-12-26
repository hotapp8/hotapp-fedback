# HotApp小程序用户反馈组件

## 开始使用
### 1.在app.js里onLaunch()初始化hotapp
```
//copyhotapp.js到自己项目中，接入hotapp.js
var hotapp = require('utils/hotapp.js');
//初始化hotapp，使用自己的hotappkey（注册地址：https://weixin.hotapp.cn/api）
hotapp.init('hotapp2427615');
```
### 2.在自己项目中引入文件代码

1.images文件（images）

2.feeback页面（page/feedbcak）

3.模板页面（template）

3.按钮代码
```

//js，事件处理函数,跳转到feedback页面
bindViewTap: function () {
    wx.navigateTo({
      url: '../feedback/index'
    })
},
//wxml
<view class="section" bindtap="bindViewTap">
    <view class="button">
      <text>反馈系统演示</text>
   <text>></text>
</view>
```
### 3.你可以hotapp小程序统计后台查看反馈信息（注意关联好自己hotappkey）
![image](http://7xn9on.com1.z0.glb.clouddn.com/IMG_0098.PNG)
## 功能展示
![image](http://7xn9on.com1.z0.glb.clouddn.com/IMG_0090.PNG?imageView2/2/w/300/h/500/interlace/0/q/100)
![image](http://7xn9on.com1.z0.glb.clouddn.com/IMG_0091.PNG?imageView2/2/w/300/h/500/interlace/0/q/100)
![image](http://7xn9on.com1.z0.glb.clouddn.com/IMG_0094.PNG?imageView2/2/w/300/h/500/interlace/0/q/100)
![image](http://7xn9on.com1.z0.glb.clouddn.com/IMG_0095.PNG?imageView2/2/w/300/h/500/interlace/0/q/100)
![image](http://7xn9on.com1.z0.glb.clouddn.com/IMG_0096.PNG?imageView2/2/w/300/h/500/interlace/0/q/1000)
![image](http://7xn9on.com1.z0.glb.clouddn.com/IMG_0097.PNG?imageView2/2/w/300/h/500/interlace/0/q/100)

### 4.关于我们

HotApp小程序统计：是第一个微信第三方小程序统计工具，包含实时统计小程序的日活，启动次数，以及留存等信息。同时支持自定义事件统计，小程序带参数二维码渠道统计功能正在邀请内测。https://weixin.hotapp.cn

免费云后台申请地址 https://weixin.hotapp.cn/cloud

API 文档地址：https://weixin.hotapp.cn/api

hotapp小程序技术讨论QQ群：173063969
