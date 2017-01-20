# DomobVideoSDK

####1．必要条件

* 1.使用Xcode 7或更高版本

* 2.运行环境为iOS 8.0或更高版本


####2．视频SDK的使用
* 1.获取Publisher ID,请从多盟官网（http://www.domob.cn) 的获取您的
Publisher ID。

* 2.可以跟据自己需求切换Publisher ID的测试、正式和暂停状态，测试状态只能请求到测试视频

* 3.将SDK添加到项目中

  * 1.将SDK包添加到您的项目中。建议直接将“IndependentVideo”文件夹添加到项目中。

  * 2.若要SDK正常工作，并添加一些依赖库(详见工程中的集成文档 SDKUserGuide.pdf) 
 
* 4.Build Settings中other link flags 选项添加-ObjC：
 
* 5.若要在应用中添加视频广告，只需要简单的几步：

	* 导入IndependentVideoManager.h 头文件。

	* 声明一个IndependentVideoManager的实例。

	* 实现IndependentVideoManagerDelegate。

	* 使用您从多盟官网获得的PublisherId来初始化IndependentVideoManager。

	* 设置IndependentVideoManager的代理。

####3．其他
* 具体API使用详见工程中的集成文档SDKUserGuide.pdf或者Wiki

* 更多接口信息，请参考SDK包中的头文件中包含的信息。

* 更详细的使用方法，请参考项目中的Sample程序和多盟官网（http://www.domob.cn)

* 如还有疑问，欢迎随时发邮件到support@domob.cn获得更多帮助。


##DOMOB iOS independent video sdk changelog

=================================
###3.5.2&emsp;&emsp;2017/01/13

1.bug fix

2.修改请求和下载逻辑,减少无用请求和下载

=================================
###3.5.0&emsp;&emsp;2016/11/26

1.bug fix

=================================
###3.4.0&emsp;&emsp;2016/11/18

1.bug fix

2.SDK适配https协议

=================================
###3.3.5&emsp;&emsp;2016/10/26

1.修改获取视频状态的逻辑

2.线程优化

=================================
###3.3.4&emsp;&emsp;2016/10/17

1.优化iOS10系统下获取idfa为0值时无视频的弹窗提示

=================================
###3.3.3&emsp;&emsp;2016/09/22

1.新增竖屏/倒竖屏游戏适配

2.bug fix 

=================================
###3.3.2&emsp;&emsp;2016/09/06

1.fix无网络状态播放视频的bug

=================================
###3.3.1&emsp;&emsp;2016/08/12

1.bug fix

=================================
###3.3.0&emsp;&emsp;2016/07/22

1.bug fix

2.点击关闭按钮跳转landingPage,landingPage的横竖屏适配

3.新增实时检测视频状态功能

_________________________________________

###3.2.0&emsp;&emsp;2016/06/15

1.去掉加载视图界面 

2.去掉非wifi下播放视频时让用户确认的提示框。

3.修改展示视频的业务逻辑

4.bug fix

_________________________________________

###3.1.1&emsp;&emsp;2016/06/05

1.bug fix
2.去掉获取用户location信息

_________________________________________

###3.1.0&emsp;&emsp;2016/01/19

1.加载界面视觉优化 

2.性能优化 

3.弹窗场景优化 

4.bug fix

_________________________________________

###3.0.0&emsp;&emsp;2015/12/29

1.预加载优化

2.增加播放器的静音功能 

3.弹窗样式更新 

4.弹窗文案优化 

5.bug fix

_________________________________________

###2.2.0&emsp;&emsp;2015/08/05

1.弹框样式改变 

2.播放完成后的弹框可控 

3.bug fix

_________________________________________

###2.1.0&emsp;&emsp;2015/04/13

1.预加载优化

2.转化率提升优化

3.bug fix

_________________________________________


###2.0.0&emsp;&emsp;2015/02/05


1.模板优化
_________________________________________


###1.3.2&emsp;&emsp;2015/01/19


1.增加视频完成播放的回调
_________________________________________


###1.3.1&emsp;&emsp;2015/01/09


1.bug fix
_________________________________________


###1.3.0&emsp;&emsp;2014/12/03


1.更新SDK使用接口
_________________________________________


###1.2.3


1.成功获取积分回调接口中添加本次视频获得的积分数
_________________________________________


###1.2.2


1.bug fix
_________________________________________


###1.2.1


1.修复在iOS8上的兼容性问题
_________________________________________


###1.2.0
1.增加iai支持
_________________________________________


###1.1.0


1.添加检测是否有可以播放的视频广告接口 
2.修复loading过长问题
_________________________________________


###1.0.0&emsp;&emsp;2014

原始版本

--------------------------
