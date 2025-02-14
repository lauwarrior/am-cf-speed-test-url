# [am-cf-speed-test-url](https://github.com/ansoncloud8/am-cf-speed-test-url)

#
▶️ **新人[YouTube](https://youtube.com/@am_clubs?sub_confirmation=1)** 需要您的支持，请务必帮我**点赞**、**关注**、**打开小铃铛**，***十分感谢！！！*** ✅
</br>🎁请 **follow** 我的[GitHub](https://github.com/amclubs)、给我所有项目一个 **Star** 星星（拜托了）！你的支持是我不断前进的动力！ 💖
</br>✅**解锁更多技能** [加入TG群【am_clubs】](https://t.me/am_clubs)、[YouTube频道【@am_clubs】](https://youtube.com/@am_clubs?sub_confirmation=1)、[【博客(国内)】](https://amclubss.com)、[【博客(国际)】](https://amclubs.blogspot.com) 
</br>✅点击观看教程[CLoudflare免费节点](https://www.youtube.com/playlist?list=PLGVQi7TjHKXbrY0Pk8gm3T7m8MZ-InquF) | [VPS搭建节点](https://www.youtube.com/playlist?list=PLGVQi7TjHKXaVlrHP9Du61CaEThYCQaiY) | [获取免费域名](https://www.youtube.com/playlist?list=PLGVQi7TjHKXZGODTvB8DEervrmHANQ1AR) | [免费VPN](https://www.youtube.com/playlist?list=PLGVQi7TjHKXY7V2JF-ShRSVwGANlZULdk) | [IPTV源](https://www.youtube.com/playlist?list=PLGVQi7TjHKXbkozDYVsDRJhbnNaEOC76w) | [Mac和Win工具](https://www.youtube.com/playlist?list=PLGVQi7TjHKXYBWu65yP8E08HxAu9LbCWm) | [AI分享](https://www.youtube.com/playlist?list=PLGVQi7TjHKXaodkM-mS-2Nwggwc5wRjqY)

## 一、项目简介

本项目是一个使用Cloudflare的Worker搭建SpeedTest测速地址的工程，主要代码在`worker.js`文件中。通过本项目，你可以很容易地在Cloudflare上搭建起自己的测速服务。

## 二、功能介绍

例如您的项目域名为 `speedtest.am.workers.dev`

1. **默认测速大小为200MB**：当未在路径中指定测速大小时，项目会默认进行200MB的测速。

- 200M   默认测试下载地址: `https://speedtest.am.workers.dev`
 

2. **自定义测速大小**：通过在路径中指定数字和单位（可选的单位包括 K，M，G），可以设定想要进行测速的数据大小，如“/500M”表示进行500MB的测速。

- 1024K  测试下载地址: `https://speedtest.am.workers.dev/1024k`
- 200M   测试下载地址: `https://speedtest.am.workers.dev/200m`
- 1G     测试下载地址: `https://speedtest.am.workers.dev/1g`

3. **推荐使用workers部署方案并绑定自定义域，即可同时具备 http/https 两种测速途径。**

## 三、使用指南

1. 克隆或下载本项目到你的本地设备。

2. 在Cloudflare的Worker中创建一个新的项目，并将`worker.js`文件中的代码复制粘贴到你的项目中。

3. 部署你的Worker项目。

现在，你可以访问你的Worker的URL，进行网速测试了。

## 四、注意事项

- 代码中的路径需要做适当修改，以反映你自己的Cloudflare Worker的URL。
- 当路径不符合预设的格式时，程序将返回400错误。

希望这个星级的项目能对你有所帮助，如果你喜欢或用到了本项目，希望能给我一个星级鼓励一下。

# 
<center>
<details><summary><strong> [点击展开] 赞赏支持 ~🧧</strong></summary>
*我非常感谢您的赞赏和支持，它们将极大地激励我继续创新，持续产生有价值的工作。*

- **USDT-TRC20:** `TWTxUyay6QJN3K4fs4kvJTT8Zfa2mWTwDD`
- **TRX-TRC20:** `TWTxUyay6QJN3K4fs4kvJTT8Zfa2mWTwDD`

<div align="center"> 
  <img src="https://github.com/user-attachments/assets/e6cdc42a-6374-4722-b833-601738f72196" width="200"></br> 
  TRC10/TRC20扫码支付 
</div> 
</details>
</center>

 #
 免责声明:
 - 1、该项目设计和开发仅供学习、研究和安全测试目的。请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
 - 2、使用本程序必循遵守部署服务器所在地区的法律、所在国家和用户所在国家的法律法规。对任何人或团体使用该项目时产生的任何后果由使用者承担。
 - 3、作者不对使用该项目可能引起的任何直接或间接损害负责。作者保留随时更新免责声明的权利，且不另行通知。
 

