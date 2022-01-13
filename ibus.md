
<tr>
<td><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/CiwnIwn">前言</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/PinInFangAng">南京官話拼音方案</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/LinIwnChaI">與漢語拼音的差異</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/angzhuangfa">安装南京拼音輸入法</a></td>
</tr>

# 安装方法〔Linux〕



Rime 在 Linux 的两种输入法平台（IBus 和 Fcitx）上都有实现，下面以 Ubuntu 上的 ibus-rime 为例。分为两大步骤：（1）安装 ibus-rime；（2）添加南京话拼音的方案和码表。

## 安装 ibus-rime

在 Ubuntu (>= 12.10) 上，可以通过下面的命令安装 ibus-rime。

```
sudo apt-get install ibus-rime
```

默认预装有“朙月拼音”和“倉頡五代”两种输入方案，用户可以根据需要安装其他输入方案，具体请参考下面这份官方说明。其他 Linux 发行版的安装也请参考这份说明。

> https://github.com/rime/home/wiki/RimeWithIBus

安装完毕后，请将 ibus-rime 添加到语言栏的菜单中，并且切换到 Rime 输入法。

![image-a1]

现在可以开始打字了。试着键入`han yu pin yin shu ru fa`，按空格键上屏。

![image-a2]

刚才输出的是繁体字。按`F4`或```Ctrl+` ```唤出菜单，选择`漢字->汉字`，切换到简化字模式。

![image-a3]

再次键入`han yu pin yin shu ru fa`，这回就是简化字了。

![image-a4]

Rime 输入法还有很多功能，需要时可以查看官网的文档。

> https://rime.im/docs

## 添加南京话拼音的方案和码表

南京话拼音输入法请从下列链接

- GITHUB： https://github.com/uliloewi/lang2jin1/archive/master.zip
或
- 百度网盘：https://pan.baidu.com/s/1AZLKPZwd_tt8z69D1iJCvA 提取码: j5vw

里面有三个.yaml文件，不需要作修改。感兴趣的读者可以用任何一款文本编辑器查看其中的内容。

- `langjin.schema.yaml`文件定义了输入方案。
- `langjin.dict.yaml`文件定义了码表。
- `default.custom.yaml`


接下来，打开文件夹`~/.config/ibus/rime/`（0.9.1 以下版本为`~/.ibus/rime/`），这个目录用于存放 Rime 的用户配置文件，我们把刚才的三个文件放到该目录下。

```
langjin.schema.yaml
langjin.dict.yaml
default.custom.yaml
```

放好之后要告知 Rime 输入法。在语言栏菜单中，点击 ⟲ (Deploy) 按钮。部署的速度取决于机器的性能，可能耗时几秒或几十秒，部署成功后会有提示信息。

![image-b1]

如果找不到 ⟲ 按钮，也可以运行下面命令，会触发“重新部署”。

```
rm ~/.config/ibus/rime/default.yaml; ibus-daemon -drx
```

回到输入界面，按`F4`或```Ctrl+` ```唤出菜单，切换到新增的“南京官话拼音”。

![image-b2]

现在可以使用南京话拼音打字了。试着键入下列字符：

```
lang jin pin in
```

![image-b3]


输入法支持用汉语拼音反查南京拼音。比如不知道“南”字怎么读，可以按 \` 键（在 Tab 键的上方），然后键入汉语拼音`nan`，就可以查到“南”字的南京话拼音。

![image-b5]

[image-a1]: https://uliloewi.github.io/LangJinPinIn/img/ibusA1.jpg
[image-a2]: https://uliloewi.github.io/LangJinPinIn/img/ibusA2.jpg
[image-a3]: https://uliloewi.github.io/LangJinPinIn/img/ibusA3.jpg
[image-a4]: https://uliloewi.github.io/LangJinPinIn/img/ibusA4.jpg

[image-b1]: https://uliloewi.github.io/LangJinPinIn/img/ibusB1.jpg
[image-b2]: https://uliloewi.github.io/LangJinPinIn/img/ibusB2.jpg
[image-b3]: https://uliloewi.github.io/LangJinPinIn/img/ibusB3.jpg
[image-b5]: https://uliloewi.github.io/LangJinPinIn/img/ibusB5.jpg
