# genish-impact-picker
<div align="center">

![](https://raw.githubusercontent.com/luyanci/Genshin-Impact-Wish-Simulator/main/static/icons/icon-256x256.png)

**原神抽卡点名器**

![Github Action](https://img.shields.io/badge/Github%20Actions-282a2e?style=for-the-badge&logo=githubactions&logoColor=367cfe)![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)

![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)![Electron.js](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white)![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

![Release](https://github.com/luyanci/genish-impact-picker/actions/workflows/release.yml/badge.svg)![Pages](https://github.com/luyanci/genish-impact-picker/actions/workflows/page.yml/badge.svg)![Build app](https://github.com/luyanci/genish-impact-picker/actions/workflows/app.yml/badge.svg)

</div>


(tips:本readme文档的信息卡片都能点，子模块的信息卡片可直接跳转到子模块仓库)

[![genish-impact-picker's Github Stats](https://stats.deeptrain.net/repo/luyanci/genish-impact-picker)](https://github.com/zmh-program/code-statistic)

[![Genshin-impact-wish-simulator's Github Stats](https://stats.deeptrain.net/repo/luyanci/Genshin-impact-wish-simulator)](https://github.com/luyanci/Genshin-impact-wish-simulator)

Rebased from https://github.com/cyanial/genshin-impact-picker

## 使用方法
### 本地使用
从release中下载对应系统的程序包，完整解压后运行程序

[![genish-impact-picker's Latest Release](https://stats.deeptrain.net/release/luyanci/genish-impact-picker)](https://github.com/luyanci/genish-impact-picker/release/latest)


### 在线使用
可通过以下按钮部署至Netlify/vercel：

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/luyanci/Genshin-Impact-Wish-Simulator)[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/luyanci/Genshin-Impact-Wish-Simulator)


也可通过以下链接访问(Powered by ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7))：



Note:Nostar为无自定义星数版本

|version|star|nostar|
|---|---|---|
|netlify status|[![Netlify Status](https://api.netlify.com/api/v1/badges/ffee3df0-a1d0-488a-b820-9bae737e4cf8/deploy-status)](https://app.netlify.com/sites/genshin-picker/deploys)|[![Netlify Status](https://api.netlify.com/api/v1/badges/6cd0fbc5-b04c-4798-840f-3ca6aa5e4855/deploy-status)](https://app.netlify.com/sites/genshin-picker-nostar/deploys)|
|link|[Click here](https://genshin-picker.netlify.app)|[Click here](https://genshin-picker-nostar.netlify.app)|

### notes
使用任意一种，在左上角问号中上传名单(**utf-8编码,txt格式**)即可使用

注意：自定义星数版本需要在名字前加3/4/5，否则不显示名字！


## 二次开发
### 要求
需要安装Nodejs

### 获取源码
由于本仓库使用了子模块功能，clone时要连着子模块一起clone过去

```sh
git clone --recursive https://github.com/luyanci/genish-impact-picker.git
```

如果已经clone，拉取子模块方法：
```
git submodule update --init --recursive
```

### 初始化

进入`Genshin-impact-wish-simulator`与`electron-static`文件夹，运行以下指令来初始化环境

```
#use npm
npm install
#use yarn
yarn install
```

### 调试

进入`Genshin-impact-wish-simulator`文件夹，运行以下指令，调试网页

```
#use npm
npm run dev
#use yarn
yarn run dev
```

### 构建

进入`Genshin-impact-wish-simulator`运行以下指令来构建

```
#use npm
npm run build
#use yarn
yarn run build
```

将`.vercel/output`里的`static`文件夹整个复制到`electron-static`文件夹里，然后在该目录下执行以下指令，构建应用程序

```
#use npm
npm run build
#use yarn
yarn run build
```


## 感谢以下贡献者

![genshin-picker's Contributors](https://stats.deeptrain.net/contributor/luyanci/genish-impact-picker)

[![Genshin-Impact-Wish-Simulator's Contributors](https://stats.deeptrain.net/contributor/luyanci/Genshin-Impact-Wish-Simulator)](https://github.com/luyanci/Genshin-impact-wish-simulator)

同时欢迎各位对本项目提PR和Issues哦！