# Saas桌面端使用手册

本文描述互动课堂SaaS组件使用方式，可以依照[官方文档](https://cloud.tencent.com/document/product/680/34356)的开通互动课堂

## 一、如何加入课堂

### 1. 下载Saas客户端


- Mac:    http://dldir1.qq.com/hudongzhibo/Saas/TClass_Saas.dmg
- Win:    http://dldir1.qq.com/hudongzhibo/Saas/TClass_Setup_Saas.exe

### 2. 加入课堂

> 如果您使用的是demo，加入课堂界面会和互动课堂SaaS组件正式版有所区别，[查看详细信息](./Demo%E4%BD%93%E9%AA%8C%E6%89%8B%E5%86%8C.md)

加入课堂的方式有两种：

#### 2.1 方式1 通过管理员分享的上课链接地址打开

点击管理员分享的上课链接地址，会看到下面的界面

![](https://main.qcloudimg.com/raw/c731c52ec6d348dcda829b319d2cd21f.png)

此种方式加入课堂需要输入【用户ID】、【用户密码】两个要素：

要素 | 说明
--------- | ---------
用户 ID | 由管理员告知。登录App的账号，一般不会变化。
用户 密码 | 由管理员告知。登录App的密码，一般不会变化。

> 仅支持Chrome浏览器，暂时不支持IE或Safari(近期将支持IE和Safari)


#### 2.2 方法2 点击安装好的应用图标

点击安装好的应用图标打开 App，界面展示如下：
![](https://main.qcloudimg.com/raw/49bb925a1cf8c37c15e2e56982ffb4ed.png)

此种方加入课堂需要输入【机构ID】、【课堂ID】、【用户ID】、【用户密码】四个要素：

要素 | 说明
--------- | ---------
机构ID | 由管理员告知。腾讯云互动课堂分配的公司编号。
课堂ID | 由管理员告知。约好的课程编号。
用户ID | 由管理员告知。登录App的账号，一般不会变化。
用户密码 | 由管理员告知。登录App的密码，一般不会变化。

> 其中，`机构 ID` 只需要第一次使用时输入，表示绑定哪个教育机构，之后再次打开 App，会默认使用第一次输入的值（除非删除 App 重新安装）

然后点击加入课堂即可进入【课堂ID】对应的课堂中，如果某一个要素输出错误，则会弹出提示框，请根据提示框进行操作。


## 二、老师如何进行备课

互动课堂客户端目前支持在上课过程中使用PPT、PDF、DOC、MP4和图片作为课件。
MP4和图片需要放在本机。在课中直接打开播放给学生看。
而PPT、PDF、DOC文件建议是在通过控制台上传。

这里上传文件有两种方式:

### 通过控制台上传
这里可以直接将文件发给管理员。由管理员通过控制台上传并绑定到老师名下(参考管理员文档)。老师可以在课件管理页的私人课件tab找到它。

### 老师在加入课堂后台上传
- 第一步 加入课堂，打开课件管理页

![](https://main.qcloudimg.com/raw/5524819f50c81ffd374325e5d6930277.png)

可通过标题栏中的课件管理(c)管理菜单进入课件管理页

- 第二步 点击上传课件

选择私人课件或者公共课件tab。
公共课件中的文件所有老师都可以使用。私人课件只能由课件所有者使用。
通过课件管理页中的上传课件打开课件上传对话框：

![](https://main.qcloudimg.com/raw/ac993bebe7dfbe8c58af170da6c20e67.png)

- 第三步  选择需要上传的课件

点击课件上传后会弹出文件选择对话框，在这里选择需要上传的课件，支持PPT,PPTX,DOC,DOCX,PDF格式。

- 第四步  测试课件

课件上传完毕后，当课件管理页里该课件的状态显示为完成后，课件就可以使用了。
点击状态是已经完成的课件栏，将在内容区域加载这个课件。
内容区域支持同时显示多个课件，并对每个课件进行单独的拖动、调整大小、缩放、使用白板进行标注。


## 三、老师如何使用客户端上课
使用Saas客户端可以使用音视频、IM聊天、白板、文档课件、播放视频等功能

### 1、如何开始上课

老师可以提前一个小时进入课堂进行备课，和学生互动。
在老师准备就绪，可通过点击标题栏中的上课(g)开始正式开始上课。

![](https://main.qcloudimg.com/raw/5524819f50c81ffd374325e5d6930277.png)

在课堂结束时，还是点击这个按钮进行下课

完整的上课流程如下：
```
约课  =>  备课  =>  上课  =>  下课
```

状态|描述
:--:|:--
约课 | 在管理员约课后，老师和学生才能加入课堂
备课 | 备课状态下，老师可以加入课堂并进行课前准备工作
上课 | 开始上课后，后台将开始记录课堂内容以便后面查询(课时统计，课堂录制等)
下课 | 下课后，未退出课堂的老师和学生仍能交互，但退出后无法再加入该课堂



> 点击上课后，后台才会开始启动在线录制功能，点击下课后会停止录制

### 2、如何控制摄像头/麦克风

![](https://main.qcloudimg.com/raw/a1acb4431ec3b4d211c2358bd895707d.png)

视频区域中，左一(1)固定是展示老师的音视频信息，将鼠标悬停在视频上，会出现音视频控制栏

图标|名称|描述
:--:|:--:|:--
a| 麦克风 | 打开或关闭麦克风
b| 摄像头 | 打开或关闭摄像头

> 老师还可以控制学生的音视频状态

### 3、如何使用IM聊天

![](https://main.qcloudimg.com/raw/b65b96859859e1883e11a4dfa24b0a7f.png)

聊天区域由消息列表(1)和消息输入框(2)和发送按钮(3)组成，整个聊天区域可以通过(4)显示或隐藏

> 自己发送的消息会展示在右边


### 4、如何加载课件

- 第一步 打开课件管理页
参考**老师如何进行备课**中**老师在加入课堂后台上传**第一步

- 第二步 点击课件加载

> 可以同时加截多个课件，但同一个课件只能加载一次

### 5、如何使用文档类课件

加载文档课件后，课件下方会有控制区域

![](https://main.qcloudimg.com/raw/b135d1131a7900d90ef651b4de4c7bb8.png)

- (1) 缩放控制区域

通过缩小/放大按钮可以将文档进行放大以及还原
- (2) 翻页控制区域

对于多页的文档，可以通过左/右翻页对文档进行前/后翻页
- (3) 功能控制区域

![](https://main.qcloudimg.com/raw/0bc792049ecb035bbde9fd40ab1b31d1.png)

图标|名称|描述
:--:|:--:|:--
a| 拖动 | 拖动组件内容(放大后有效)
b| 撤销 | 撤销上一次白板操作
c| 恢复 | 恢复上一次撤销操作
d| 清空 | 清空白板

### 6、如何使用白板
整个内容大屏的背景，以及所有的文档类课件都可以当作白板使用
内容大屏右侧的工具栏可以修改白板的使用状态
选择画面可以直接进行板书

![](https://main.qcloudimg.com/raw/ddb52bdb486a9450f02948392fa65fab.png)

图标|名称|描述
:--:|:--:|:--
a| 选择 | 进入点击翻页或白板框选状态
b| 画笔 | 进入画笔状态
c| 文本 | 进入文件输入状态
d| 激光笔 | 进入激光笔状态
e| 橡皮擦 | 进入橡皮擦状态
f| 撤销 | 撤销上一次内容大屏白板操作
g| 恢复 | 恢复上一次内容大屏撤销操作
h| 清空 | 清空内容大屏白板

### 7、如何播放视频

- 第一步 打开工具箱

![](https://main.qcloudimg.com/raw/5524819f50c81ffd374325e5d6930277.png)

老师可通过标题栏中的工具箱(e)管理菜单打开工具箱

- 第二步 选择播放视频
- 第三步 选择要播放的视频文件

### 8、如何使用屏幕分享
- 第一步 点击屏幕分享-标题栏中功能区域的屏幕分享菜单(a)
- 第二步 选择屏幕分享区域

![](https://main.qcloudimg.com/raw/bd6792bbb8ff69bae34090dbc4305968.png)

- 第三步 开始屏幕分享
开始屏幕分享后，其他人可能过屏幕分享的播放地址观看
- 第四步 关闭屏幕分享
在不再需要分享屏幕时，可通过点击标题栏中功能区域的菜单(a)关闭

### 9、如何使用本地录制
 - 第一步 点击本地录制-标题栏中功能区域的录制菜单(b)
 - 第二步 选择开始或选择录制文件保存目录

![](https://main.qcloudimg.com/raw/efc274ce3bead6ff640b3011929edf8c.png)

 - 第三步 停止本地录制
 - 第四步 播放本地录制
 可在录制文件保存目录中找到录制文件，并使用播放器播放

### 10、如何进行成员管理
可以通过点击屏幕分享-标题栏中功能区域的成员管理菜单(d)

![](https://main.qcloudimg.com/raw/e076c18690ff0390214dd0a697ab0a14.png)

这里展示所有学生，并能够控制学生状态

图标|名称|描述
:--:|:--:|:--
a| 麦克风 | 打开或关闭该学生的麦克风
b| 摄像头 | 打开或关闭该学生的摄像头
c| 禁言 | 将该学生禁言或解除禁言
d| 移出 | 将该学生移出课堂
