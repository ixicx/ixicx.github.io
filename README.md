# 直播源项目

- [目录](#目录)
- [**直播源广播电视简介**](#直播源广播电视仓库简介)
  - [有效性检测](#有效性检测)
  - [播放器推荐](#播放器推荐)
- [**广播电视源**](#广播电视源)
  - [**广播电视目录导航**](#广播电视目录导航)
  - [**直播源代理直播源**](#直播源代理直播源)
    - [直播源PHP代理](#直播源php代理-1)
    - [更新日志](#更新日志-1)
  - [**直播源代理直播平台源**](#直播源代理直播平台源)
    - [使用教程](#使用教程-2)
    - [更新日志](#更新日志-2)
  - [**直播源代理youtube源**](#直播源代理youtube源)
    - [使用教程](#使用教程-3)
    - [更新日志](#更新日志-3)
  - [**直播源代理4GTV源**](#直播源代理4gtv源)
    - [M3U文件](#m3u文件-4)
    - [更新日志](#更新日志-4)
  - [**直播源自制轮播源**](#直播源自制轮播源)
    - [M3U文件](#m3u文件-5)
    - [更新日志](#更新日志-5)
  - [**互联网收集直播源**](#互联网收集直播源)
    - [M3U文件](#m3u文件-6)
    - [更新日志](#更新日志-6)
  - [**直播源代理广播源**](#直播源代理广播源)
    - [使用教程](#使用教程-7)
    - [更新日志](#更新日志-7)
- [**鸣谢**](#鸣谢)  
---
---

# **直播源广播电视简介**


直播源广播电视是直播源项目之一，主要以分享全球IPTV直播源、广播源为主，所有电视直播源广播源均收集于互联网并经过精挑细选而成。同时为方便各位观看，直播源代理了一些其他平台可开放观看的直播节目/频道。IPTV/Radio内含有世界各国电视直播广播频道，因各国文件差异及认知水平不同在收看节目时请理性思考，恪守爱国、敬业、诚信、友善社会主义核心价值观公民个人层面的价值准则。

直播源项目包括：电视直播，关注直播源，直播源关注世界，世界在您身边！

直播源流媒体 Telegram频道：https://t.me/

直播源IPTV Telegram频道：https://t.me/

直播源流媒体 Telegram交流群：https://t.me/

直播源IPTV Telegram交流群：https://t.me/

---





## 有效性检测
> 有效性检测工具：IPTV Checker.exe
>   * 搜索一下
> 直播源节目源检测Bot：@iptvcheck_bot
>   * Bot需要在JMS直播源广播电视群中使用，频道有使用教程




---



## 播放工具推荐
> * Windows端：Potplayer、vlc
> 
> * 电视端：Kodi、TiviMate
> 
> * 手机端：Televizo
> 




---
---




# **广播电视源**
## **广播电视源目录导航**
* [直播源代理直播源](#直播源代理直播源)
* [直播源代理直播平台源](#直播源代理直播平台源)
* [直播源代理youtube源](#直播源代理youtube源)
* [直播源代理4GTV源](#直播源代理4gtv源)
* [直播源自制轮播源](#直播源自制轮播源)
* [互联网收集直播源](#互联网收集直播源)
* [直播源代理广播源](#直播源代理广播源)



---



## **直播源代理直播源**
直播源通过各种程序或项目代理的电视直播源。代理亦可理解为转发的含义，因部分公开的电视直播受限于固定的播放环境，通过代理即可重新定义直播源体现形式，将各种有验证的动态的链接固定为单一的静态链接，方便大家观看。


![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.06-brightgreen?style=for-the-badge)




### 直播源PHP代理

直播源通过PHP代码代理出的电视源，适用任何播放器，因全国运营商网络环境复杂，部分频道播放有可能卡顿，请自行筛选出最快的源使用。因为频道涵盖央视、卫视和各地市县频道，所以本M3U源文件未匹配和添加电视台台标LOGO，需要的可自行匹配添加！同时欢迎各位网友和电视机爱好者们提供台标，谢谢！

节目源当前频道数：139

> https://m3u.52sf.ga/JMSTV-PHP.m3u
> 

### 更新日志
> **2022.09.06**：剔除失效代理和慢速代理，已涵盖TVB无线新闻、Now新闻系列频道，央视、卫视以及运营商付费数字频道。
> 
> **2022.07.31**：新增一组咪咕代理源。
> 
> 


---



## **直播源代理直播平台源**

直播源基于Golang语言做的一套国内知名直播平台代理系统，实现重定向访问虎牙、斗鱼、Bilibili直播间M3U8/FLV直播流，将直播平台动态源转换为静态链接，方便在各种终端平台的播放器中直接播放。更多直播平台将陆续添加。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.06-brightgreen?style=for-the-badge)

### 使用教程

直播源表现格式：

> 主：https://live.52sf.ga/平台/ID
> 
> 备：https://liveb.52sf.ga/平台/ID
>   * 虎牙=huya；斗鱼=douyu；B站=bilibili

完整直播源举例：

> 主：https://live.52sf.ga/bilibili/10375360
> 
> 备：https://liveb.52sf.ga/bilibili/10375360
>   * 如果主播下播将无法观看哦~

### 更新日志
> **2022.09.06**：修复备份直播代理服务器。
> 
> 
---



## **直播源代理youtube源**

直播源基于PHP语言做的一套Youtube代理(解析)系统，实现重定向访问Youtube直播流无需挂代理，可直接在各种终端平台的播放器中直接播放，较之前的Youtube代理更具灵活性和稳定性。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.06-brightgreen?style=for-the-badge)

### 使用教程

> ~~https://php.52sf.ga/@Curly_MouseIPTV-YTB.php?id=youtubeID&P=分辨率~~
>  已下架，敬请期待替代代理方案！

使用示例：
> Youtube链接：https://www.youtube.com/watch?v=LbS-xQ67fos
> 
> 分辨率：720P=720  1080P=1080
> 
> ~~https://php.52sf.ga/@Curly_MouseIPTV-YTB.php?id=watch?v=LbS-xQ67fos&P=1080~~
> 
### 更新日志
> **2022.09.06**：因用户反馈部分频道无法播放，经检测发现此代理方式对播放器兼容性不是很友好，暂时下架。
> 
> **2022.09.06**：更换代理方式，更自由灵活，用户可自定义制作自己的Youtube代理频道。
> 
>
> 


---


## **直播源代理4GTV源**

直播源基于开源Python程序提供台湾4GTV电视频道节目源，可直接在各种终端平台的播放器中直接播放，目前收录120个频道。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.15-brightgreen?style=for-the-badge)

### M3U文件

> https://m3u.52sf.ga/JMSTV-4G.m3u
> 

### 更新日志
> **2022.09.15**：切换API接口，修复无法播放的错误。
> 

> **2022.09.06**：上线4GTV台湾电视频道节目源，当前收录频道数：120
> 


---

## **直播源自制轮播源**
直播源基于Golang语言做的一套自推流轮播系统，可对接全球知名直播平台，也可单独推出轮播节目源。

---



## **互联网收集直播源**
直播源从互联网以及群友分享的节目源中检测整理的节目源，精简好用。但大街源失效迅速，维护不易，且用且珍惜。


![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.06-brightgreen?style=for-the-badge)

### M3U文件

> https://m3u.52sf.ga/JMSTV-JSYD.m3u
> 
> https://m3u.52sf.ga/JMSTV-HNYD.m3u
> 

### 更新日志
> **2022.09.06**：上线江苏移动大街源、湖南移动大街源、大街源失效不补，随缘更新。
> 

---

## **直播源代理广播源**
直播源通过PHP代码代理出的广播源，目前支持蜻蜓FM、喜马拉雅FM、云听FM中所有广播频道，适用任何播放器。三家各有优势，同时频道可能会重复，请按需选用，方便喜欢收听广播又不想安装手机软件的听友们。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.06-brightgreen?style=for-the-badge)




### 使用教程

> 随机收听蜻蜓FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMQT.php?id=rand
> 
> 获取地区分类蜻蜓FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMQT.php?id=rand&type=蜻蜓FM分类ID
> 
> 蜻蜓FM分类ID
> 
> 407=网络台   217=广东   3=北京
> 433=咨询台   139=江西   5=天津
> 442=音乐台   151=山东   7=河北
> 429=交通台   19=山西    83=上海
> 439=经济台   202=湖南   257=重庆
> 432=文艺台   187=湖北   169=河南
> 441=都市台   254=海南   85=江苏
> 430=体育台   59=吉林    281=贵州
> 431=双语台   69=黑龙江  44=辽宁
> 440=综合台   316=陕西   259=四川
> 438=生活台   31=内蒙古  99=浙江
> 435=旅游台   239=广西   351=宁夏
> 436=曲艺台   291=云南   129=福建
> 434=方言台   11=安徽    327=甘肃
> 357=新疆     342=青海   308=西藏
> 
> 随机收听云听FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMYT.php?id=&type=
> 
> 获取地区分类云听FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMYT.php?id=list&type=云听FM分类ID
> 
> 云听FM分类ID
> 
> china=中国        shandong=7山东
> beijing=北京      shanxi_1=山西
> hebei=河北        hunan=湖南
> shanghai=上海     hubei=湖北
> chongqing=重庆    hainan=海南
> henan=河南        jilin=吉林
> jiangsu=江苏      heilongjiang=黑龙江
> guizhou=贵州      shanxi_2=陕西
> liaoning=辽宁     neimenggu=内蒙古
> sichuan=四川      guangxi=广西
> zhejiang=浙江     yunnan=云南
> ningxia=宁夏      anhui=安徽
> fujian=福建       qinghai=青海
> gansu=甘肃        xinjiang=新疆
> guangdong=广东    xizang=西藏
> jiangxi=江西      xinjiangbingtuan=新疆兵团
> 
> 随机收听喜马拉雅FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMXMLY.php?id=rand

> 获取喜马拉雅全部FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMXMLY.php?id=list
> 
### 更新日志
> **2022.09.06**：新增加广播节目，云听、蜻蜓FM、喜马拉雅FM。
> 



---

## 鸣谢

感谢  [google](https://google.com/) 提供搜索服务！
感谢  [JMS](https://jmstv.github.io//) 的GitHub模板！

