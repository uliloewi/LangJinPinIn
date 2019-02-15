<tr>
<td><a style="margin-right: 50px;" href="https://uliloewi.github.io/LangJinPinIn/CiwnIwn">前言</a></td>
<td ><a style="margin-right: 50px;" href="https://uliloewi.github.io/LangJinPinIn/PinInFangAng">南京官話拼音方案</a></td>
<td ><a style="margin-right: 50px;" href="https://uliloewi.github.io/LangJinPinIn/LinIwnChaI">與漢語拼音的差異</a></td>
<td ><a style="margin-right: 50px;" href="https://uliloewi.github.io/LangJinPinIn/angzhuangfa">安装南京拼音輸入法</a></td>
</tr>

# 安装方法〔macOS〕

{% include "./common_header.md" %}

在 macOS 上安装南京话拼音输入法，有两大步骤：（1）安装鼠须管输入法；（2）添加南京话拼音的方案和码表。

## 安装鼠须管输入法

从 Rime 的官网下载、安装“鼠须管输入法”。

> https://rime.im/download

安装完毕后，在语言栏的菜单中选择`鼠须管`/`Squirrel`。如果用户的系统语言是中文，该菜单选项也会是中文。

![image-a1]

现在可以开始打字了。试着键入`han yu pin yin shu ru fa`，按空格键上屏。

![image-a2]

刚才输出的是繁体字。按```Ctrl+` ```唤出菜单，其中第 2 项是基本选项，剩下是其他输入方案。这里选择`2`，展开基本选项，再选择`漢字->汉字`，切换到简化字模式。

![image-a3]

![image-a4]

再次键入`han yu pin yin shu ru fa`，这回就是简化字了。

![image-a5]

鼠须管输入法还有很多功能，需要时可以查看官网的文档。

> https://rime.im/docs

## 添加南京话拼音的方案和码表

南京话拼音输入法请从下列链接下载

> 百度网盘：https://pan.baidu.com/s/TODO

里面有两个文件，不需要作修改。感兴趣的读者可以用任何一款文本编辑器查看其中的内容。

- 以`schema.yaml`结尾的文件定义了输入方案。
- 以`dict.yaml`结尾的文件定义了码表。

除此之外，还要下载`default.custom.yaml`文件。用文本编辑器打开这个文件，把不需要的输入方案删去，保留自己想要的。其中，“朙月拼音”就是全拼，建议保留。

如果读者有兴趣，可以把 6 种口音同时添加到输入法，但是会增加后面的部署时间。建议第一次不要贪多，先选一个就好。这里以潮州音为例，修改后的`default.custom.yaml`文件如下所示。

```
patch:
  schema_list:
    - schema: luna_pinyin    # 朙月拼音
    - schema: langjin         # 南京官话拼音
```

接下来，选择语言栏菜单中的`用户设定`/`Settings`，系统会打开一个文件夹。

![image-b1]

这个目录用于存放 Rime 的用户配置文件，我们把刚才的三个文件放到该目录下。

```
langjin.schema.yaml
langjin.dict.yaml
default.custom.yaml
```

放好之后要告知鼠须管输入法。在语言栏菜单中，选择`重新部署`/`Deploy`。部署的速度取决于机器的性能，可能耗时几秒或几十秒，部署成功后会有提示信息。

回到输入界面，按```Ctrl+` ```唤出菜单，切换到新增的“南京官话拼音”。

![image-b2]

现在可以使用南京话拼音打字了。试着键入下列字符：

```
lang jin pin in
```

![image-b3]

![image-b4]

输入法支持用汉语拼音反查南京话拼音。比如不知道“朝”字怎么读，可以按 \` 键（在 Tab 键的上方），然后键入汉语拼音`chao`，就可以查到“朝”字的南京话拼音。

![image-b5]

[image-a1]: https://ww2.sinaimg.cn/large/006mIeATjw1f2qfq0mxlmj30m80m8adb.jpg
[image-a2]: https://ww2.sinaimg.cn/large/006mIeATjw1f2qfq13jhsj30fa0dwgmp.jpg
[image-a3]: https://ww2.sinaimg.cn/large/006mIeATjw1f2qfq1pjxkj30go0fadh9.jpg
[image-a4]: https://ww2.sinaimg.cn/large/006mIeATjw1f2qfq2ak5kj30dw0faab6.jpg
[image-a5]: https://ww1.sinaimg.cn/large/006mIeATjw1f2qfq2v1p0j30fa0fajsm.jpg

[image-b1]: https://ww1.sinaimg.cn/large/006mIeATjw1f2qfq3bolcj30m80m8adb.jpg
[image-b2]: https://ww3.sinaimg.cn/large/006mIeATjw1f2qfq3sp9bj30go0dw0tu.jpg
[image-b3]: https://ww1.sinaimg.cn/large/006mIeATjw1f2qfq4jx94j30nc0goabo.jpg
[image-b4]: https://ww1.sinaimg.cn/large/006mIeATjw1f2qfq5457yj30kk0godhf.jpg
[image-b5]: https://ww1.sinaimg.cn/large/006mIeATjw1f2qfq5vbatj30dw0i2dh8.jpg
