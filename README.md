# srs-win32
Simple-Rtmp-Server 的windows编译版  
基于cygwin的st-1.9  
用于在windows平台快速部署本地开发测试环境的另一个选择，双击运行run.bat即可  

另外一个比较成熟的windows平台测试环境是由本人提交补丁并首先成功移植到windows平台的https://github.com/illuspas/nginx-rtmp-win32  

但srs在Linux环境中性能更强，功能更多，尤其是2.0后支持的rtmp转http-flv是目前流媒体运营中非常流行的方案，具有RTMP的低延迟,HTTP的稳定.被各大商用直播App采用。  
当前为srs项目develop分支最后一次提交的版本3.0.6  
默认配置srs.conf里开启了http-flv,hls，更多配置参数请看full.conf

此项目方便windows平台开发者快速配置开发环境，不建议做运营服务器。

欢迎使用NodeMediaClient SDK 来开发直播流媒体App，真正秒开RTMP、HTTP-FLV,GPU算法加速美颜直播。  
 * iOS: https://github.com/NodeMedia/NodeMediaClient-iOS
 * Android: https://github.com/NodeMedia/NodeMediaClient-Android  
 

