# YEEPlugin for Filemaker
## 插件开发背景
YEEPlugin是一个免费的Filemaker插件，作者将不断集成实用的功能。
目前已经集成了条码、二维码、win和mac的系统级通知与容器图片旋转和裁剪的功能。
二维码在国内的应用非常广泛，可惜 FileMaker 没有内置的二维码生成函数。如果要在 FileMaker 中生成二维码，需要通过 WebViewer 或脚本发送带有内容参数的 URL API，从服务器获取二维码数据。不过，这种方式速度较慢、需要网络连接，且打印时容易模糊。所以，插件成了在 FileMaker 中离线生成二维码及其它条码的最优选择。

## 插件使用  
1. 在首选项 -> 插件 -> 显示插件文件夹，将对应平台的插件文件放置在Extension文件夹中

* Yee.fmplugin-Mac.zip		Mac  需要解压
* YEEPlugin.fmx		Win 32位  Windows 32版本已停止更新，仅有二维码和条码功能。
* YEEPlugin.fmx64		Win 64位  

2. 完全退出Filemaker程序  
3. 打开YEEPlugin-Demo.fmp12 这个测试文件，见脚本实现即可。

该插件可应用于单机部署，同时支持服务器部署（可实现部署Server的情况下，然后使用服务器执行脚本，让FM Go生成二维码）。

已测试过的平台：
Filemaker Pro/Advance 15、 16、 17 在 mac osx 10.12， 10.13, windows 7, windows 10 x86 与 x64平台。
Filemaker Server 15、 16 在 windows Server 2012 R2

#### 同时为了使二维码插件更符合国内用户的使用习惯，欢迎 Bug 反馈及功能建议，联系作者QQ：53345316。

# 更新
### 2019年4月10日更新
#### 增加了图片裁剪和旋转的功能。
### 2018年8月20日更新
#### 增加了Mac端的脚本步骤，可以发送mac的通知和回调脚本。
### 2018年7月30日更新
#### 增强了windows 10下面发送系统通知的功能，可通过按钮绑定回调脚本。
### 2018年7月3日更新
#### 增强了FM16以下的支持，不再需要下载Visual C++ Redistrubution库。
### 2018年6月24日更新
#### 增加了Code128条码生成函数。

<br>
<br>

## 打赏捐赠
### 本插件免费使用，无任何限制。做不定期更新，加入更多可选参数及定制个性化条码的功能。
### 若本插件为您创造商业价值，请考虑捐助。作者将继续努力开发，感谢您的支持。

#### 微信
<p align="left">
  <img src="https://github.com/OrcaData/FMQRCode/raw/master/wechatpay.png" width="25%" height="25%" />
</p>
