# wechat-sdk
微信小程序授权登录

官方dome修改的，把官方坑踩掉了

坑一：[已解决]wx.request返回的json是字符串，并无法用JSON.parse，还会报错。

原因：官方的加密数据解密算法PHP - SDK里的三个文件有带BOM头，要去除

![Foo](https://mmbiz.qlogo.cn/mmbiz_png/LzqOsJaVibY8yegD8T1lJNAhuaXESC8P7hGBQW94xc4W5zOyID0rMBs599vrQAOdl4esBPdOmm54xPsM11exX2A/0?wx_fmt=png
)
