# NETEASE_EDU_MFG_INTRO
网易教育产品部的介绍页面。（网易前端微专业大作业）

展示页面：http://cucluoting.github.io/NETEASE_EDU_MFG_INTRO/

具体功能要求如下：

1. 关闭顶部通知条
点击顶部通知条中的“X 不再提醒”后，刷新页面不再出现此通知条。

2. 关注“网易教育产品部”/登录

  (1)点击关注按钮：首先判断登录的cookie是否已设置

  (2)如果未设置登录cookie，则弹出登录框，使用给定的用户名和密码（需要表单验证）调用服务器Ajax登录，成功后设置登录cookie

  (3)登录成功后，调用关注API，并设置关注成功的cookie

  (4)登录后“关注”按钮变成不可点的“已关注”状态。

3. 顶部右侧导航及内容区各产品的“了解更多”
点击导航中的“网易公开课”，“网易云课堂”，“中国大学MOOC”，新窗口打开对目的页面，点击“了解更多>”的跳转链接及打开方式相同。

4. 轮播图
三张轮播图轮播效果：实现每5s切换图片，图片循环播放；鼠标悬停某张图片，则暂停切换；切换效果使用入场图片500ms淡入的方式。点击后新开窗口打开目的页面。

5. 左侧内容区tab切换
点击“产品设计”或“编程语言”tab，实现下方课程内容的更换。

6. 查看课程详情
鼠标悬停“产品设计”或“编程语言”tab下的任意课程卡片，出现浮层显示该课程的课程详情；鼠标离开课程详情浮层，则浮层关闭。

7. 右侧“机构介绍”中的视频介绍
点击“机构介绍”中的整块图片区域，调用浮层播放介绍视频。浮层中调用的播放器（不做浏览器兼容,可用html5）。

8. 右侧“热门推荐”
实现每次进入或刷新本页面，“热门推荐”模块中，接口返回20门课程数据，默认展示前10门课程，隔5秒更新一门课程，实现滚动更新热门课程的效果。
