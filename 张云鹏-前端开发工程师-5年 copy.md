 <center>
     <h2>张云鹏 </h2> 
     <div style="display: flex; justify-content: center; align-items: center;">
         <span style="display: flex; align-items: center;">
             <img src="assets/phone-solid.svg" width="18px">
             152-2324-6130
         </span>
         &nbsp;
         ·
         &nbsp;
         <span style="display: flex; align-items: center;">
             <img src="assets/weixin.svg" width="20px">
             15223246130
         </span>
         &nbsp;
         ·
         &nbsp;
         <span style="display: flex; align-items: center;">
             <img src="assets/envelope-solid.svg" width="18px">
             314705487@qq.com
         </span>
         &nbsp;
         ·
         &nbsp;
         <span style="display: flex; align-items: center;">
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/claude-hub">claude-hub</a>
         </span>
     </div>
</center>

####  个人信息

 - 男，1997，27岁
 - 求职意向：前端工程师 - 成都
 - 工作经验：5年
 - 求职状态：离职

#### 教育经历

- 学士，重庆理工大学，软件工程专业，2015.9~2019.7

#### 技能清单

- 熟悉 HTML / CSS / JavaScript / TypeScript，熟悉 ES6。
- 熟悉 React、Redux，React-Redux， React-Router、Dva.js，熟悉 React 实现原理，fiber 架构，diff 算法等，从 0 到 1 编写 mini-react。
- 熟悉首屏优化、性能监控、性能优化。
- 熟悉 Webpack、Vite，Eslint，Prettier、lerna 等工程化构建工具。
- 熟悉微前端架构，Iframe、Web Components、single-spa、Webpack Module Federation、qiankun。
- 熟悉 node，能使用 node 开发 cli 工具，以及各种提效小工具。
- 熟悉 gitlab CI/CD。
- 熟练使用 Vue 2.0、3.0， 熟悉 Vue 原理。
- 了解 SSR、Electron、Flutter、uni-app。
- 了解 Java，了解微服务，docker 等。

#### 工作经历

- 神策数据，分析云 - A/B 测试，前端工程师，2021.03.11 ~ 2024.09.14（3.5年）

- 成都聚思力信息技术有限公司，GUI 部门，前端工程师，2019.03.11 ~ 2021.03.11（2年）

#### 项目经历

**神策数据，技术栈 React**

- **A/B Testing**

  **项目描述**

  神策数据是一家提供大数据分析服务的公司，它帮助企业收集、分析并管理用户行为数据。A/B Testing 是神策数据分析工具包中的一个重要功能。

  在 A/B Testing 中，通常会创建两个版本（A版和B版）的网页、应用功能或其他类型的用户体验，并随机将用户分配到这两个版本中之一。这样可以观察并比较哪个版本的表现更好，比如转化率、点击率等关键性能指标。通过这种方式，企业能够基于实际数据来决定哪个版本更优，从而做出更明智的产品决策。

  具体来说，在神策数据的平台上，你可以：

  1. 设计试验：定义要测试的目标页面或功能，以及需要衡量的关键指标。
  2. 创建变体：设计不同的版本，通常一个作为对照组（通常是当前版本），另一个或多个作为试验组（新版本）。
  3. 分配流量：设置如何将用户流量分配给这些不同的版本。
  4. 收集数据：当用户与你的产品互动时，平台会自动收集相关数据。
  5. 分析结果：使用统计方法分析哪个版本的表现更佳。
  6. 做出决策：根据测试结果，选择最佳版本进行全面推广。

  **个人职责**

  A/B Testing 包含 试验管理（编程试验、多链接试验、可视化试验、多人群试验、时间片试验、父子试验）、指标管理、试验层、空白域、调试设备管理、试验配置、试验报告等。从入职到离职，深度参与 A/B Testing 产品开发，技术调研，技术设计等。

  **重难点**
  
  


- **SensD UI  基础 UI 组件库**

  **项目描述**

  基于 Antd 4.18.2 fork 开发，以解决现有业务平台设计体验不一致的问题。该项目旨在替代 Antd 组件，减少因风格差异导致的设计还原难度和补丁代码累积，从而降低维护成本。同时，通过创建自定义组件库，确保向后兼容性，便于新功能的引入和缺陷修复，提升整体开发效率和产品质量。

  **个人职责**
  
  负责开发维护：Select、Tree、Tree Select、Select Panel、Select Transfer 等公共组件。
  
  **重难点**
  
  由于神策设计风格和 Antd 有差异性，开发之初，需要避免对组件原有 api 的影响。维护时，需要向下兼容，避免对业务线造成影响。比如 Select 下拉菜单 新增 全选、取消、确认功能，下拉中可以搜索等。


- **SEF 基础平台框架**

  **项目描述**

  在神策 2021 年平台化战略背景下，主导开发了SEF（Sensors Extendable Frontend），一个基于现有前端技术架构的可拓展微前端架构。SEF 利用 Webpack 5 的 Module Federation 技术实现模块间依赖共享，提供基础架构服务以支持应用级别的可插拔能力，重构了产品信息架构。

  SEF 由两部分组成：@sef/toolchain 和 @sef/runtime。其中，toolchain 是一个基于 Webpack 的交互式项目脚手架，支持 SEF 架构下的调试、编译和发布等功能，确保开发标准化并促进各开发环节的顺畅衔接。runtime 则负责模块的注册和加载，协调 DVA 组件渲染，并提供了路由管理、埋点、Hook系统、异常处理、国际化支持及插件系统等丰富功能。
  
  通过 SEF，我们不仅提升了开发效率，还增强了系统的灵活性和可维护性。
  
  **个人职责**
  
  


- **pig、intl-check、feedi 等提效工具**

  pig：解决循环依赖、影子依赖的扫描工具。

  intl-check：国际化漏翻检查工具。

  feedi：异常诊断工具。解决排查客户线上问题难的情况。 基于这个工具，能够收集到客户使用过程中产生的数据，进行异常问题的分析和诊断。基于 rrweb 拓展开发。



**成都聚思力信息技术有限公司，技术栈 React**

- **STELLR 平台**

  **项目描述**

  STELLR 是对 B 端的在线销售平台，主要为 reseller 提供线上产品的销售服务。整个系统包含: 合同管理，用户管理，消息中心，dashboard，埋点等。项目采用 react，dva，redux，immutable 等。采用分页分包技术，单独部署每个包，减小项目大小。solv-ui 基于 ant design 3.x 版本打造，扩展出符合公司业务的精美组件，solv-models 管理业务逻辑，solv-utils 提供基础方法。

  **个人职责**

  主要负责项目中的用户管理模块，合同管理，dashboard 等，参与前端组件规范讨论、组件开发，收集组件场景等。

  **重难点**
  
  负责大文件上传的封装，采用分片上传，断点续传，秒传，超时重试等技术，解决上传相关的一系列问题。



**个人项目，技术栈 Vue**

- qx-admin-web

  使用 vue 2.0、vuex、vue-router、element-ui，实现后台管理系统。包含 登录注册、导航、权限管理、代码生成等。

