[简体中文](#)

# debug-for-sdk

<p><p/>
<h1>基于嘉立创EDA专业版开发工具构建的新版EDA调试专用开发工具</h1>
<p><p/>
<a href="https://github.com/easyeda/pro-api-sdk" style="vertical-align: inherit;" target="_blank"><img src="https://img.shields.io/github/stars/easyeda/pro-api-sdk" alt="GitHub Repo Stars" class="not-medium-zoom-image" style="display: inline; vertical-align: inherit;" /></a>&nbsp;<a href="https://github.com/easyeda/pro-api-sdk/issues" style="vertical-align: inherit;" target="_blank"><img src="https://img.shields.io/github/issues/easyeda/pro-api-sdk" alt="GitHub Issues" class="not-medium-zoom-image" style="display: inline; vertical-align: inherit;" /></a>&nbsp;<a href="https://github.com/easyeda/pro-api-sdk" style="vertical-align: inherit;" target="_blank"><img src="https://img.shields.io/github/repo-size/easyeda/pro-api-sdk" alt="GitHub Repo Size" class="not-medium-zoom-image" style="display: inline; vertical-align: inherit;" /></a>&nbsp;<a href="https://choosealicense.com/licenses/apache-2.0/" style="vertical-align: inherit;" target="_blank"><img src="https://img.shields.io/github/license/easyeda/pro-api-sdk" alt="GitHub License" class="not-medium-zoom-image" style="display: inline; vertical-align: inherit;" /></a>&nbsp;<a href="https://www.npmjs.com/package/@jlceda/pro-api-types" style="vertical-align: inherit;" target="_blank"><img src="https://img.shields.io/npm/v/%40jlceda%2Fpro-api-types?label=pro-api-types" alt="NPM Version" class="not-medium-zoom-image" style="display: inline; vertical-align: inherit;" /></a>&nbsp;<a href="https://www.npmjs.com/package/@jlceda/pro-api-types" style="vertical-align: inherit;" target="_blank"><img src="https://img.shields.io/npm/d18m/%40jlceda%2Fpro-api-types" alt="NPM Downloads" class="not-medium-zoom-image" style="display: inline; vertical-align: inherit;" /></a>
<h2>我们的目标是</h>
<p><p/>
<image src="images/Title.png" alt="logo" width="300" height="100"> <image src="images/Title.png" alt="logo" width="300" height="100">

<p><p/>
<h3>支持多文件加载<h3/>
<image src="images/MoreCode.png"  width="500" height="200">
<h3>支持从云端拉取代码<h3/>
<image src="images/ServerCode.png" width="500" height="200">
<p><p/>

> 详细开发文档请访问：[https://prodocs.lceda.cn/cn/api/guide/](https://prodocs.lceda.cn/cn/api/guide/)

## 进入开发

本开发工具组包含了用于开发 [嘉立创EDA专业版](https://pro.lceda.cn/) 扩展包的所有环境和工具，并内置了 Prettier 和 ESLint 的推荐规则。
除此之外，内置了一个专业的debug工具，用于插件部分代码的快速测试

1. 克隆 [eda-debug-tool](https://github.com/JamAnNa/EDA-Extern-debug-tool) 项目仓库到本地

    Gitee:

    ```shell
    git clone --depth=1 国内暂无仓库
    ```

    GitHub:

    ```shell
    git clone --depth=1 https://github.com/JamAnNa/EDA-Extern-debug-tool
    ```

2. 初始化开发环境（安装依赖）

    ```shell
    npm install
    ```

3. 进行些许变更 ...
   在iframe中编辑你的页面和代码，然后在src/index.ts中调用eda.sys_IFrame.openIFrame("iframe/dev/index.html")以查看你的页面

4. 编译扩展包

    ```shell
    npm run build
    ```

5. 在 嘉立创EDA专业版 中安装生成在 `./build/dist/` 下的扩展包

## 开源许可

<a href="https://choosealicense.com/licenses/apache-2.0/" style="vertical-align: inherit;" target="_blank"><img src="https://img.shields.io/github/license/easyeda/pro-api-sdk" alt="GitHub License" class="not-medium-zoom-image" style="display: inline; vertical-align: inherit;" /></a>

本开发工具组使用 [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/) 开源许可协议，你仅可以将 **嘉立创EDA**、**EasyEDA** 商标信息用于依托于本工具组开发的扩展包的 **功能描述部分** 和 **开源发布的标题部分**。
