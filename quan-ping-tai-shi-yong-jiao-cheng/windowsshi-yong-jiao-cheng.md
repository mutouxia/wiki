### Boomcloud加速 使用教程 —— Windows
- - -
### Windows平台使用方法一（推荐新手）
#### 1.登录BoomCloud门户
建议使用Chrome浏览器登录，以获得最佳体验
#### 2.转到用户中心-客户端下载菜单
客户端下载在用户中心面板的右侧
#### 3.下载Boomcloud Client for WIndows客户端
· 登录 Boomcloud 账户自动获取接入点信息  
· 自动获取套餐到期时间以及流量使用剩余信息  
· 适应多套餐用户，可自由自主切换套餐无需登录面板   
· 以 shadowsocksr 方式运行
#### 4.安装软件，打开之后登录账号
账号即使BoomCloud门户的注册邮箱，密码即您的账号密码
#### 5.登录之后即可开始科学上网
登录之后软件会自动选择默认线路，如无法正常上网，您可以尝试切换线路


### Windows平台使用方法二(推荐专业)
#### 1. 使用桌面浏览器登录到 Boom Cloud 管理门户
建议使用Chrome浏览器，访问 Boom Cloud 管理门户

![](/assets/win/0.png)

在"[资源下载](https://www.boomssr.com/downloads.php)" 区域，找到 ShadowsocksR for macOS。点击下载软件。

![](/assets/win/2.png)

#### 2. 导入 Boom Cloud 接入点信息
下载后使用 7-zip 软件或其他解压缩软件对压缩包进行解压，应当会得到这些文件

![](/assets/win/3.png)

返回到 Boom Cloud 管理门户，在页面顶部可以发现 [ 自动配置 ] 功能区，点击 Windows 配置的 “SSR 配置” 以下载一键配置文件  

![](/assets/win/5.png)

你的浏览器应当会下载一个名为`gui-config.json` 的文件。如果没有开始下载，建议更换为其他现代浏览器（推荐 Google Chrome） 

![](/assets/win/6.png)  

将该文件放到之前 ShadowsocksR 客户端的目录中，并双击ShadowsocksR图标启动

![](/assets/win/7.png)

#### 3. 配置系统代理
祝贺！你现在已经完成了所有客户端配置，但是想要使用 Boom Cloud 加速网络，还需要打开系统代理。
请右键点击托盘栏的纸飞机图标，在系统代理模式中选择 [ PAC 模式 ] 或 [ 全局模式 ]

![](/assets/win/10.png)

然后选择PAC 更新下GFWlist。

![](/assets/win/8.png)

```
  A、更新PAC为绕过大陆常见域名列表：绕过大陆基本网站；
  B、更新PAC为绕过大陆IP：所有国外网站使用代理，在路由器上配置SS后NAS的BT下载也会使用代理，谨慎使用；
  D、更新PAC为GFW List：GFW List中列表网站，推荐。
```
- - -
注意事项：  
1. 个人专属配置文件是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。  
2. 如果节点有更新，则需要再次导入配置文件进行更新。  
3. ShadowsocksX如果出现BUG请联系软件作者，BoomCloud无法解决客户端层面问题。