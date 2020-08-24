# Haato-Button - Akai Haato's Voice Button

![Version](https://img.shields.io/github/package-json/v/voosc/haato-button)
![Last Commit](https://img.shields.io/github/last-commit/voosc/haato-button)
![Stars](https://img.shields.io/github/stars/voosc/haato-button)

README: [中文](https://github.com/voosc/haato-button/blob/master/README.md) | [日本語](https://github.com/voosc/haato-button/blob/master/README.JA.md) | **English**

> Brand new voice buttons for Akai Haato, we are aimming at building a comprehensive project related to Akai Haato.

Project Homepage: https://haato.club

Related Links:

* [Akai Haato's Youtube Channel](https://www.youtube.com/channel/UC1CfXB_kRs3C-zaeTG3oGyg)
* [Akai Haato's Bilibili Channel](https://space.bilibili.com/339567211)
* [Akai Haato's Twitter](https://twitter.com/akaihaato)

## Contributing

If you don't know how to participate on GitHub, you can directly send voice clips or suggestions to [haato@fubuki.moe](mailto:haato@fubuki.moe) with title, content and your social ID(Twitter, Bilibili or so on). We will add your ID to the contributors list below.

Also you can submit [Issues](https://github.com/voosc/haato-button/issues) to upload audio clips.

If you can do some programming, just fork this repository and modify it. After you have done, just open a Pull Request. For detailed information, please read below.

### Add or modify voice

Voice is always in mp3 format with 128Kbps bitrate and stored in `static/voices/`. The corresponding URL is `/voices/`.

All voice meta data is stored in `assets/voices.json`. To add or modify these voices, you need to modify this file accordingly.

If you want to modify existed voice clips, I suggest deleting the origin file and name a new filename to avoid browers' cache problem.

### Participate in translation

Please help us translate to English and Japanese!

The language files for the main program are in three json files named the language name in `assets/locales/`.

The language files for voices are in `assets/voices.json`.

## Deploying a local development environment

This site is developed using Vue + NuxtJS + Vuetify.

To deploy a local development environment, first install the latest version of Node and Yarn. Then follow these steps:

1. Fork and clone the code.

2. Go to the code directory and run `yarn` to install dependencies.

3. Run `yarn dev` to start local developemnt server at `localhost:3000`. The local development server can immediately reflect the results of your modification.

4. To compile the files for deployment, run `yarn generate`, which will generate the `dist` directory. This site is completely static, you can directly deploy the entire `dist` directory.

## Contributors

This project is based on [Fubuki Button](https://github.com/voosc/haato-button).

Development:

- [Lonely Ion](https://github.com/lonelyion)

Audio Editors:

- 迷猫
- 绝望二足兽

Translation:

- takanemanaka

Special Thanks to:

- [赤井心保护协会](https://space.bilibili.com/157389653)
- [御宅白狐的狐笋之林](https://space.bilibili.com/314977548)
- And those who contributed to this project on GitHub

[![GitHub Contributors](https://contributors-img.web.app/image?repo=voosc/haato-button)](https://github.com/voosc/haato-button/graphs/contributors)

## LICENCE

Audio: According to the [Hololive Secondary Creation Terms](https://www.hololive.tv/terms) (Japanese only).

Other parts: [MIT License](https://github.com/voosc/haato-button/blob/master/LICENSE)

This project is a work of enthusiasts and is not related to the Hololive official.

## 支持

### BrowserStack

Proudly using BrowserStack.

[![](https://i.loli.net/2017/09/27/59cbc16b0f8b4.png)](https://www.browserstack.com/)

> **BrowserStack** is a cloud-based cross-browser testing tool that enables developers to test their websites across various browsers on different operating systems and mobile devices, without requiring users to install virtual machines, devices or emulators.

### Vercel

Powered by Vercel.

[![vercel.png](https://i.loli.net/2020/07/18/rPah8FVmqBXL6dj.png)](https://www.vercel.com/?utm_source=oruyanke&utm_campaign=oss)

> **​Vercel** is a cloud platform for static sites and Serverless Functions that fits perfectly with your workflow. It enables developers to host Jamstack websites and web services that deploy instantly, scale automatically, and requires no supervision, all with no configuration.
