
<tr>
<td><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/CiwnIwn">前言</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/PinInFangAng">南京官話拼音方案</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/LinIwnChaI">與漢語拼音的差異</a></td>
<td ><a style="margin-right: 40px;" href="https://uliloewi.github.io/LangJinPinIn/angzhuangfa">安装南京拼音輸入法</a></td>
</tr>

# 安装方法〔iOS〕



在 iOS 上安装南京话拼音输入法，有两大步骤：（1）安装 iRime 输入法；（2）添加南京话拼音的方案和码表。其中，第2步需要一台电脑，和手机连上同一个WiFi/路由器。

## 安装 iRime 输入法

在 App Store 上搜索“iRime输入法”并安装。安装好后，桌面上会有“iRime输入法”。

![image-a1]

从桌面打开“iRime输入法”，可以看到设置菜单，其中“电脑快传”我们很快要用到。

![image-a3]

## 添加南京话拼音的方案和码表

这一步需要一台电脑，和手机连上同一个WiFi/路由器。

请从下列链接，选择南京话拼音输入法（langjin）下载到电脑上。
- GITHUB： https://github.com/uliloewi/lang2jin1/archive/master.zip
或
- 百度网盘：https://pan.baidu.com/s/1RCdZpaY6cxqrjDKm899mtg 提取码: ucj2


里面有多個文件，最主要的是这 2 个“langjin”开头的文件：

```
langjin.schema.yaml
langjin.dict.yaml
```

在手机桌面上打开“iRime输入法”，点击“电脑快传”。

![image-a3]

iRime 会在手机上启动一个服务器，如果成功，会在手机屏幕上显示手机的 IP 地址。

![image-b1]

如果失败，会显示`启动服务器失败`。遇到这种情况，请把“iRime输入法”杀掉，再重试一下。

![image-b2]

在电脑浏览器中访问手机上显示的 IP 地址，就可以通过该服务器来修改手机上的配置文件了。这配置文件default.customer.yaml（或叫default.yaml）可能就在IP http://192.168.178.xx/ 下，也可能在http://192.168.178.xx/下的文件夹“build”中。

![image-b3]

点击向下箭头如上图，下载default.customer.yaml（或叫default.yaml）文件，并打开此文件，找到“schema_list:”。

![image-e1]

在default.customer.yaml（或叫default.yaml）文件中的“schema_list:”下添加 “  - schema: langjin ”，并保存这个修改。



从电脑上把刚才的 2 个“langjin”开头的文件和修改过的配置文件上传到手机：

```
langjin.schema.yaml
langjin.dict.yaml
default.customer.yaml（或叫default.yaml）
```

在手机上回到“iRime输入法”页面，点击“部署”。
![image-a4]

等部署结束后，点击“选择方案”，找到新增的“南京官话拼音”。

![image-b4]

现在可以使用南京话拼音打字了。试着键入下列字符：

```
lang jin pin in
```

![image-b5]

[image-a1]: https://uliloewi.github.io/LangJinPinIn/img/irimeA1.jpg
[image-a3]: https://uliloewi.github.io/LangJinPinIn/img/irimeA3.jpg
[image-a4]: https://uliloewi.github.io/LangJinPinIn/img/irimeA4.jpg

[image-b1]: https://uliloewi.github.io/LangJinPinIn/img/irimeB1.jpg
[image-b2]: https://uliloewi.github.io/LangJinPinIn/img/irimeB2.jpg
[image-b3]: https://uliloewi.github.io/LangJinPinIn/img/irimeB3.jpg
[image-b4]: https://uliloewi.github.io/LangJinPinIn/img/irimeB4.jpg
[image-b5]: https://uliloewi.github.io/LangJinPinIn/img/irimeB5.jpg
[image-e1]: https://uliloewi.github.io/LangJinPinIn/img/irimeE1.jpg
