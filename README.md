# android_cpu
功能：获取android设备当前app的实时cpu占比，共执行n分钟，n为入参；环境：python3，adb；运行方法：打开要检验的app，连接adb，执行parse_cpu.py文件即可

结果是将脚本获取的数值以折线图的方式存放在report文件下，名称为本地实时时间
结果数值是百分比，但是设备cpu全量并不一定是100%，举例来说，我手机是vivo iqoo，是一个八核手机，那么我手机cpu总值就是800%。

作者联系方式：
qq：1004302821
