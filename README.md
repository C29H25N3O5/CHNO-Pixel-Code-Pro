![Title](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/Title.jpg)

# CHO Pixel Code

## 介绍

氦, 这里是 C₂₉H₂₅N₃O₅. 没错, 就是那个在 B 站上做东方 Arrange 的那个 C₂₉H₂₅N₃O₅. 其实很久以前就有想要设计一套属于自己的字体的想法了, 但是迫于硬件条件没能实现.


不过事先声明一下, 我个人不是专业的字体设计师. 如果大佬们觉得这套字体设计得很屑的话, 望轻喷(


这款字体是一个等宽像素字体, 只有一个字重而且没有斜体(后面可能会补上), 同时参考了 Fira Code 和 Jetbrains Mono 的等宽连字. 这款字体还加入了 Powerline 字符, 所以你可以将这款字体用在你的终端 (如 zsh) 上. 这款字体兼容大部分拉丁字母､ 西里尔字母和基础希腊字母, 支持显示约 160 种语言.

这个作品同时也遵守 Creative Commons 发布的 CC BY 4.0 协议. 你可以将这个字体任意使用, 包括商用､ 设计､ 出版以及基于此字体开发自己的字体, 但是在使用时请注明原作者(C₂₉H₂₅N₃O₅). 使用时无需通知我本人.

因为个人原因, 之后我可能不会对这款字体作进一步的更新.




## 特性

- 支持超过 160 种语言
- 支持约 120 种等宽连字 (如 `-->` 和 `!=` )
- 支持170+种语言
- 十六进制数字和乘法中'x'的位置优化



## 安装

CHO Pixel Mono 可以安装在多种平台上.

### macOS

1. 下载字体.
2. 打开 "字体册".
3. 将下载的字体文件拖入字体册中的字体列表中.

### Windows

1. 下载字体.
2. 选择下载的字体.
3. 右键单击选中的字体, 然后再弹出的菜单中选择"安装".

### Linux

1. 下载字体.
2. 将字体移动至`~/.local/share/fonts` (如果你想给每个用户都安装此字体的话, 请移动到`/usr/share/fonts`).
3. 在 Terminal 中执行 `fc-cache -f -v`.

### iOS/iPadOS

1. 下载字体.
2. 在 App Store 中下载 iFont.
3. 打开"文件", 然后选择下载的字体.
4. 点击"分享", 然后点击 iFont.
5. 在 iFont 中找到"Installer"选项卡, 然后再列表中找到想要安装的字体并点击"INSTALL"按钮.
6. 在描述文件设置页面, 输入配置文件的名称(可以随便起).
7. 接下来会弹出一个网页, 点击对话框中的"允许".
8. 对话框会提醒已下载描述文件.
9. 打开设置, 在"飞行模式"上方会出现"已下载描述文件"的选项. 点击此选项.
10. 单击右上角的"安装".
11. 如果你的设备有密码的话, 输入密码.
12. 单击右上角的"安装".
13. 点击屏幕下方的"安装".

### Android

1. 下载字体.

2. 在应用商店下载 iFont.

3. 在"文件管理"中, 将字体文件移动至`Android SD Card/iFont/Custom`.

4. 打开 iFont, 进入我的>我的字体.

5. 打开安装的字体,  然后点击"安装".

   请注意,  此方法可能不适用于部分的 Android 发行版.

对于以上并未提及的操作系统, 请参考系统自带的说明.



## 支持连字列表:

![List of Ligatures](/Users/ms/Documents/Local Files/Git Repos/cho_pixel_code/Media/ligatures.jpg "List of Ligatures")

注: http､ https､ ftp 和十六进制连字可能无法在部分文本编辑器中正常显示. 某些文本编辑器不支持连字.



## 发行版

编译完成, 可以直接安装的字体以四种格式提供: OTF､ TTF､ WOFF 和 WOFF2.

但如果你想从源代码编译, 请参考以下步骤:

1. __请确认你有一个可以运行 macOS 的电脑.__ Glyphs 目前只能运行于 macOS 平台.

2. 在 glyphapps.com 下载最新版本的 Glyphs (官网有试用版).

3. 安装 Glyphs.

4. 使用 Glyphs 打开 .glyphs 文件.

5. 按下 Command-E, 然后选择导出选项.

6. 点击"导出"来导出字体文件.

   如果你只有运行 Windows､ Linux 或其他操作系统的电脑, 请安装虚拟机.



## 显示效果

![Sample](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/samples.jpg "Some Sample Texts")

![Languages](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/languages.jpg "CHO Pixel in 14 different languages")

![iTerm 2](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/iterm2.jpg "CHO Pixel in iTerm2 and zsh")

![C](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/c.jpg "C in Sublime Text")

![Java](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/java.jpg "Java in Sublime Text")

![Python](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/python.jpg "Python 3 in Sublime Text")



## 开源声明

本作品遵守美国 Creative Commons (创意共享) 发布的 CC BY 4.0 (署名) 协议. 你可以在根目录下的 LICENSE.cn.txt 中找到该协议的全文或访问 <https://creativecommons.org>.

![CC BY 4.0](https://gitee.com/c29h25n3o5_real/cho_pixel_code/raw/master/Media/cc_by.jpg)



## 支持语言列表 (机翻, 有可能出错):

__注: 部分支持的语言可能未出现在这个列表中.__

- 南非荷兰语
- 阿加姆语
- 阿肯语
- 阿尔巴尼亚语
- 阿斯图里亚语
- 阿苏语
- 阿塞拜疆语
- 巴菲亚语
- 班巴拉语
- 巴什基尔语
- 巴斯克语
- 白俄罗斯语
- 本巴语
- 贝纳语
- 波斯尼亚语
- 布列塔尼语
- 保加利亚语
- 加泰罗尼亚语
- 宿务语
- 车臣语
- 齐嘎语
- 楚瓦什语
- 科隆语
- 康沃尔语
- 科西嘉语
- 克罗地亚语
- 捷克语
- 丹麦语
- 杜阿拉语
- 荷兰语
- 恩布语
- 英语
- 额尔兹亚语
- 世界语
- 爱沙尼亚语
- 埃维语
- 法罗亚语
- 菲律宾语
- 芬兰语
- 法语
- 弗留里亚语
- 富拉语
- 嘎语
- 加利西亚语
- 甘达语
- 德语
- 希腊语
- 瓜拉尼语
- 古西语
- 豪萨语
- 匈牙利语
- 冰岛语
- 日语
- 伊格博语
- 伊纳里萨米语
- 印尼语
- 因特语
- 爱尔兰语
- 意大利语
- 爪哇语
- 济州语
- 约拉-方伊语
- 卡布弗迪亚努语
- 卡拉阿利苏特语
- 卡伦金语
- 坎巴语
- 哈萨克语
- 基库尤语
- 基尼亚卢旺达语
- 柯伊拉基尼语
- 小拉伯勒森尼语
- 科佩尔语
- 库尔德语
- 夸西奥语
- 吉尔吉斯语
- 兰吉语
- 拉脱维亚语
- 林加拉语
- 立陶宛语
- 逻辑语
- 低地德语
- 下索布语
- 卢巴语–加丹加语
- 罗语
- 卢森堡语
- 鲁雅语
- 马其顿语
- 马查姆语
- 马库瓦语
- 马孔德语
- 马达加斯加语
- 马来语
- 马耳他语
- 马恩语
- 毛利语
- 马普契语
- 马赛语
- 梅鲁语
- 梅特语
- 莫霍克语
- 蒙古语 (西里尔)
- 森日语
- 纳玛语
- 恩吉安语
- 北恩德贝莱语
- 北部萨米语北部索托语
- 挪威语博克马尔语
- 挪威语尼诺斯克语
- 努尔语
- 楚瓦语 
- 年科尔语
- 奥西坦语
- 奥罗莫语
- 奥塞梯语
- 波兰语
- 葡萄牙语
- 盖丘亚语
- 罗马尼亚语
- 罗曼斯语
- 隆博语
- 润迪语
- 俄语
- 西乞力马扎罗语
- 萨哈语
- 桑布吕语
- 桑果语
- 桑古语
- 撒丁语
- 苏格兰盖尔语
- 塞纳语
- 塞尔维亚语
- 香巴拉语
- 肖纳语
- 西西里语
- 斯洛伐克语
- 斯洛文尼亚语
- 索加语
- 索马里语
- 南恩德贝莱语
- 南索托语
- 西班牙语
- 斯瓦希里语
- 斯瓦提语
- 瑞典语
- 瑞士德语
- 台塔语
- 塔吉克语
- 太鲁阁语
- 塔萨瓦克语
- 鞑靼语
- 特索语
- 宗嘎语
- 茨瓦纳语
- 土耳其语
- 土库曼语
- 泰亚普乌克兰语
- 上索布亚语
- 文达语
- 越南语
- 温乔语
- 瓦隆语
- 沃尔瑟德语
- 威尔士语
- 西弗里西亚语
- 沃洛夫语
- 科萨语
- 中雅巴萨语
- 约鲁巴语
- 扎玛语
- 祖鲁语

