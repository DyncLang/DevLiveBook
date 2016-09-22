####[从无到有开发连麦直播技术点整理-AnyRTC](https://github.com/DyncLang/DevLiveBook)

#### 直播关键字
**采集**、**前处理**、**编码**、**传输**、**解码**、**渲染**, **推流**, **拉流**、**连麦**、**直播**、**互动**、**RTMP**

####原理科普

1. [为何一直推荐WebRTC？](http://www.jianshu.com/p/40d4d4f172e6)
4. [RTMP vs RTMFP](http://www.jianshu.com/p/8f219e8aeb54)
5. [大话直播](http://www.jianshu.com/p/dd73132ea5e2)
3. [android音视频点/直播模块开发一些基本概念](http://www.jianshu.com/p/8436c7353296)
2. [【如何快速的开发一个完整的iOS直播app】(原理篇)](http://bbs.520it.com/forum.php?mod=viewthread&tid=2049)
3. [姚东（YY），金山18667号码农，张云龙（全民TV), 何李石（七牛）分享如何搭建直播平台浅谈](https://www.zhihu.com/question/42162310)
4. [视频参数（流媒体系统，封装格式，视频编码，音频编码，播放器）对比](http://blog.csdn.net/leixiaohua1020/article/details/11842919)
5. [流媒体中用到的几个协议简介](http://zzqhost.github.io/hostwiki/%E5%A4%9A%E5%AA%92%E4%BD%93%E7%9B%B8%E5%85%B3_%E6%B5%81%E5%AA%92%E4%BD%93%E4%B8%AD%E7%94%A8%E5%88%B0%E7%9A%84%E5%87%A0%E4%B8%AA%E5%8D%8F%E8%AE%AE%E7%AE%80%E4%BB%8B.html)
6. [【总结】视音频编解码技术零基础学习方法](http://lib.csdn.net/article/liveplay/40882)
7. [【移动开发】关于视频直播技术，你想要知道的都在这里了（三）编码和封装](http://www.jianshu.com/p/b61cd0bc2abe)
8. [【HTML 5】 视频直播一站式扫盲](http://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653577297&idx=1&sn=a292ff3b499168f4eb589e40b7aa6d13&scene=4#wechat_redirect)
9. [【React Native】 在直播应用中的实践 | 架构师实践日](https://mp.weixin.qq.com/s?__biz=MjM5NzAwNDI4Mg==&mid=2652190492&idx=1&sn=1e63171591ca6bb4e83bd5cc16aefbff&scene=0&key=8d8120cb97983fad78d4439160fb7aa075f4d554feb0dc78797c41592277d6ac71005bd52f7581cd5662dd4f04b657c3&ascene=0&uin=MjIxOTQ3OTM1&devicetype=iMac%20MacBookAir6,2%20OSX%20OSX%2010.11.5%20build%2815F34%29&version=11020201&pass_ticket=%2bHT0TrV0J81HeO2LhW3/jdBApmf%2bX8PC/%2bITJ9F92lo=)
10. [TCP 的那些事儿（上）](http://coolshell.cn/articles/11564.html)
11. [【移动开发】关于视频直播技术，你想要知道的都在这里了（三）编码和封装](http://www.jianshu.com/p/b61cd0bc2abe)

#### WebRTC 

1. [AnyRTC-RTMP 商业级开源代码，高效稳定](https://github.com/AnyRTC/AnyRTC-RTMP)
1. [Getting Started with WebRTC](http://www.html5rocks.com/en/tutorials/webrtc/basics/)
1. [【WebRTC】使用WebRTC搭建前端视频聊天室——入门篇](http://lingyu.wang/#/post/2014/3/15/webRTC-1)
2. [【WebRTC】用WebRTC搭建前端视频聊天室——信令篇](http://lingyu.wang/#/post/2014/3/18/webRTC-2)
3. [用WebRTC搭建前端视频聊天室——点对点通信篇](https://segmentfault.com/a/1190000000733774)
4. [WebRTC的RTCDataChannel](http://lingyu.wang/#/post/2014/5/22/webrtc-data-channels)
5. [7 Creative Uses of WebRTC’s Data Channel](https://bloggeek.me/webrtc-data-channel-uses/)
6. [Android之WebRTC介绍](http://www.devtf.cn/?p=669)


####流媒体-服务器-CDN

1. [奥点云](http://www.aodianyun.com/)
4. [七牛](http://www.qiniu.com/)
5. [网宿](http://www.wangsucloud.com/)
6. [UCloud](https://www.ucloud.cn/)
1. [【**Nginx**】优秀的免费Web服务器，通过扩展的nginx-rtmp模块，可以支持流媒体播放和管理。](https://github.com/arut/nginx-rtmp-module)
2. [【**EasyDarwin**】高性能开源流媒体服务器，支持RTSP、HLS、HTTP直播](https://github.com/EasyDarwin/EasyDarwin)

#### **IM** 

礼物系统，聊天系统，弹幕系统多半依赖IM，可根据自定义的消息来定义不同消息类型；

1. [环信](http://www.easemob.com/)
2. [极光IM](https://www.jiguang.cn/im)
3. [Teameeting-MsgServer **免费开源**](https://github.com/Teameeting/Teameeting-MsgServer)


#### 连麦互动

 1. [视频直播中用户连麦技术模型与特点分析（转载）](http://www.jianshu.com/p/d525a4ca1d17)
 2. [全球首创4人连麦-RTMP + RTC](https://www.anyrtc.io/RTMPC-product/)
 3. [亲加通讯云郝飞：探讨直播低延迟低流量的粉丝连麦技术](http://www.csdn.net/article/a/2016-07-08/15839390)
 4. [探讨直播低延迟低流量的粉丝连麦技术](http://mp.weixin.qq.com/s?__biz=MzI4NzE1NTYyMg==&mid=2651101375&idx=1&sn=9f1469979c93fbba5ecb5f5fd1faea5b&scene=5&srcid=07077MlnmSrrscM6SteuLpAN#rd)

#### 性能优化-架构
1. [移动直播技术秒开优化经验（含PPT）](http://toutiao.com/i6278412629417394689/)
2. [QQ空间直播秒开优化实践 ](http://bugly.qq.com/bbs/forum.php?hmsr=toutiao.io&mod=viewthread&tid=1204&utm_medium=toutiao.io&utm_source=toutiao.io)
3. [Facebook 直播如何撐起瞬間 80 萬人的流量？](http://www.inside.com.tw/2016/07/01/how-facebook-live-streams-to-800000-simultaneous-viewers?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
4. [浅析低延迟直播协议设计：RTP/RTCP](http://mp.weixin.qq.com/s?__biz=MzIyNjE4NjI2Nw==&mid=2652556829&idx=1&sn=5e341308669c930e36d9908919d4ab82&scene=0#wechat_redirect)
5. [如何实现1080P延迟低于500ms的实时超清直播传输技术](http://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653547697&idx=1&sn=acc748b7fcf0058b58e244970e51eabc&scene=0&from=groupmessage&isappinstalled=0#wechat_redirect)
6. [《程序员》：聚光灯下的熊猫TV技术架构演进](http://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&mid=2650687197&idx=1&sn=5fa841cbf95f2a8664906452bda37a91&chksm=bea6370e89d1be18d9e5b04a9c8000b2ffd336bf5f675e604b59eee4e07624193bc5e4838a4f&scene=0#wechat_redirect)
7. [教育交互直播的技术难点与架构探索](http://mp.weixin.qq.com/s?__biz=MzI0NzUxMzQ2Mg==&mid=2247483762&idx=1&sn=3a0ffb2a2259652107861878f8d57546)


####优秀开源项目
 
1.  [【Android】DyncRTMPLiveClient-Android-推流-拉流-连麦-弹幕](https://github.com/AnyRTC/DyncRTMPLiveClient-Android)
2. [【IOS】MPCHybirdEngine-IOS-推流-拉流-连麦-美颜-弹幕](https://github.com/AnyRTC/RTMPCHybirdEngine-IOS)
3. [ijkplayer-播放器](https://github.com/Bilibili/ijkplayer)
4. [基于ijkplayer的视频直播软件](%E5%9F%BA%E4%BA%8Eijkplayer%E7%9A%84%E8%A7%86%E9%A2%91%E7%9B%B4%E6%92%AD%E8%BD%AF%E4%BB%B6)
5. [【IOS】现了作为一个直播App的基本功能，比如本地视频流采集、播放、美颜、礼物、点赞出心](https://github.com/GrayJIAXU/520Linkee)
6. [【IOS】PLCameraStreamingKit](https://www.sdk.cn/datas/3190)
7. [【IOS】一个高仿项目](https://github.com/SunLiner/MiaowShow)


#### **App技术点**

1. [**【IOS】**仿在直播、映客、Periscope、花椒等直播APP点赞动画](https://github.com/singer1026/DMHeartFlyAnimation)
2. [**【IOS】**上弹幕源码实现](https://github.com/panghaijiao/HJDanmakuDemo)
3. [**【IOS】**基于IOS的图像处理 **美颜**](https://github.com/BradLarson/GPUImage)
4. [  开源的H.264编码器](https://github.com/cisco/openh264/commits/master)
5. [【IOS】直播开源项目 喵播-APP](http://jhdr.xhby.net/content/201608/03/c213550.html)
1. [【Android】开源弹幕](https://github.com/Bilibili/DanmakuFlameMaster)
2. [【Android】仿花椒直播聊天的时候消息向上弹出，一定时间后自动消失的效果](https://github.com/journey-M/AutoMissingMessage)
3. [QQ 空间直播页面礼物冒泡效果](http://www.diycode.cc/topics/115)


#### 服务提供商

1. [AnyRTC-全球首创RTMP + RTC](https://www.anyrtc.io/);
4. [网易云信 - 在线教育;](http://netease.im/)
6. [腾讯云 - 老牌公司;](https://www.qcloud.com/solution/video.html)
7. [声网  ](http://cn.agora.io/)
8. [阿里云](https://help.aliyun.com/document_detail/29964.html)
9. [一只视频程序猿的移动直播SDK初体验](http://science.china.com.cn/2016-06/06/content_8816359.htm)

#### 专栏博客

1. [WebRTC开发总结](http://www.cnblogs.com/lingyunhu/)
3. [铂渊信息技术](http://www.jianshu.com/users/eadc7531ecb8/latest_articles)
4. [雷霄骅(leixiaohua1020)的专栏一个广院工科生的视音频技术笔记](http://blog.csdn.net/leixiaohua1020?viewmode=contents)

#### 竞品分析-产品方向

1. [全民娱乐直播：映客、花椒直播竞品分析](http://www.jianshu.com/p/48b80708d099)
4. [花椒和映客直播App竞品分析](http://www.woshipm.com/evaluating/305667.html)
5. [视频直播的发展历程、产品分类及现况](http://www.jianshu.com/p/1936e71395a2)
6. [站在风口，移动直播+营销将何去何从？](http://www.jianshu.com/p/efbfce255925)
7. [“映客直播”产品体验报告](http://www.jianshu.com/p/6bb63eff1654)
8. [移动直播异军突起：ME直播产品体验报告](http://www.woshipm.com/evaluating/339187.html)

####业界新闻-

1. [AnyRTC：国内独家拥有四连麦技术的直播平台](http://www.jianshu.com/p/d106a1756d8a)
2. [直播逐渐渗透各行各业，在未来有哪些新的趋势？](https://www.zhihu.com/question/48106149)
3. [给你一幅中国 VR 产业的全景图（内附PDF版）](http://geekpark-media.qiniudn.com/geekpark-vr-report.pdf)
5. [在直播大战中杀出重围的一种套路—搞CP](http://mp.weixin.qq.com/s?__biz=MjM5MjgwNjgwMA==&mid=2649764998&idx=1&sn=dddc9091451130ede06d5533f5f699a9&scene=1&srcid=0901KeN82NVg2zNtC9s4aXoF#wechat_redirect)
6. [PPT+长文推荐：『直播』大时代](https://zhuanlan.zhihu.com/p/20717041)
7. [以直播类产品为例，产品总监如何制定公司2016年的KPI？](http://www.woshipm.com/pmd/302216.html)
5. [【直播风口】--资讯整合](http://www.jianshu.com/p/802ff7338c68)
6. [游戏直播产品的 10 个 Growth Hacking 营销案例盘点](http://www.jianshu.com/p/fbd727863b23)


---
**注意：**`doc`文件夹里面有一些文档；
[GitHub持续更新-欢迎Star](https://github.com/DyncLang/DevLiveBook)

**欢迎加入我们一起研究直播技术：** 

> 
**QQ群：580477436** </br>

**Email: zhulang@dync.cc**

