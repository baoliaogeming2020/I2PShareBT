# 建立分享服务器 #  
## 1. 下载软件 ##  
[I2P官网](https://geti2p.net/en/download)，下载 i2pinstall_0.9.47_windows.exe / JRE / I2P-Profile-Installer-0.02b.exe  
i2pinstall_0.9.47：根据自己的操作系统下载。  
JRE：因软件是 Java 编写，所以需要环境才能运行。进入下载页面，会自动选择自己操作系统的版本，直接下载就可以了。  
I2P-Profile-Installer：这是 FireFox 的 I2P 版本，可以在这下载，也可以自己到官网下载。后边还有一步有下载链接。  
<img src="/img2/1-001.png" width="80%" height="80%">  
<img src="/img2/1-002.png" width="80%" height="80%">  
## 2. 安装软件 ##  
### 2.1. 安装JRE ###
基本不需要改设置，一路下一步就够了。  
<img src="/img2/2-001.png" width="40%" height="40%">  
<img src="/img2/2-002.png" width="40%" height="40%">  
<img src="/img2/2-003.png" width="40%" height="40%">  
<img src="/img2/2-004.png" width="40%" height="40%">  
### 2.2. 安装I2P ###  
<img src="/img2/3-001.png" width="40%" height="40%">  
<img src="/img2/3-002.png" width="40%" height="40%">  
<img src="/img2/3-003.png" width="40%" height="40%">  
<img src="/img2/3-004.png" width="40%" height="40%">  
<img src="/img2/3-005.png" width="40%" height="40%">  
<img src="/img2/3-006.png" width="40%" height="40%">  
<img src="/img2/3-007.png" width="40%" height="40%">  
<img src="/img2/3-008.png" width="40%" height="40%">  
<img src="/img2/3-009.png" width="40%" height="40%">  
<img src="/img2/3-010.png" width="40%" height="40%">  
<img src="/img2/3-011.png" width="40%" height="40%">  
### 2.3. 设置I2P ###   

在开始菜单启动后会在状态栏内出现一个小人图标。  
<img src="/img2/4-001.png" width="20%" height="20%">  
双击此图标，在浏览器打开I2P设置。  
<img src="/img2/4-002.png" width="80%" height="80%">  
<img src="/img2/4-003.png" width="80%" height="80%">  
<img src="/img2/4-004-1.png" width="80%" height="80%">  
<img src="/img2/4-004-2.png" width="80%" height="80%">  
<img src="/img2/4-005.png" width="80%" height="80%">  
此处也有一个 FireFox 下载链接。  
<img src="/img2/4-006.png" width="80%" height="80%">  
<img src="/img2/4-007.png" width="80%" height="80%">  
结束设置向导。进入 I2P 管理页面。  
点击 I2P 大图标，可以进入详细设置界面。  
<img src="/img2/4-008.png" width="80%" height="80%">  
当活动节点数量 > 10 时，说明连接节点数量足够，可以正常上网。  
点击 隐藏服务器管理 对 eepsite(I2P 网站服务器) 进行设置。  
<img src="/img2/4-009.png" width="80%" height="80%">  
启动网站服务。  
<img src="/img2/4-010.png" width="80%" height="80%">  
正在启动。等一会，手动刷新页面。  
<img src="/img2/4-011.png" width="80%" height="80%">  
已经正常启动。  
<img src="/img2/4-012.png" width="80%" height="80%">  
设置 FireFox 浏览器通过 I2P 代理上网。  
<img src="/img2/4-013.png" width="80%" height="80%">  
<img src="/img2/4-014.png" width="80%" height="80%">  
代理地址：127.0.0.1:4444。  
<img src="/img2/4-015.png" width="80%" height="80%">  
访问自己的 I2P 网站。  
<img src="/img2/4-016.png" width="80%" height="80%">  
这就是软件自带的网站界面。"...b32.i2p"就是你对外的域名。其实这个自带的主页是自动跳转到 help 目录。  
<img src="/img2/4-017.png" width="80%" height="80%">  
打开文件夹 "C:\ProgramData\Application Data\i2p\eepsite\"，备份 "eepPriv.dat" 文件，未来重装时把这个文件拷贝回来，你的域名保持不变，否则每次重装都会生成新的32位域名。  
<img src="/img2/5-001.png" width="80%" height="80%">  
做自己的主页，进入文件夹 "C:\ProgramData\Application Data\i2p\eepsite\docroot"，修改 "index.html" 文件。这就是你的对外主页。  
这里还有一个 "robot.txt" 这是为了谷歌 SEO 和 爬虫预留的文件。不用动，删除也行。  
<img src="/img2/5-002.png" width="80%" height="80%">  
下边会回到软件 BiglyBT，安装请参考 [JoinShare.md](JoinShare.md)。  
打开"我的共享"。  
<img src="/img2/6-001.png" width="80%" height="80%">  
向"我的共享"拖拽你要分享的文件。最好把所有要共享的文件放到一个文件夹内。这样好管理。  
<img src="/img2/6-002.png" width="80%" height="80%">  
<img src="/img2/6-003.png" width="80%" height="80%">  
给共享文件分类。  
<img src="/img2/6-004.png" width="80%" height="80%">  
<img src="/img2/6-005.png" width="80%" height="80%">  
<img src="/img2/6-006.png" width="80%" height="80%">  
进行 I2P匿名网络 分享。  
每一个文件都要选择"I2P匿名网络"。如果你对自己的安全无所谓，就选择"公共IP网络"，否则，去掉此选项，因为任何人都可以看到你的IP。  
<img src="/img2/6-007.png" width="80%" height="80%">  
<img src="/img2/6-008.png" width="80%" height="80%">  
当分享的文件太多时，会出现排队，最好"强制做种"才能让所有文件不排队。  
<img src="/img2/6-009.png" width="80%" height="80%">  
对此分类创建 RSS。  
<img src="/img2/6-010.png" width="80%" height="80%">  
启用 RSS。
<img src="/img2/6-011.png" width="80%" height="80%">  
<img src="/img2/6-012.png" width="80%" height="80%">  
访问刚创建的 RSS。  
<img src="/img2/7-001.png" width="80%" height="80%">  
<img src="/img2/7-002.png" width="80%" height="80%">  
<img src="/img2/7-003.png" width="80%" height="80%">  
将文件存在 "C:\ProgramData\Application Data\i2p\eepsite\docroot" 文件夹。  
<img src="/img2/7-004.png" width="80%" height="80%">  
到此，你的共享 和 订阅已经完成，将 "...b32.i2p/miles.xml" 分享给战友，战友通过参考 "JoinShare.md" 就可以订阅下载你的文件。
