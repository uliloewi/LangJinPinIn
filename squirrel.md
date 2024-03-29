
<tr>
<td><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/CiwnIwn">前言</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/PinInFangAng">南京官話拼音方案</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/LinIwnChaI">與漢語拼音的差異</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/angzhuangfa">安装南京拼音輸入法</a></td>
</tr>

# 安装方法〔macOS〕



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

- GITHUB： https://github.com/uliloewi/lang2jin1/archive/master.zip
或
- 百度网盘：https://pan.baidu.com/s/1RCdZpaY6cxqrjDKm899mtg 提取码: ucj2

里面有三个.yaml文件，不需要作修改。感兴趣的读者可以用任何一款文本编辑器查看其中的内容。

- `langjin.schema.yaml`文件定义了输入方案。
- `langjin.dict.yaml`文件定义了码表。
- `default.custom.yaml`

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

输入法支持用汉语拼音反查南京话拼音。比如不知道“南”字怎么读，可以按 \` 键（在 Tab 键的上方），然后键入汉语拼音`nan`，就可以查到“南”字的南京话拼音。

![image-b5]

[image-a1]: https://uliloewi.github.io/LangJinPinIn/img/squirrelA1.jpg
[image-a2]: https://uliloewi.github.io/LangJinPinIn/img/squirrelA2.jpg
[image-a3]: https://uliloewi.github.io/LangJinPinIn/img/squirrelA3.jpg
[image-a4]: https://uliloewi.github.io/LangJinPinIn/img/squirrelA4.jpg
[image-a5]: https://uliloewi.github.io/LangJinPinIn/img/squirrelA5.jpg

[image-b1]: https://uliloewi.github.io/LangJinPinIn/img/squirrelB1.jpg
[image-b2]: https://uliloewi.github.io/LangJinPinIn/img/squirrelB2.jpg
[image-b3]: https://uliloewi.github.io/LangJinPinIn/img/squirrelB3.jpg
[image-b5]: https://uliloewi.github.io/LangJinPinIn/img/squirrelB5.jpg

