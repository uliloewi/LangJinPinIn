<tr>
<td><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/CiwnIwn">前言</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/PinInFangAng">南京官話拼音方案</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/LinIwnChaI">與漢語拼音的差異</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/angzhuangfa">安装南京拼音輸入法</a></td>
</tr>

# 安装方法〔Windows〕

在 Windows 上安装南京话拼音输入法，有两大步骤：（1）安装小狼毫输入法；（2）添加南京话拼音的方案和码表。

## 安装小狼毫输入法

从 Rime 的官网下载“小狼毫输入法”。下面的截图来自版本 0.9.30，部分界面与最新版本略有差异。

> https://rime.im/download

![image-a1]

运行安装程序。输入法程序需要比较高的系统权限，如果被某些杀毒软件拦截，请允许放行。

![image-a2]

接下来是一系列的安装选项，可以不用修改。

![image-a3]

![image-a4]

安装后会弹出设定菜单，左边一栏列出了预设的输入方案，有各种常见的音码、形码输入法，还有粤语、吴语，甚至中古汉语的输入方案。其中“朙月拼音”就是全拼，下面以它为例。这项配置以后可以随时更改。

![image-a6]

选择界面风格，安装完毕。这个选项以后也可以更改。

![image-a7]

点击桌面右下角的语言栏，切换到新增的输入法选项`小狼毫`。

![image-b1]

现在可以开始打字了。试着键入`han yu pin yin shu ru fa`，按空格键上屏。

![image-b2]

刚才输出的是繁体字。可以按`F4`或```Ctrl+` ```，唤出菜单，按`↑`和`↓`上下移动，按`PageUp`和`PageDown`前后翻页。第一页提供了基本选项，翻页后可以看到其他输入方案。这里选择`5`，切换到简化字模式。

![image-b3]

再次键入`han yu pin yin shu ru fa`，这回就是简化字了。

![image-b4]

小狼毫输入法还有很多功能，需要时可以查看官网的文档。

> https://rime.im/docs

## 添加南京话拼音的方案和码表

南京话拼音输入法在此下载：

> 百度网盘：https://pan.baidu.com/s/TODU


里面有两个文件，感兴趣的读者可以用任何一款文本编辑器查看其中的内容。

- 以`schema.yaml`结尾的文件定义了输入方案。
- 以`dict.yaml`结尾的文件定义了码表。

选好南京拼音添加到输入法。

![image-c1]

接下来的几个步骤，要用到“开始”菜单中“小狼毫输入法”文件夹的三个选项，下面分步详述。

![image-c11]

首先，在开始菜单中，选择`【小狼毫】用户文件夹`，系统会打开一个文件夹。这个目录用于存放 Rime 的用户配置文件，我们把`schema.yaml`和`dict.yaml`两个文件放到该目录下。

![image-c3]

放好之后要告知小狼毫输入法。在开始菜单中，选择`【小狼毫】重新部署`。

部署的速度取决于机器的性能，可能耗时几秒或几十秒。部署成功后没有提示信息，感兴趣的读者可以打开进程管理器，如果`WeaselDeploy.exe`进程消失了，说明部署过程结束。

![image-c5]

在开始菜单中，选择`【小狼毫】输入法设定`，唤出选项菜单。在左边一栏的最下方可以找到新增的“南京官话拼音”，打勾选上。

![image-c6]

回到输入界面，按`F4`或```Ctrl+` ```唤出菜单，按`PageDown`翻页，切换到新增的“南京官话拼音”。

![image-c7]

现在可以使用南京话拼音打字了。试着键入下列字符：

```
lang jin pin in
```

![image-c8]


输入法支持用汉语拼音反查南京话拼音。比如不知道“朝”字怎么读，可以按 \` 键（在 Tab 键的上方），然后键入汉语拼音`nan`，就可以查到“南”字的南京话拼音。

![image-c10]

[image-a1]: https://uliloewi.github.io/LangJinPinIn/img/weaselA1.jpg
[image-a2]: https://ww4.sinaimg.cn/large/006mIeATjw1f2ai9lmksdj30sg0lcn01.jpg
[image-a3]: https://uliloewi.github.io/LangJinPinIn/img/weaselA3.jpg
[image-a4]: https://uliloewi.github.io/LangJinPinIn/img/weasel4.jpg
[image-a5]: https://ww4.sinaimg.cn/large/006mIeATjw1f2ai9nloqkj30sg0lcwic.jpg
[image-a6]: https://ww4.sinaimg.cn/large/006mIeATjw1f2ai9o3rzqj30sg0lcn13.jpg
[image-a7]: https://ww1.sinaimg.cn/large/006mIeATjw1f2ai9ondg7j30sg0lcdjy.jpg
[image-a8]: https://ww3.sinaimg.cn/large/006mIeATjw1f2ai9p2lq0j30sg0lcwi2.jpg

[image-b1]: https://ww4.sinaimg.cn/large/006mIeATjw1f2aiempz48j30sg0lctaw.jpg
[image-b2]: https://ww3.sinaimg.cn/large/006mIeATjw1f2aien6s3sj30sg0lc76u.jpg
[image-b3]: https://ww4.sinaimg.cn/large/006mIeATjw1f2aienthpej30sg0lcgo5.jpg
[image-b4]: https://ww3.sinaimg.cn/large/006mIeATjw1f2aieo9qwoj30sg0lc0vc.jpg

[image-c1]: https://uliloewi.github.io/LangJinPinIn/img/weaselC1.jpg
[image-c2]: https://ww4.sinaimg.cn/large/006mIeATjw1f2aij98ozyj30sg0lc77d.jpg
[image-c3]: https://uliloewi.github.io/LangJinPinIn/img/weaselC3.jpg
[image-c4]: https://ww4.sinaimg.cn/large/006mIeATjw1f2aija7gdjj30sg0lctca.jpg
[image-c5]: https://ww4.sinaimg.cn/large/006mIeATjw1f2aijasbf5j30sg0lcn17.jpg
[image-c6]: https://uliloewi.github.io/LangJinPinIn/img/weaselC6.jpg
[image-c7]: https://uliloewi.github.io/LangJinPinIn/img/weaselC7.jpg
[image-c8]: https://uliloewi.github.io/LangJinPinIn/img/weaselC8.jpg
[image-c9]: https://ww3.sinaimg.cn/large/006mIeATjw1f2aijem663j30sg0lcdih.jpg
[image-c10]: https://uliloewi.github.io/LangJinPinIn/img/weaselC10.jpg
[image-c11]: https://ww4.sinaimg.cn/large/006mIeATjw1f2qc0urd6jj30sg0lcgp8.jpg

