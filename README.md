# free-chatgpt-client-pub

**A free chatgpt client, no need for a key, no need to log in.免费的chatgpt客户端，无需密钥，无需登录**

## 重大更新,已支持联网搜索,AI画图 Major update, now Supported online search,AI Drawing..

本次重大更新,重构了界面样式,更加美观(感谢群内热心的”白板”兄弟爆肝写界面,真的非常感谢!)

更新内容:

1.全新的界面;

2.优化检测更新模块,支持静默检测,不弹窗打扰;

3.优化节点自动选择方式;

4.新增插件系统,可以自己写插件,插入即可新增节点;

5.新增poe海外节点,内置GPT4和Claude+等多种模型,不过需要自行登录;

6.优化国际版,官方版的页面跟随窗口大小自适应;

## 支持官方API

QQ交流群:743685926


下载链接 Download link:
>**Windows--[ChatGPT.Setup.3.0.0.exe](https://github.com/akl7777777/free-chatgpt-client-pub/releases/download/v3.0.0/OpenAi-ChatGPT-Setup-3.0.0.exe)**

>**Windows免安装版--[win-unpacked_v3.0.0.zip](https://github.com/akl7777777/free-chatgpt-client-pub/releases/download/v3.0.0/win-unpacked-3.0.0.zip)**

>**Win7版--[Win7-Setup-3.0.0.exe](https://github.com/akl7777777/free-chatgpt-client-pub/releases/download/v3.0.0/Win7-Setup-3.0.0.exe)**

>**Win7免安装版--[win7-unpacked-3.0.0.zip](https://github.com/akl7777777/free-chatgpt-client-pub/releases/download/v3.0.0/win7-unpacked-3.0.0.zip)**

>**MacOS--[OpenAi-ChatGPT-3.0.0.dmg](https://github.com/akl7777777/free-chatgpt-client-pub/releases/download/v3.0.0/OpenAi-ChatGPT-3.0.0.dmg)**

>**Linux--[OpenAi-ChatGPT_3.0.0_amd64.deb](https://github.com/akl7777777/free-chatgpt-client-pub/releases/download/v3.0.0/OpenAi-ChatGPT_3.0.0_amd64.deb)**

>**手机版请去[ChatGPT手机客户端](https://github.com/akl7777777/free-chatgpt-client-mobile-pub)**


### 功能点:

>0.支持GPT联网搜索

>1.支持多节点测速自动切换;

>2.支持国内免翻版和国际版的切换;

>3.无需无需key,无需注册,无需登录;

>4.支持多平台,Windows,MacOS,Linux,Android;

>5.支持:普通对话模式,翻译模式,长文翻译(不限制字数),文字润色四种模式切换;

>6.支持对话上下文,清空对话上下文;

>7.支持导出markdown

>8.支持官方API自行填写key

>9.支持AI出图


使用效果图:

3.0.0新版效果:

<img width="1011" alt="image" src="https://user-images.githubusercontent.com/84266551/232382176-e039728c-d47e-4e37-88e1-bbed6bc3bf42.png">


多节点自动切换(联网GPT节点可用):

<img width="336" alt="image" src="https://user-images.githubusercontent.com/84266551/229284827-d19d597f-bda3-4089-9713-e6db69e7ab17.png">



目前已支持5种模式:对话,文字润色,翻译,长文翻译(不限字数),AI出图

<img width="222" alt="image" src="https://user-images.githubusercontent.com/84266551/227693939-3b8b36b3-ef80-4b89-af1a-f17b038c8f61.png">

联网回答(类似于new bing)

<img width="1024" alt="image" src="https://user-images.githubusercontent.com/84266551/229284913-ee247071-7676-44a1-a208-31e51d32a731.png">


AI出图

<img width="1024" alt="image" src="https://user-images.githubusercontent.com/84266551/227693826-cd90f49a-b40c-4dda-9621-b2493ca9369d.png">


默认版:

<img width="824" alt="image" src="https://user-images.githubusercontent.com/84266551/224465821-80d66b48-fa40-446a-b040-ab2dfff9c9bf.png">

国际版:

<img width="824" alt="image" src="https://user-images.githubusercontent.com/84266551/224465757-aead01c0-50a7-469f-8ff1-130aa31d2d5f.png">


<img width="824" alt="image" src="https://user-images.githubusercontent.com/84266551/224361804-9addf006-66c2-4683-a021-80cb13e76222.png">

**ChatGPT写代码效果图:**

![5eb2c2fe4395269df093230718e59916](https://user-images.githubusercontent.com/84266551/225805028-03d31c32-c4a5-4f24-bfc7-b06a48b4bedb.png)

**长文翻译不限字数效果图**

<img width="1311" alt="image" src="https://user-images.githubusercontent.com/84266551/226585792-e2600ab3-fe1e-4ff1-840f-f85e4d39d001.png">


备注 : MacOS如果打不开需要开启任意来源

打开【启动台】，选择【终端】，输入：
```
sudo spctl  --master-disable
```
然后回车，继续输入密码（密码输入时是不可见的），然后回车。

MacOS 打开软件出现 ‘xxx’ "将对您的电脑造成伤害。 您应该将它移到废纸篓。"的解决方式

解决方法一
访达 -> 应用程序 xxx.App -> 右键 -> 显示简介 -> 勾选 “覆盖恶意软件保护”。

![image](https://user-images.githubusercontent.com/84266551/230546962-4be53b45-9183-4c14-886f-5902d7b8fd58.png)

解决方法二

如果没用，尝试使用以下的命令方式

codesign --force --deep --sign - /Applications/OpenAi-ChatGPT.app


关于Windows7的问题:

可能有些用户会出现

![image](https://user-images.githubusercontent.com/84266551/227716216-b0eed99b-cf0e-4f1c-81d5-dd19ee72bad6.png)

如果条件允许的情况下,试着升win10

如果一定要用win7,建议去下载个补丁试试

https://support.microsoft.com/zh-cn/topic/microsoft-%E5%AE%89%E5%85%A8%E5%85%AC%E5%91%8A-%E4%B8%8D%E5%AE%89%E5%85%A8%E7%9A%84%E5%BA%93%E5%8A%A0%E8%BD%BD%E5%8F%AF%E8%83%BD%E5%85%81%E8%AE%B8%E8%BF%9C%E7%A8%8B%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%A0%81-486ea436-2d47-27e5-6cb9-26ab7230c704

https://www.exefiles.com/zh-cn/dll/kernel32-dll/

安装补丁“此更新不适用于你的计算机”解决办法

https://blog.csdn.net/xunan003/article/details/82832528

## 友情链接

### bob翻译插件大合集:

>[OpenAI ChatGPT(免秘钥)插件](https://github.com/akl7777777/bob-plugin-akl-chatgpt-free-translate)

>[DeepL翻译插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-deepl-free-translate)

>[有道翻译插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-youdao-free-translate)

>[CNKI学术翻译插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-cnki-free-translate)

>[火山翻译插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-volcengine-free-translate)

>[百度翻译插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-baidu-free-translate)

>[腾讯翻译君插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-tencent-free-translate)

>[腾讯交互翻译插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-transmart-free-translate)

>[彩云小译插件(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-caiyunxiaoyi-free-translate)

>[只为日语 - MOJi辞書（じしょ）](https://github.com/akl7777777/bob-plugin-akl-mojidict-translate)

>[Papago Naver 韩语翻译(免秘钥)](https://github.com/akl7777777/bob-plugin-akl-papago-free-translate)

>[Bob翻译剪切板图片的AlfredWorkflow](https://github.com/akl7777777/BobTranslateClipboard)

>[Bob的Postman接口调试插件](https://github.com/akl7777777/bob-plugin-akl-postman)



### 开发不易,如果喜欢可以请作者喝一杯可乐,谢谢!

<img width="615" alt="zfbwx" src="https://user-images.githubusercontent.com/84266551/226084836-8260658f-4840-4fa0-bfa1-74fa0c41f4ff.png">


