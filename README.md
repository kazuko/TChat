## :rocket: 编码不易，点个star！如果觉得本项目对您有用，请随意打赏，谢谢。 ##

![wechatpay](https://github.com/WZTENG/TChat/blob/master/screenshots/WECHATPAY.png)&nbsp;&nbsp;&nbsp;&nbsp;
![alipay](https://github.com/WZTENG/TChat/blob/master/screenshots/ALIPAY.png)

**iOS版：https://github.com/WZTENG/ZChat**

**本项目使用网易云信IM加上网上开源项目编写，
（附上使用的开源地址，如有侵权或遗漏马上修改）。**

### 使用以下开源项目并修改了部分内容 ###

 > https://github.com/Curzibn/BottomDialog<br/>
 > https://github.com/LuckSiege/PictureSelector<br/>
 > https://github.com/Jude95/SwipeBackHelper<br/>
 > https://github.com/CJT2325/CameraView<br/>
 > https://github.com/bingoogolapple/BGAQRCode-Android<br/>
 > https://github.com/Naoki2015/CircleDemo<br/>
 > https://github.com/koral--/android-gif-drawable/<br/>
 > https://github.com/Sunzxyong/Recovery<br/>
 > https://github.com/wenmingvs/LogReport<br/>
 > https://github.com/SumiMakito/AwesomeQRCode<br/>
 > https://github.com/CarGuo/GSYVideoPlayer<br/>

当前编辑版本与编译环境：

- Android Studio 3.1.2
- Gradle Version 4.4
- Android Plugin Version 3.1.2
- Android SDK Platform-Tools 27.0.3
- Android 7.1.1 API25
- 真机原生7.1.2

提供已有测试账号，请勿修改相关信息！<br/>
 > 账号：dawa<br/>
 > 密码：123456<br/>

为了减小体积只保留一个armeabi-v7a，如果部分手机出现错误请自行修改配置<bt/>

* :memo:说明:android studio 3.1.2可能修改了什么东西，暂时去掉ndk，不然提示CreateProcess error=2, 系统找不到指定的文件。(错误提示指向一个ndk文件)

* :bug:已知Bug:<br/>
   > 1. 部份低版本系统侧滑返回会显示透明桌面(未修复)<br/>
   > 2. 二维码扫描框未根据屏幕尺寸进行调整(未修复)<br/>
   > 3. ~~朋友圈小视频目前无法在6.0以上使用，会导致崩溃(正在修复，2017/05/12 修复崩溃，但无法播放，2018/01/24 修复完成。)~~<br/>
   > 4. ~~修复低版本提示jar包错误(2017/05/10 修复完成)~~<br/>

* :memo:日志:<br/>
   > 1. 2018/01/23<br/>  >> :art:更新高德地图 3DMap_5.7.0 Navi_5.6.0 Search_5.7.0 Location_3.7.0 20180109版本<br/>
                         >> :art:更新聊天定位发送图片为实时图片，但接收图片为默认图片<br/>
   > 2. 2018/01/24<br/>  >> :art:更新朋友圈视频为IJKPlayer播放器，可以正常播放视频<br/>
   > 3. 2018/01/25<br/>  >> :sparkles:增加朋友圈音乐连接到百度随机播放歌曲<br/>
   > 4. 2018/01/31<br/>  >> :art:修改朋友圈链接使用jsoup爬虫简单分析网页再刷新内容<br/>
   > 5. 2018/02/01<br/>  >> :sparkles:升级IM到4.0，增加好友在线状态<br/>
   > 6. 2018/02/02<br/>  >> :sparkles:增加聊天表情雨<br/>
   > 7. 2018/02/06<br/>  >> :bug:修复设置里面的"网络通话设置","音视频通话网络探测"的bug<br/>
   > 8. 2018/03/06<br/>  >> :art:改进Tab小红点点击就消失的"bug"<br/>
   > 9. 2018/05/15<br/>  >> :art:改进Toolbar返回按钮与标题间隙<br/>
   > 10. 2018/08/21<br/>  >> :art:修改朋友圈发表界面。微信使用GridView，本项目使用RecyclerView与微信效果有点区别，主要在微信效果为覆盖，本项目为透传。<br/>
   > 11. 2018/08/22<br/>  >> :sparkles:增加类似公众号侧滑悬浮球效果，与微信有一点区别（还有点小bug）。同时在SwipeBackHelper中增加触摸回调实现位置判断来处理。<br/>
   > 12. 2018/11/23<br/>  >> :art:修改朋友圈图片浏览效果，具有点击放大与返回缩小效果。<br/>

:art: 截图<br/>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170309-133335.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170309-133340.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170314-151150.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170309-133350.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170309-132948.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170310-101434.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170310-101618.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170310-101902.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170320-104011.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170322-154439.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-141033.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-151113.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-151211.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-151222.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-151249.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-151457.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-151527.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-154807.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170412-154834.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170413-105031.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170413-105042.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170413-105052.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170414-174236.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075030.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075050.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075101.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075133.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075140.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075148.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075155.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170420-075301.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170426-133027.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170426-133039.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170426-161828.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170426-161908.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170511-130921.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170511-131055.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170511-152618.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170511-153120.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170512-164207.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20170516-135538.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180123-171843.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180124-141604.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180124-141617.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180125-164339.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180126-162243.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180126-162520.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180126-162701.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180125-173849.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180202-161549.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180202-161555.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180202-161557.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180821-185352.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180821-185416.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180822-190422.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180822-190430.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180822-190452.png"/>
</div>
<div>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180822-190503.png"/>
<img width="288" height="512" src="https://github.com/WZTENG/TChat/blob/master/screenshots/Screenshot_20180822-190518.png"/>
</div>
未完待续2018-08-22 13:30



