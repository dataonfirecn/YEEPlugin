# YEEPlugin for Filemaker QRCode & Code128
## 插件开发背景  
二维码在国内的应用非常广泛，可惜 FileMaker 没有内置的二维码生成函数。如果要在 FileMaker 中生成二维码，需要通过 WebViewer 或脚本发送带有内容参数的 URL API，从服务器获取二维码数据。不过，这种方式速度较慢、需要网络连接，且打印时容易模糊。

所以，插件成了在 FileMaker 中离线生成二维码及其它条码的最优选择。

## 插件使用  
1. 在首选项 -> 插件 -> 显示插件文件夹，将对应平台的插件文件放置在Extension文件夹中

* Yee.fmplugin		Mac  
* YEEPlugin.fmx		Win 32位  
* YEEPlugin.fmx64		Win 64位  

2. 完全退出Filemaker程序  
3. 打开YEEPluginQrCode.fmp12 这个测试文件，见脚本实现即可。

该插件可应用于单机部署，同时支持服务器部署（可实现部署Server的情况下，然后使用服务器执行脚本，让FM Go生成二维码）。

## 本插件会做不定期更新，加入更多可选参数及定制个性化条码的功能。
### 同时为了使二维码插件更符合国内用户的使用习惯，非常欢迎大家提供 Bug 反馈及功能建议，联系方式QQ：53345316。

# 2018年6月24日更新
## 增加了Code128条码生成函数。
