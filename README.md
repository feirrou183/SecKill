

# 软件介绍

Seckill是一款使用Python和pyqt编写，利用selenium库实现的自动化抢单软件，它界面友好，使用方便，可以帮助你在购物时快人一步，及时秒杀到自己想要的商品。

<img src="https://raw.githubusercontent.com/distiny-cool/SecKill/main/manual/img/show.png" alt="qiang">

# 源码配置

Python 3.7.9
PyQt5
Chrome 	100.0.4896.60

windows配置方法：
pip install pyqt5	#pyqt5的界面
pip install selenium	#核心包，用于自动化chrome
pip install qrainbowstyle  #这个包用来更改界面配置

python3 main.py

## 常见的问题与调试

我的系统chrome版本是100.0.4896.60，使用默认的chromedriver可能会和你的版本不同
你可以选择下载100.0.4896.60的chrome浏览器
也可以将主目录中的chromedriver.exe更换为你的chrome对应的版本，这里建议你使用后一种方法，chromedriver下载地址为：http://chromedriver.storage.googleapis.com/index.html

## 建议和期待

欢迎大家对本软件fork进行改进，如果觉得不错可以给个**stars**✨或者关注一下[**作者**](https://github.com/distiny-cool)
在尝试使用pyinstaller发布本软件exe版本时，出现了一些bug，例如外部库和图片资源不能成功导入等，所以暂时没有发布exe版本，大家可以尝试一下，期待你的改进！

# 使用说明

#### 第一步 选择购物平台

目前我们支持的购物平台包括淘宝和京东

#### 第二步 输入商品链接

在淘宝或京东的网页端找到你要购买的商品页，例如https://item.jd.com/100014219124.html

#### 第三步 选择购物方式

###### 方式1：马上抢购

点击图标<img src="https://raw.githubusercontent.com/distiny-cool/SecKill/main/icons/taobao.png" alt="qiang" style="zoom:10%;" />后，左侧的自动化网页即会跳转到淘宝/京东登录页面，使用手机扫码登录，登陆成功后网页会自动跳转至对应商品界面，选择要购买的商品类型和商品数量，等待秒杀活动开始时，软件会自动在活动开始时0.01秒内进行秒杀，之后会自动提交订单并跳转至付款界面，提示您抢购成功。

###### 方式2：定时抢购

点击图标<img src="https://raw.githubusercontent.com/distiny-cool/SecKill/main/icons/jdong.png" alt="later" style="zoom:10%;" />后，会弹出设置抢单时间页面，设置成功后，左侧的自动化网页即会跳转到淘宝/京东登录页面，使用手机扫码登录，登陆成功后网页会自动跳转至对应商品界面，选择要购买的商品类型和商品数量，之后软件会在设定的时间开始自动进行抢单。


# 关于

请注意：连续长时间多次使用本软件抢单可能会被购物平台列为敏感用户。

本软件是 Distiny 在应用软件设计课程的小作业，抢单功能及代码逻辑仅供个人使用和学习，请勿滥用。

欢迎对本软件的设计和改进提出建议！

