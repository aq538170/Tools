注意事项：
	1.所有路径不带中文，最好也不要带空格
	2.插件最佳使用版本是 JMeter 3.1及以下
	3.插件需要JDK支持，所以服务器端也要安装JDK


操作说明：
	1.解压JMeterPlugins-Standard-1.4.0.zip文件
	2.把解压文件里的 JMeterPlugins-Standard.jar 包放在JMeter安装目录下的 \lib\ext\

	3.解压ServerAgent-2.2.1.zip文件
	4.把解压得到的 ServerAgent-2.2.1 整个文件夹复制到服务器任意路径，
		Window运行startAgent.bat，
		Linux运行startAgent.sh；

	5.在JMeter运行界面添加监听器，选择jp@gc - PerfMon Metrics Collector 
		点击Add Row
		Host/IP 输入要监控的服务器的IP，
		Port 默认是4444(一般需要修改，如何修改自己百度)，
		Metric to collect 可选择监控的资源；

参考网址：
https://jmeter-plugins.org/wiki/Start/