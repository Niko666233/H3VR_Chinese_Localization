# H3VR汉化模组 (WIP)

基于[XUnity Auto Translator](https://github.com/bbepis/XUnity.AutoTranslator)的汉化模组。未完全汉化，但给新手入门足够了，后面会不断完善。

## English (If you can read this you probably don't need this)

A mod for H3VR that uses [XUnity Auto Translator](https://github.com/bbepis/XUnity.AutoTranslator) to translate the game to Chinese. Very WIP. Now can be installed with one click, just like any other mods.

## **现可一键自动安装**

现在你可以像安装其他普通mod一样安装此汉化模组了

## **现已解决mod冲突问题**

~~目前已知汉化mod会和使用Newtonsoft.Json的模组冲突，例如[Stovepipe](https://thunderstore.io/c/h3vr/p/Smidgeon/Stovepipe/)和[MagBoop](https://thunderstore.io/c/h3vr/p/Smidgeon/MagBoop/)，实际情况因mod而异，很遗憾的是这是XUnity Auto Translator的问题，我尝试了最新版本依然有这个问题，如果你有什么解决方法请务必告诉我。~~

现已解决，理论上不会再和别的mod冲突了，但如果还有问题请告诉我。如果依然有冲突的话请尝试卸载汉化并重新安装，或者手动删除XUnity.AutoTranslator下的Translators文件夹。

## 汉化更新慢？

由于Thunderstore的审核机制，每次更新汉化都要被自动审核退回（Invalid Submission），每次都要去Discord找管理员对线，所以我现在决定只在大版本更新时在Thunderstore更新汉化，其他的汉化更新会放在[爱发电](https://afdian.tv/a/Niko666)和[Github](https://github.com/Niko666233/H3VR_Chinese_Localization)上，等不及的话可以在上述地方下载最新版本的汉化。

## 致谢

- XUnity Auto Translator制作组
- 我仅剩的唯一一个真心朋友TengNB，虽然他连VR都没有
- H3VR中文交流群，群号：495110970，国内的mod作者基本都在里面了，我也在里面当金牌客服，只要我有空基本有求必应，没事也欢迎在群里聊天吹水
- 你
- 做付费汉化的哥们，有钱一起恰，我的爱发电：<https://afdian.tv/a/Niko666>

## 为什么能一键安装了，以及代价

众所周知，本汉化基于XUnity Auto Translator，而XUnity Auto Translator需要XUnity ResourceRedirector作为依赖，由于之前版本的汉化使用的是最新版的XUnity Auto Translator，与Thunderstore的XUnity ResourceRedirector不兼容，而且由于Thunderstore无法上传“相同”的mod，所以之前的汉化不能附带最新版本的XUnity ResourceRedirector，要想上传就只能舍弃它，然后让用户手动安装。

这个版本的汉化使用的是非常老旧版本的XUnity Auto Translator，解决了兼容性问题，如果你愿意帮忙汉化的话欢迎在[Github](https://github.com/Niko666233/H3VR_Chinese_Localization) Pull Requests，文本在config\Translation\里面的四个.txt文件里（实际上只用到了三个）。具体如何进行汉化建议看XUnity Auto Translator的官方文档。

## 更新日志

- 0.1.5: 更新汉化
- 0.1.4: 修复mod冲突问题
- 0.1.2: 更新汉化，XUnity Auto Translator更新至4.21.0（最后一个支持Resource Redirector 1.2.0的版本）
- 0.1.1: 更新汉化
- 0.1.0: 替换XUnity Auto Translator为旧版本，实现一键安装
