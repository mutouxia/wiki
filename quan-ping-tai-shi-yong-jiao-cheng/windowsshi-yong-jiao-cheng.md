### Boomcloud加速 使用教程 —— Windows
- - - - -
#### 1. 使用桌面浏览器登录到 Boom Cloud 管理门户
建议使用Chrome浏览器，访问 Boom Cloud 管理门户
![](/assets/map.svg)
在"资源下载" 区域，找到 ShadowsocksR for macOS。点击下载软件。
![](/assets/map.svg)
#### 2. 导入 Boom Cloud 接入点信息
下载后使用 7-zip 软件或其他解压缩软件对压缩包进行解压，应当会得到这些文件
![](/assets/map.svg)
返回到 Boom Cloud 管理门户，在页面顶部可以发现 [ 自动配置 ] 功能区，点击 Windows 配置的 “SSR 配置” 以下载一键配置文件
![](/assets/map.svg)
你的浏览器应当会下载一个名为```gui-config.json``` 的文件。如果没有开始下载，建议更换为其他现代浏览器（推荐 Google Chrome）
![](/assets/map.svg)
将该文件放到之前 ShadowsocksR 客户端的目录中，并双击ShadowsocksR图标启动
![](/assets/map.svg)
#### 3. 配置系统代理
祝贺！你现在已经完成了所有客户端配置，但是想要使用 Boom Cloud 加速网络，还需要打开系统代理。
请右键点击托盘栏的纸飞机图标，在系统代理模式中选择 [ PAC 模式 ] 或 [ 全局模式 ]
![](/assets/map.svg)
然后选择PAC 更新下GFWlist。
![](/assets/map.svg)
```
  A、更新PAC为绕过大陆常见域名列表：绕过大陆基本网站；
  B、更新PAC为绕过大陆IP：所有国外网站使用代理，在路由器上配置SS后NAS的BT下载也会使用代理，谨慎使用；
  D、更新PAC为GFW List：GFW List中列表网站，推荐。
```
- - - - --
注意事项：  
1. 个人专属配置文件是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。  
2. 如果节点有更新，则需要再次导入配置文件进行更新。  
3. ShadowsocksX如果出现BUG请联系软件作者，BoomCloud无法解决客户端层面问题。