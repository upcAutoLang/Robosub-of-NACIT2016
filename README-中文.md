该仓库中内容是NACIT于2016年7月25—31日于美国圣地亚哥举行的Robosub竞赛的策略总控与图像处理源代码。
本团队获得了全部48支队伍中的第11名，笔者是当时的策略总控与图像处理负责人。笔者自知功力浅薄，有待学习之处甚多，此时已经距离16年比赛时间甚远，所以此处提供当时的源码，供各路大神批评指正。
参考地址：http://robonation.org/sites/default/files/RoboSub2016%20Summary%20Scores%20and%20Rankings.pdf

# 文件说明
- Final Control & ImageProcessing Programs of NACIT2016：策略总控与图像处理源代码
	- Source Code：源代码
		- AUVAutoControl：策略控制程序源码（基于Qt5）
		- VisionClass：视觉系统源码（基于C++与OpenCV 2.4.9）
		- CustomizeFuntions：笔者自定义函数集
			- CustomizeStructs：自定义结构体
			- GeneralImageProcess：通用图像处理函数
			- SpecialImageProcess：针对比赛图像任务的图像处理函数
			- SupportFunctions：其他支持函数
		- ThirdParty：第三方库，此处包括传感器的SDK与OpenCV库文件
		- XML Save Path：将实验数据以XML文档形式存储，并在程序中读取
	- 调试小程序：当时为了方便图像调试而自己编写的调试程序（基于Qt5，所以环境变量中需要有Qt路径）
- Control Program Introduction of NACIT2016.docx：系统性的介绍策略总控系统
- ImageProcess Program Introduction of NACIT2016.docx：系统性的介绍视觉系统
