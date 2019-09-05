# hktv

### hkgw 
根据海康官网可下载的web包实现的
只是web包是没有模块化的，这里加到了vue实现了模块化
jsencrypt用的npm安装的
jsWebControl-1.0.0.min.js 用的动态生成script的（用import报错）
jquery-1.12.4.min.js 倒是可以import进来
https://open.hikvision.com/docs/741bcdc108014f6980b0b49ab4c86e41

### hkno
这是没有用js插件，用的type='application/x-vlc-plugin'，实现的读取rtsp流
但是需要chrome44-45版本浏览器
并且浏览器上插件开启NPAPI
然后安装VLC media player软件（用作媒介，读取rtsp流）
