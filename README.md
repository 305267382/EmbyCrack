# EmbyCrack
[English Version](https://github.com/YukiCoco/EmbyCrack/blob/master/README-EN.md)  
[Telegram Group](https://t.me/crackemby)


## 小广告
是否在为 Emby 无法刮削片子而烦恼？**Emby 国内加速破解版**加速所有刮削器访问下载，拒绝手动刮削，直接勾选 TheMovieDb、The Open Movie Database、TheTVDB 来刮削电影、剧集、动画，让海报布满你的 Emby，让刮削不再成问题！旨在为了提高中国用户的 Emby 使用体验。[了解一下](https://neko.re/archives/192.html "Emby 国内加速破解版效果展示")  

## Feature
+ 破解 Emby 高级版验证
+ 修改了默认插件源，加速中国用户下载插件
+ docker 一键安装

## Usage

### 服务端
部分用户反馈群晖套件版替换后打不开，请使用 docker 版  
详细使用方法移步[这里](https://neko.re/archives/128.html)
#### 手动替换
+ **注意**：如果以前使用其他破解方案，必须将系统的 hosts 的 `mb3admin.com` `www.mb3admin.com` 条目删除，否则破解不会生效
+ 将 [破解程序集](https://github.com/YukiCoco/EmbyCrack/tree/master/assembly) 替换原有文件即完成破解，原有文件路径为 `system/System.Net.Http.dll`

#### 使用 Docker
+ `yukinococo/emby_crack:unix-x64`（Unix）
+ `yukinococo/emby_crack:windows-x64` （Windows）

### 客户端
+ 浏览器：安装 [URLRedirector]() 插件，将 `https://mb3admin.com` 替换为 `http://crackemby.neko.re`
+ Android & Android TV：直接使用破解版，自己找找就有了
- IOS：[破解教程](https://neko.re/archives/208.html "破解教程")
