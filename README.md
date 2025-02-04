下载请点旁边的 Releases—>棱光PDF

因wps的会员很烦，心血来潮，自己用deepseek写了一个pdf工具箱，用的是python计算机语言，用**PDF24**的话导出的pdf不支持中文水印（会乱码，只保留英文，原因就是不能选自定义中文字体），这样师傅们在写自己原创文章的时候PDF的水印东西就可以用来引流了，非常实用！！

![image-20250203232525951](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502032325577.png)

那么我是怎么问的呢？

1、帮我写一个pdf批量去水印的工具，py项目，ui用pyqt5，界面要有科技感，并且呢按钮和输入框都要很帅，能体会科技公司的魅力，全部都中文

2、嗯，很好，在此基础上给我添加一个功能”PDF批量添加水印“，如果你感觉这个界面放不下，就新加一个主界面来链接，并且主界面是一个py文件（主界面一定要帅），每个大功能（PDF批量添加水印算一个大功能）是一个py文件，每个文件需要互相衔接，功能导航按钮在左边，右边显示功能，接下来的所有代码都要有扩展性，用于添加新的功能，告诉我操作的时候要易懂，不忽视每一个小细节

3、。。。。。。。。。。。。

emmmm并不是说给了你代码你就能写出来的，毕竟AI错误率是很高的，代码功底还是要有的

我的建议是第一步让它给出一个项目结构，也就是目录结构，分为什么什么文件，哪些文件夹有什么东西，然后你让它一个文件一个文件的给你输出，你只负责调试就ok，下面来介绍一下吧

## 功能列表

1、制作PDF单个水印文件

2、批量添加PDF水印

3、批量删除PDF水印

下面介绍一下本项目的使用方法，这是实现之后的效果图

![image-20250204113806462](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041138724.png)

首先是制作一个PDF水印文件

![image-20250203232525951](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502032325577.png)

需要选择你的字体文件（**必须支持中文的字体文件！**）

推荐一个字体网站：https://fontmeme.com/ziti

![image-20250204112123039](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041121337.png)

之后点击选择路径，添加水印文件名

![image-20250204112428463](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041124700.png)

设置好参数

![image-20250204112554164](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041125429.png)

之后在桌面打开，这样就生成成功了**模板**

![image-20250204112650956](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041126190.png)

有了水印模板，那么就可以批量添加水印了，这里选择水印PDF就是刚刚制作的水印PDF文件

![image-20250204113213911](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041132182.png)

一切正常（注意生成的目录不能和源需要加水印的PDF在同一个文件夹）

![image-20250204113452955](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041134240.png)

刚刚选择的第二个文件，非常的实用！！

![image-20250204113622383](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041136622.png)

尝试增加参数

![image-20250204113806462](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041138724.png)

接下来就是文件批量删除水印

![image-20250204114014065](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041140347.png)

一切清除正常，但是之前水印的地方内容不见了，缺点就是这个，目前市面上的工具也很少能直接去除关键字，这就是v1.0.0版本，后续还会添加新功能的（仅提供使用，如果需要源码还请联系我），欢迎关注

![image-20250204114234931](https://md-1312988675.cos.ap-nanjing.myqcloud.com/myImg/202502041142179.png)

完，感谢观看，如果师傅们有什么需求的话，欢迎在【泷羽Sec公众号】留言，后续会持续更新

## 往期推荐

[一分钟搭建本地大模型DeepSeek！永久免费！无需联网！一条命令即可搭建！！！！](https://mp.weixin.qq.com/s?__biz=Mzg2Nzk0NjA4Mg==&mid=2247498557&idx=1&sn=4be63db2842575769a912e8c3332c989&scene=21#wechat_redirect)

[一款集成了fofa、鹰图平台、360quake的信息收集工具 ](https://mp.weixin.qq.com/s?__biz=Mzg2Nzk0NjA4Mg==&mid=2247497974&idx=1&sn=2c6e91afcc8b898d403ad51730d4d2f5&scene=21#wechat_redirect)

[开箱即用！265种windows渗透工具合集--灵兔宝盒](https://mp.weixin.qq.com/s?__biz=Mzg2Nzk0NjA4Mg==&mid=2247492994&idx=1&sn=ca2ba6fe86b4172e3e6d3cbb3791c05f&scene=21#wechat_redirect)

[【渗透测试】DC1~9(全) Linux提权靶机渗透教程，干货w字解析，建议收藏](https://mp.weixin.qq.com/s?__biz=Mzg2Nzk0NjA4Mg==&mid=2247495774&idx=1&sn=ad20212bd08f94652d40e286406ed40f&scene=21#wechat_redirect)

[Viper一个互联网攻击面管理，红队模拟平台](https://mp.weixin.qq.com/s?__biz=Mzg2Nzk0NjA4Mg==&mid=2247497000&idx=1&sn=6b07a7a43b25ecc72f1cbd90a7fe477d&scene=21#wechat_redirect)

[一款在线的免杀平台](https://mp.weixin.qq.com/s?__biz=Mzg2Nzk0NjA4Mg==&mid=2247496274&idx=1&sn=78ee1bbc1b1e013e9db86d285b4a8d5e&scene=21#wechat_redirect)

[【oscp】稀有靶机-Readme](https://mp.weixin.qq.com/s?__biz=Mzg2Nzk0NjA4Mg==&mid=2247497745&idx=1&sn=953fa36ed8fd1e176e00e5c14b32b527&scene=21#wechat_redirect)
