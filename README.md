# wanxiao-js-api
-玩校JSSDK  v1.1.8, v1.1.9版本
-原理 web页面用js方法通过 jsbrige与原生系统进行通信,定义了一系列的原生功能列表,满足web页面使用需求.
-[需要特别注意,JSSDK方法必须在玩校中进行运行才能完成]
#
-v1.1.8 JSSDK版本支持目前玩校v3.2.7及以上版本
-v1.1.9 JSSDK版本支持目前玩校v3.3.0及以上版本
#
-demo 里js_demo_new.html 是对JSSDK v1.1.9使用的例子
-demo 里js_demo_old.html 是对JSSDK v1.1.8使用的例子

#
-功能列表
#
-0.0.1 getToken 获取用户信息
#
-0.0.2 getUserJsonValue 获取用户信息
#
-0.0.3 sendRemoteNotification 发起推送
#
-0.0.4 openCamera 打开相机
#
-0.0.5 shareTo   分享 
#
-0.0.6 getCredits 获取积分信息
#
-0.0.7 addCredits 增加积分
#
-0.0.8 reduceCredits 减去积分
#
-0.0.9 openPayWay   打开收银台
#
-0.1.0 closeAppWeb  关闭打开的APP界面
#
-0.1.1 setMenu      设置menu
#
-0.1.2 scanBarcode  扫描条码
#
-0.1.3 shake        摇一摇
#
-0.1.4 getLocation  获取用户信息
#
-0.1.5 appChannel   三方插件调用command方法
#
-0.1.6 getUserGravatar  获取用户头像
#
-0.1.7 openImageView   打开图片浏览
#
-0.1.8 getNetworkStatus 获取网络状态
#
-0.1.9 selectImage     选择图片查看
#
-0.2.0 selectImage1    选择图片扩展
#
-0.2.1 setTitle       设置标题
#
-0.2.2 commonCallback  统一回调接口  (私有)
#
-0.2.3 setMenu1        设置menu扩展接口           ------JSSDKV1.1.8 玩校v3.2.7
#
-0.2.4 showMenu        显示menu
#
-0.2.5 hideMenu        隐藏menu
#
-0.2.6 setConfig       设置配置项 (私有)
#
-0.2.7 getConfig       获取配置项 (私有)
#
-0.2.8 NCPStartTalkFun 调用直播   (私有)          -------JSSDKV1.1.9 玩校v3.3.0 
