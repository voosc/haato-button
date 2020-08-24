# 心按钮 / HAATO-BUTTON

![Version](https://img.shields.io/github/package-json/v/voosc/haato-button)
![Last Commit](https://img.shields.io/github/last-commit/voosc/haato-button)
![Stars](https://img.shields.io/github/stars/voosc/haato-button)

README: **中文** | [日本語](https://github.com/voosc/haato-button/blob/master/README.JA.md) | [English](https://github.com/voosc/haato-button/blob/master/README.EN.md)

> 哈恰玛~哈恰玛~

主页： https://haato.club

相关链接:

- [赤井心的 YouTube 频道](https://www.youtube.com/channel/UC1CfXB_kRs3C-zaeTG3oGyg)
- [赤井心的 Bilibili 频道](https://space.bilibili.com/339567211)
- [赤井心的 Twitter](https://twitter.com/akaihaato)

## 参与完善本项目

如果您不知道如何直接参与GitHub开发，可以直接将素材或意见建议发送到[haato@fubuki.moe](mailto:haato@fubuki.moe)，带上标题、内容以及您的ID（Bilibili、Twitter等均可），贡献者名单将会有您的名字。

当然您也可以发在 [Issues](https://github.com/voosc/haato-button/issues) ，同样也请带上标题和内容。

如果您可以进行开发，那么请Fork本项目进行修改，完成修改后在本项目中发起一个Pull Request，详细说明如下：

### 添加或修改音频

音频文件为mp3格式，码率128Kbps，储存在`static/voices/`目录下，对应的URL为`/voices/`。

所有的音频信息都存储在`assets/voices.json`中，要添加或修改音频，你同样需要修改这个文件中对应的内容。

如果需要对现有音频进行修改，建议将原音频文件删除，重新命名一个新文件，这样可以避免浏览器缓存问题。

### 参与翻译

请帮助进行日语和英语的翻译！

网页的翻译在`assets/locales/`中的以三个语音命名的json文件中，音频信息的翻译在`assets/voices.json`中对应的字段。

### 参与网页开发

本项目使用Vue + NuxtJS + Vuetify框架进行开发，要部署本地开发环境，请先安装最新版的Node与Yarn包管理器。

1. Fork 并 Clone 代码到本地
2. 进入代码目录，运行`yarn`以安装依赖项目
3. 开启本地开发服务器，运行`yarn dev`，这将会在`localhost:3000`启动，在代码修改过程中，本地开发服务器可以即时反映修改的结果。
4. 要编译可供部署的文件，请运行`yarn generate`，这将会在`dist`目录下生成可以直接部署到静态网站托管（GitHub Pages等）的文件。

## 贡献者

本项目基于[狐按钮](https://github.com/voosc/haato-button)进行修改。

开发：

- [离子](https://github.com/lonelyion)

音频剪辑：

- 迷猫
- 绝望二足兽

翻译：

- takanemanaka

特别感谢：

- [赤井心保护协会](https://space.bilibili.com/157389653)
- [御宅白狐的狐笋之林](https://space.bilibili.com/314977548)
- 以及以下在GitHub参与过项目的各位

[![GitHub Contributors](https://contributors-img.web.app/image?repo=voosc/haato-button)](https://github.com/voosc/haato-button/graphs/contributors)

## 协议

音频部分: [Hololive 二次创作条款](https://www.hololive.tv/terms) (只有日语).

其他部分：[MIT License](https://github.com/voosc/haato-button/blob/master/LICENSE)

本项目为爱好者作品，和 Hololive 官方没有关联

## 支持

### BrowserStack

Proudly using BrowserStack.

[![](https://i.loli.net/2017/09/27/59cbc16b0f8b4.png)](https://www.browserstack.com/)

> **BrowserStack** is a cloud-based cross-browser testing tool that enables developers to test their websites across various browsers on different operating systems and mobile devices, without requiring users to install virtual machines, devices or emulators.

### Vercel

Powered by Vercel.

[![vercel.png](https://i.loli.net/2020/07/18/rPah8FVmqBXL6dj.png)](https://www.vercel.com/?utm_source=oruyanke&utm_campaign=oss)

> **​Vercel** is a cloud platform for static sites and Serverless Functions that fits perfectly with your workflow. It enables developers to host Jamstack websites and web services that deploy instantly, scale automatically, and requires no supervision, all with no configuration.
