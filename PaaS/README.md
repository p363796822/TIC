## 下载说明

<font color="#FF0000">注意：</font> 由于`Github`默认不支持大文件上传，请您在clone代码前先安装[Git-LFS](./Git-LFS.md)，用于实现Github对大文件的支持。请使用以下命令clone代码，<font color="#FF0000">勿</font>直接`Download ZIP`。
```
git clone https://github.com/tencentyun/TIC.git
```

如果您访问 Github 或安装 Git-LFS 遇到问题，请使用腾讯云分流地址下载：

<table>
<tr>
<th style="text-align:center">Web</th>
<th style="text-align:center">小程序</th>
<th style="text-align:center">Windows</th>
<th style="text-align:center">Android</th>
<th style="text-align:center">iOS</th>
<th style="text-align:center">macOS</th>
</tr>
<tr>
<td style="text-align:center"><a href="https://tic-res-1259648581.file.myqcloud.com/demo/Web.zip">Download Zip</a></td>
<td style="text-align:center"><a href="https://tic-res-1259648581.file.myqcloud.com/demo/小程序.zip">Download Zip</a></td>
<td style="text-align:center"><a href="https://tic-res-1259648581.file.myqcloud.com/demo/Windows.zip">Download Zip</a></td>
<td style="text-align:center"><a href="https://tic-res-1259648581.file.myqcloud.com/demo/Android.zip">Download Zip</a></td>
<td style="text-align:center"><a href="https://tic-res-1259648581.file.myqcloud.com/demo/iOS.zip">Download Zip</a></td>
<td style="text-align:center"><a href="https://tic-res-1259648581.file.myqcloud.com/demo/macOS.zip">Download Zip</a></td>
</tr>
</table>

## Demo 下载

|所属平台|Demo 源码|Demo 运行说明| TIC 接入文档| TEduBoard 接入文档|
|:-:|:-:|:-:|:-:|:-:|
|Android|[Github](https://github.com/tencentyun/TIC/tree/master)|[Doc](./Android/README.md)|[Doc](./Docs/SDK文档/Android/互动课堂接入文档.md)|[Doc](./Docs/SDK文档/Android/互动白板接入文档.md)|
|iOS|[Github](https://github.com/tencentyun/TIC/tree/master)|[Doc](./iOS/README.md)|[Doc](./Docs/SDK文档/iOS/互动课堂接入文档.md)|[Doc](./Docs/SDK文档/iOS/互动白板接入文档.md)|
|Windows|[Github](https://github.com/tencentyun/TIC/tree/master)|[Doc](./Windows/README.md)|[Doc](./Docs/SDK文档/Windows/互动课堂接入文档.md)|[Doc](./Docs/SDK文档/iOS/互动白板接入文档.md)|
|macOS|[Github](https://github.com/tencentyun/TIC/tree/master)|[Doc](./macOS/README.md)|[Doc](./Docs/SDK文档/macOS/互动课堂接入文档.md)|[Doc](./Docs/SDK文档/iOS/互动白板接入文档.md)|
|Web|[Github](https://github.com/tencentyun/TIC/tree/master)|[Doc](./Web/README.md)|[Doc](./Docs/SDK文档/Web/互动课堂接入文档.md)|[Doc](./Docs/SDK文档/iOS/互动白板接入文档.md)|
|小程序|[Github](https://github.com/tencentyun/TIC/tree/master)|[Doc](./小程序/README.md)|[Doc](./Docs/SDK文档/小程序/互动课堂接入文档.md)|[Doc](./Docs/SDK文档/iOS/互动白板接入文档.md)|

## Demo 编译

为避免开发测试导致账号被强制下线，您需要替换自己的`SdkAppId`和测试账号信息。在 [实时音视频应用列表](https://console.cloud.tencent.com/rav) 中选择对应的应用，单击**下载公私钥**并输入私钥**生成 Demo 配置文件内容**，替换 Demo 中配置文件的账号内容即可开始测试。

|所属平台|配置文件路径|
|-|-|
|Android|Android/Demo/app/src/main/res/raw/config.json|
|iOS|iOS/Demo/TICDemo/TICDemo/Config/config.json|
|Windows|Windows/Demo/config.json|
|macOS|macOS/Demo/TICDemo_Mac/TICDemo_Mac/Config/config.json|
|Web|Web/Demo/js/account_dev.js|
|小程序|小程序/Demo/miniprogram/pages/tic/account.js|



