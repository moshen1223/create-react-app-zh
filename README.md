# 创建React应用 [![Build Status](https://travis-ci.org/facebookincubator/create-react-app.svg?branch=master)](https://travis-ci.org/facebookincubator/create-react-app)

- [English](https://github.com/facebookincubator/create-react-app/blob/master/README.md)
- 简体中文

无构建配置下创建React应用。

* [入门](#入门) – 如何创建新应用。
* [用户指南](https://github.com/XanthusL/create-react-app-zh/blob/master/packages/react-scripts/template/README-zh.md) – 如何根据引导开发React应用。

创建在macOS、 Windows、和Linux下通用的React应用<br>
如遇到问题请[提交issue](https://github.com/facebookincubator/create-react-app/issues/new).

## 快速预览

```sh
npm install -g create-react-app

create-react-app my-app
cd my-app/
npm start
```

打开[http://localhost:3000/](http://localhost:3000/)查看应用.<br>
当准备部署应用时, 通过 `npm run build` 命令创建一个精简包.

<img src='https://camo.githubusercontent.com/506a5a0a33aebed2bf0d24d3999af7f582b31808/687474703a2f2f692e696d6775722e636f6d2f616d794e66434e2e706e67' width='600' alt='npm start'>

### 立即开始

你 **不** 需要安装或配置像Webpack、Babel这类工具<br>
这些工具是预设好并隐藏的，因此你可以专注于代码。

仅需要创建个项目, 然后就可以继续了。

## 入门

### 安装


全局安装一次:


```sh
npm install -g create-react-app
```

**你机器上的Node版本需要>=4**.

**为了更快的安装速度和更好的磁盘利用，我们强烈建议使用 6 以上版本的Node和 3 以上版本的npm。** 你可以通过 [nvm](https://github.com/creationix/nvm#usage) 在不同的项目之间轻松地切换Node版本。

**此工具不提供Node后端**. Node的安装仅是Create React App所需。

### 创建应用

创建一个新应用, 执行命令:

```sh
create-react-app my-app
cd my-app
```

它会在当前文件夹下创建一个叫做 `my-app` 的目录。<br>
在该目录下会生成初始的项目结构并安装相关的依赖：

```
my-app/
  README.md
  node_modules/
  package.json
  .gitignore
  public/
    favicon.ico
    index.html
  src/
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
```

无需配置，也没有复杂的目录结构，只有你构建应用所需的文件。<br>
安装完成后，你就可以在项目文件夹中执行一些命令：

### `npm start` 或 `yarn start`

在开发模式下运行应用<br>
打开 [http://localhost:3000](http://localhost:3000) 在浏览器中查看。

你做出编辑时，页面会重新加载<br>
在控制台能看到构建错误和警告。

<img src='https://camo.githubusercontent.com/41678b3254cf583d3186c365528553c7ada53c6e/687474703a2f2f692e696d6775722e636f6d2f466e4c566677362e706e67' width='600' alt='Build errors'>

### `npm test` 或 `yarn test`

在交互模式下运行测试观察者(test watcher)。<br>
默认情况下，运行与自上次提交以来有改变的文件有联系的测试。

[Read more about testing.](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#running-tests)

### `npm run build` 或 `yarn build`

将应用作为产品构建到 `build` 文件夹。<br>
它在生产模式下正确打包React，并优化构建以获得最佳性能。

此构建是已压缩的，文件名含有散列值(hash)<br>
现在你的应用可以部署了!

## 用户指南

[用户指南](https://github.com/XanthusL/create-react-app-zh/blob/master/packages/react-scripts/template/README-zh.md) 包括不同话题的信息，例如：

- [更新到新版本](https://github.com/XanthusL/create-react-app-zh/blob/master/packages/react-scripts/template/README-zh.md#更新到新版本)
- [目录结构](https://github.com/XanthusL/create-react-app-zh/blob/master/packages/react-scripts/template/README-zh.md#目录结构)
- [可用脚本](https://github.com/XanthusL/create-react-app-zh/blob/master/packages/react-scripts/template/README-zh.md#可用脚本)
- [Supported Language Features and Polyfills](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#supported-language-features-and-polyfills)
- [Syntax Highlighting in the Editor](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#syntax-highlighting-in-the-editor)
- [Displaying Lint Output in the Editor](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#displaying-lint-output-in-the-editor)
- [Debugging in the Editor](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#debugging-in-the-editor)
- [Changing the Page `<title>`](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#changing-the-page-title)
- [Installing a Dependency](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#installing-a-dependency)
- [Importing a Component](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#importing-a-component)
- [Adding a Stylesheet](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-stylesheet)
- [Post-Processing CSS](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#post-processing-css)
- [Adding a CSS Preprocessor (Sass, Less etc.)](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-css-preprocessor-sass-less-etc)
- [Adding Images, Fonts, and Files](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-images-fonts-and-files)
- [Using the `public` Folder](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#using-the-public-folder)
- [Using Global Variables](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#using-global-variables)
- [Adding Bootstrap](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-bootstrap)
- [Adding Flow](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-flow)
- [Adding Custom Environment Variables](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-custom-environment-variables)
- [Can I Use Decorators?](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#can-i-use-decorators)
- [Integrating with an API Backend](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#integrating-with-an-api-backend)
- [Proxying API Requests in Development](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#proxying-api-requests-in-development)
- [Using HTTPS in Development](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#using-https-in-development)
- [Generating Dynamic `<meta>` Tags on the Server](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#generating-dynamic-meta-tags-on-the-server)
- [Pre-Rendering into Static HTML Files](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#pre-rendering-into-static-html-files)
- [Running Tests](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#running-tests)
- [Developing Components in Isolation](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#developing-components-in-isolation)
- [Making a Progressive Web App](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#making-a-progressive-web-app)
- [Deployment](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#deployment)
- [Advanced Configuration](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#advanced-configuration)
- [Troubleshooting](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#troubleshooting)

用户指南的一份副本将会以 `README.md` 创建在你的项目文件夹下。

## 如何更新到新版本?

请参阅 [用户指南](https://github.com/XanthusL/create-react-app-zh/blob/master/packages/react-scripts/template/README-zh.md#更新到新版本) 以了解相关信息。

## 理念

* **单一依赖:** 只构建一个依赖。 它使用了Webpack，Babel，ESLint和一些其他惊人项目，但提供了它们之上的体验。(译者注：屏蔽了这些工具的具体使用细节，体验更友好)

* **无需配置:** 你不需要配置任何东西。 开发和生产的构建所需的合理配置都已经替你处理好了，因此可以专心撸代码了。

* **无锁定:** 你可以随时"eject"到自定义设置。 运行单个命令，所有需要的配置和依赖会直接移至你的项目中，因此可以从上次停下来的地方继续。

## 为什么用这个?

**如果你已经入门了** React, 通过 `create-react-app` 命令来自动化应用的构建。没有配置文件， `package.json`中的`react-scripts` 是唯一额外的构建依赖。你的环境中将有构建一个现代化React应用所需的一切：

* React, JSX, ES6, 和链式语法支持。
* ES6之外的语言扩展，如对象扩展运算符。
* 一个能检查出常见错误的开发服务器。
* 直接从JavaScript导入CSS和图像文件。
* 自动添加CSS前缀，因此不再需要`-webkit`或其它前缀。
* 通过一个`build`脚本绑定Js、CSS和image到你的产品, 使用 Source map.

**功能设置被有意限制**. 不支持高级功能,例如服务端渲染或者CSS模块. 这写工具是 **不可配置的** 因为当用户可能调整什么时，它很难提供一致的体验和通过一组工具完成更新。

**你可以不用这个.** 从以往经验来看，[逐步采用](https://www.youtube.com/watch?v=BF58ZJ1ZQxY) React很容易. 然而很多人每天匆匆的创建新的React单页面应用. 我们[响亮](https://medium.com/@ericclemmons/javascript-fatigue-48d4011b6fc4)、 [清晰](https://twitter.com/thomasfuchs/status/708675139253174273) 地听到这个处理可能容易出错而且繁琐, 尤其是如果这个是你第一个JavaScript构建的栈.
这个项目是一个试图找出一个好的方法开始开发React应用程序。

### 转换为一个自定义设置

**如果你是一个资深用户** 并且你不满意默认的配置, 你可以使用“eject”工具并且使用它作为模板生成器.

运行 `npm run eject` 正确的拷贝所有配置文件和传递性依赖(Webpack, Babel, ESLint, etc)到你的项目中,如此你可以完全的控制他们. 像`npm start`和`npm run build` 命令让然可以工作, 但是他们指向复制的版本因此你可以操作他们.在这个版本上, 处理的是自己的.

**注意: 这是一个单向操作. 一旦`eject`了, 你不能撤回!**

你不必一直使用`eject`. 这个管理功能设置适合于中小部署, 你不应该感觉有义务使用这个功能. 然而我们知道如果你不能自定义这个工具将不会被使用.

## 局限性

当前有些功能 **不支持**:

* 服务端渲染.
* 一些实验性语法扩展 (e.g. 修饰器).
* CSS 模块.
* 直接导入 LESS 或者 Sass ([但是你仍然可以使用它们](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-css-preprocessor-sass-less-etc)).
* 组件的热更新.

未来可能会添加一些稳定的,对大多数React应用有用的, 不与现有的工具冲突, 并且不需要引入额外配置的功能.

## 内部都有什么？

创建React应用程序使用的工具可能会改变.
目前许多神奇的社区项目基础还比较薄弱,例如:
* [webpack](https://webpack.github.io/) 支持 [webpack-dev-server](https://github.com/webpack/webpack-dev-server), [html-webpack-plugin](https://github.com/ampedandwired/html-webpack-plugin) 支持 [style-loader](https://github.com/webpack/style-loader)
* [Babel](http://babeljs.io/) 支持ES6并使用Facebook的扩展 (JSX, [object spread](https://github.com/sebmarkbage/ecmascript-rest-spread/commits/master), [class properties](https://github.com/jeffmo/es-class-public-fields))
* [Autoprefixer](https://github.com/postcss/autoprefixer)
* [ESLint](http://eslint.org/)
* [Jest](http://facebook.github.io/jest)
* 其他.

他们都提供npm包来传递依赖关系的.

## 贡献

我们很愿意你的帮助来传递 `create-react-app`! 有关我们正在寻找的和如何开始学习的更多信息请看[CONTRIBUTING.md](CONTRIBUTING.md).
## React Native

在寻找一些类似的, 有没有关于React Native的?<br>
请参阅[Create React Native App](https://github.com/react-community/create-react-native-app/).

## 感谢

我们感谢现有相关项目的作者的想法和合作:

* [@eanplatter](https://github.com/eanplatter)
* [@insin](https://github.com/insin)
* [@mxstbr](https://github.com/mxstbr)

## 备选方案

在这个项目里如果你不同意做出选择, 你可能想通过不同的权衡寻找替代品.<br>
下面这些很受欢迎并且被积极维护:

* [insin/nwb](https://github.com/insin/nwb)
* [mozilla-neutrino/neutrino-dev](https://github.com/mozilla-neutrino/neutrino-dev)
* [NYTimes/kyt](https://github.com/NYTimes/kyt)
* [zeit/next.js](https://github.com/zeit/next.js)
* [gatsbyjs/gatsby](https://github.com/gatsbyjs/gatsby)

值得注意的包括:

* [enclave](https://github.com/eanplatter/enclave)
* [motion](https://github.com/motion/motion)
* [quik](https://github.com/satya164/quik)
* [sagui](https://github.com/saguijs/sagui)
* [roc](https://github.com/rocjs/roc)
* [aik](https://github.com/d4rkr00t/aik)
* [react-app](https://github.com/kriasoft/react-app)
* [dev-toolkit](https://github.com/stoikerty/dev-toolkit)
* [tarec](https://github.com/geowarin/tarec)

你可以直接使用像 [webpack](http://webpack.github.io) 和 [Browserify](http://browserify.org/) 模块打包.<br>
React文档包括这个话题的[演示](https://facebook.github.io/react/docs/package-management.html).
