### Boomcloud加速 使用教程 —— Mac OS
- - -
#### macOS平台使用方法一（推荐新手）
##### 1.下载BoomCloud for Mac客户端
下载地址1:[BoomCloud Wiki Center 全平台客户端下载地址](https://wiki.boomssr.com/xia-zai-di-zhi.html)  

下载地址2:[BoomCloud 用户中心   客户端下载菜单下](https://www.boomssr.com/downloads.php)
##### 2.安装客户端并登陆
将下载好的客户端压缩包解压，然后安装，安装成功后双击加速器图标启动程序并登录BoomCloud门户账号，即您的邮箱及密码。
· 登录 Boomcloud 账户自动获取接入点信息  
· 自动获取套餐到期时间以及流量使用剩余信息  
· 适应多套餐用户，可自由自主切换套餐无需登录面板   
· 以 shadowsocksr-NG 方式运行
##### 3.开始科学上网
登录之后软件会自动选择默认线路，如无法正常上网，您可以尝试切换线路

#### 方法二.
##### 1. 下载软件
登录用户中心，在"[资源下载](https://www.boomssr.com/downloads.php)" 区域，找到 ShadowsocksR for macOS。点击下载软件。解压安装包，将 ShadowsocksR-NG 拖入应用程序文件夹。
##### 2. 使用桌面版浏览器，进入用户中心，获取配置文件
登录用户中心，在"您订购的产品" 区域，找到 Boomcloud 加速服务。点击进入产品详情页面。

![](/assets/howtouse/surge-use1.png)

使用桌面版浏览器（Chrome 等），选择任意节点，点击 “自动配置” 区域中，Windows 配置右侧的“SSR 配置文件” 按钮，即可获取包含 Relay 服务所有信息的配置文件。此配置文件非常关键，请勿泄露，以免 云加速 服务被其他人盗用。

![](/assets/howtouse/ssr-win-2.png)

##### 3. 为 macOS 设备开启 云加速 服务
双击ShadowsocksR 程序图标，打开软件。点击桌面上方状态栏中飞机图标——服务器——导入服务器配置文件。找到下载好的 “gui-config.json" ，点击选取后，确认即可。选择任意线路，即可开启 加速 服务。
PAC 模式：自动代理模式，仅需要代理的流量通过 Relay 服务器。
全局代理模式： 所有流量通过服务器。

![](/assets/howtouse/ssr-mac-1.png)
![](/assets/howtouse/ssr-mac-2.png)
![](/assets/howtouse/ssr-mac-3.png)

- - -
注意事项：  
1. 个人专属配置文件是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。   
2. 如果节点有更新，则需要再次导入配置文件进行更新。  
3. ShadowsocksX如果出现BUG请联系软件作者，BoomCloud无法解决客户端层面问题。  