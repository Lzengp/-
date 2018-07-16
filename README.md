# WeChat
微信公众号开发（Java）

### 备注：
* [NATAPP](https://natapp.cn/login)
 * natapp是用来内网穿透的，可以理解为在自己电脑上写的web项目通过内网穿透，别人的电脑也可以访问自己的项目，把localhost:8080换成natapp上生成的地址，注意，因为微信公众号只支持80和443端口，所以在申请免费隧道的时候记得选择web协议的端口，关闭natapp.exe就不能用这个地址了，这个只是测试用的，很好用的工具。
* [微信公众号](https://mp.weixin.qq.com)
 * 在MenuSetting中填写自己的appId，appSecret，然后在url填写自己natapp上的地址，形如 http://et6i45.natappfree.cc/WeChat/wechat ，wechat在xml里面配置指向WxServlet，Token要和WxServlet的一致。
 ### 其他
 如果你有云服务器，也可以把地址换成你的，这样就不担心关闭natapp就不能测试了。老师说这些代码不用了，别人都已经封装好了，所以没什么实际价值，只是用来玩一玩。
