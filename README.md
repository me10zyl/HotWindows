##HotWindows是什么？
一个增强窗口切换效率的脚本。

##HotWindows有那些功能？
* 热激活功能根据窗口标题名称的字母索引快速的激活窗口
* 热启动功能为程序创建热键`一键`启动/激活/隐藏
* 自定义热键对窗口最大化/最小化/剧中显示

##HotWindows如何使用？

###热激活功能
开启脚本后等待托盘区提示准备完成，<br>![](https://github.com/liumenggit/pic/raw/master/HotWindowszbwc.gif)<br>功能为利用窗口标题字母索引窗口，例如激活AutoHotkey高级群窗口，则按住空格在点击GJQ（高级群的首拼）会出现TrayTip提示一个列表，<br>![](https://github.com/liumenggit/pic/raw/master/HotWindowsgjq.gif)<br>现在松开空格键即可激活高级群窗口，如果没有列表说明没有相似名字的窗口，如果列表中有多条则依照数字按下数字激活响应的窗口，如果所需激活的窗口为头条则松开空格后即可激活。

###热启动功能
在想要定义热启动功能的程序窗口，按住Tab单击需要创建的热激活热键。例如为Photoshop软件创建热启动。<br>![](https://github.com/liumenggit/pic/raw/master/HotWindowsps.gif)<br>在Photoshop程序窗口按住Tab并单击P键，则可为Photoshop程序创建热启动。<br>![](https://github.com/liumenggit/pic/raw/master/HotWindowspsp.gif)<br>程序提示创建热键成功，此时Photoshop程序已经缩小到托盘图标再次按住Tab并单击P则可激活窗口，在程序界面再次按下Tab单击P则删除此热键。

##GIF演示
![](https://github.com/liumenggit/pic/raw/master/HotWindows.gif)

##最新制作意向
优先选择功能，对于常激活窗口进行靠前排列。

##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流
* 邮件(admin#xueahk.com, 把#换成@)
* QQ:4845514

##捐赠开发者
在兴趣的驱动下,写一个`免费`的东西，有欣喜，也还有汗水，希望你喜欢我的作品，同时也能支持一下。 当然，有钱捧个钱场，没钱捧个人场，谢谢各位。<br>
![](https://github.com/liumenggit/pic/raw/master/alipayhotwin12.png)

##更新历史
* 201706
	* 添加-激活程序视图可选性TrayTip/ListView
	* 添加-输入保护防止输入中意外激活窗口
	* 优化-代码结构
* 201705
	* 增强-脚本启动速度
	* 修正-删除热启动为在所需删除的程序窗口再次按下设置的热键即可删除
	* 修正-保存设置BUG
	* 修正-执行热键的时候不会乱输出热键
	* 修正-保存设置无效问题
* 201704
	* 新增-提示用户修改注册表实现气泡提示
	* 修正-GUI界面信息错误
	* 修正-检查更新前检查网络是否链接
	* 修正-开机启动读取INI信息失败
* 201703
	* 更改-主要功能热键可更改
	* 添加-更新功能并记录用户数
