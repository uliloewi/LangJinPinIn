# 安装方法〔iOS〕

{% include "./common_header.md" %}

在 iOS 上安装南京话拼音输入法，有两大步骤：（1）安装 iRime 输入法；（2）添加南京话拼音的方案和码表。其中，第2步需要一台电脑，和手机连上同一个WiFi/路由器。

## 安装 iRime 输入法

在 App Store 上搜索“iRime输入法”并安装。

在系统“设置”中，找到“键盘”选项，点击“添加新键盘”，将“iRime输入法”添加进来。

![image-a1]

![image-a2]

从桌面打开“iRime输入法”，点击“选择你喜欢的输入法”。这里列出了预置的输入方案，有各种常见的音码、形码输入法，还有粤语、吴语，甚至中古汉语的输入方案。其中“朙月拼音”就是全拼，下面以它为例。

![image-a3]

点击“繁简转换”，默认是繁体字模式。选择“繁体到简体”，切换到简化字模式。

![image-a4]

打开一处能够写字的地方，将输入法切换成“iRime输入法”。

![image-a5]

现在可以开始打字了。试着键入`han yu pin yin shu ru fa`，按空格键上屏。

![image-a6]

## 添加南京话拼音的方案和码表

这一步需要一台电脑，和手机连上同一个WiFi/路由器。

请从下列链接，选择南京话拼音输入法（langjin）下载到电脑上。

> 百度网盘：https://pan.baidu.com/s/TODO


里面有 4 个文件，包括了输入方案和编译好的二进制码表，这 4 个文件分别是：

```
langjin.prism.bin
langjin.reverse.bin
langjin.schema.yaml
langjin.table.bin
```

除此之外，还要下载 2 个配置文件：

```
default.yaml
default.custom.yaml
```

在手机上打开“iRime输入法”，点击“配置你的输入法”。iRime 会在手机上启动一个服务器，如果成功，会在手机屏幕上显示手机的 IP 地址。

![image-b1]

如果失败，会显示`启动服务器失败`。遇到这种情况，请把“iRime输入法”杀掉，再重试一下。

![image-b2]

在电脑浏览器中访问手机上显示的 IP 地址，就可以通过该服务器来修改手机上的配置文件了。

![image-b3]

先把手机上原有的 2 个配置文件删掉：

```
default.yaml
default.custom.yaml
```

再从电脑上把刚才的 6 个文件上传到手机：

```
default.yaml
default.custom.yaml
langjin.prism.bin
langjin.reverse.bin
langjin.schema.yaml
langjin.table.bin
```

在手机上回到“iRime输入法”页面，点击“选择你喜欢的输入法”，找到新增的“南京官话拼音”。

![image-b4]

现在可以使用南京话拼音打字了。试着键入下列字符：

```
lang jin pin in
```

![image-b5]

[image-a1]: https://wx2.sinaimg.cn/large/006mIeATgy1fefis6qpxjj30ku1123zc.jpg
[image-a2]: https://wx3.sinaimg.cn/large/006mIeATgy1fefis76vtmj30ku1120vb.jpg
[image-a3]: https://wx1.sinaimg.cn/large/006mIeATgy1fefis7n4s1j30ku112410.jpg
[image-a4]: https://wx3.sinaimg.cn/large/006mIeATgy1fefis82wk8j30ku1120ue.jpg
[image-a5]: https://wx1.sinaimg.cn/large/006mIeATgy1fefis8src5j30ku11244s.jpg
[image-a6]: https://wx3.sinaimg.cn/large/006mIeATgy1fefis9jm13j30ku112n2v.jpg

[image-b1]: https://wx3.sinaimg.cn/large/006mIeATgy1fefisa0pa2j30ku112wfk.jpg
[image-b2]: https://wx3.sinaimg.cn/large/006mIeATgy1fefisaf8s5j30ku1123zp.jpg
[image-b3]: https://wx3.sinaimg.cn/large/006mIeATgy1fefisawpx5j30zi10wn0w.jpg
[image-b4]: https://wx3.sinaimg.cn/large/006mIeATgy1fefisbeftpj30ku112go3.jpg
[image-b5]: https://wx3.sinaimg.cn/large/006mIeATgy1fefisbxp3ij30ku112wk6.jpg
