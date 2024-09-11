<center>
	<h2>张云鹏</h2> 
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="16px">
             152-2324-6130
         </span>
         ·
         <span>
             <img src="assets/weixin.svg" width="18px">
             15223246130
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="16px">
             314705487@qq.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="16px">
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

- 本科，重庆理工大学，软件工程专业，2015.9 ~ 2019.7

#### 技能清单

- 熟练掌握前端开发技术（HTML5 、CSS3、 JavaScript 、TypeScript、 ES6等）
- 深入理解 React 及相关生态，熟悉 React 实现原理，从 0 到 1 编写 mini-react，实现 fiber 架构，diff 算法等
- 熟悉 Vue 2.0、3.0 全家桶及底层原理
- 对前端工程化有深入理解及实践，熟悉 Webpack、Vite，Eslint、lerna 等工程化构建工具
- 对浏览器渲染原理、性能监控、页面性能优化、用户体验及可访问性有深入了解及实践
- 掌握计算机网络原理，对前端网络安全、前端网络监控优化有一定研究
- 深入研究微前端 Webpack Module Federation、qiankun 实现原理，有微前端实践经验
- 熟练使用 node，开发 cli 工具，以及各种提效小工具（循环依赖检查、中文漏翻）
- 了解 SSR、Electron、Flutter、uni-app

#### 工作经历

神策网络科技有限公司，分析云 - A/B 测试，前端工程师，2021.03.11 ~ 2024.09.14

- 负责 A/B 测试系统的开发、公共组件开发，参与前端基础框架、CI/CD、工程化建设
- 围绕前端技术债、业务痛点方向，基于前端工程化全链路对系统进行持续的技术迭代优化，利用技术产生更大的业务价值

成都聚思力信息技术有限公司，GUI 部门，前端工程师，2019.03.11 ~ 2021.03.11

- 负责 To B 在线销售平台开发，公共组件规范制定等

#### 项目经历

**神策数据**

- **SEF 基础平台框架（2021 ~ 2024）**

  **项目描述**

  在 2021 年公司平台化战略下，神策大前端主导开发 SEF（Sensors Extendable Frontend），基于 Webpack 5 Module Federation 的微前端架构，设计并实现了 SEF 的 toolchain 和 runtime 两部分，支持模块间的依赖共享及插拔式应用服务。通过 SEF 提升开发效率，增强系统灵活性与可维护性。

  **个人职责**

  - 主导开发设计 toolchain 接入 monorepo，并完成 cli template 生成。



在神策 2021 年平台化战略背景下，主导开发了SEF（Sensors Extendable Frontend），一个基于现有前端技术架构的可拓展微前端架构。SEF 利用 Webpack 5 的 Module Federation 技术实现模块间依赖共享，提供基础架构服务以支持应用级别的可插拔能力，重构了产品信息架构。

SEF 由两部分组成：@sef/toolchain 和 @sef/runtime。其中，toolchain 是一个基于 Webpack 的交互式项目脚手架，支持 SEF 架构下的调试、编译和发布等功能，确保开发标准化并促进各开发环节的顺畅衔接。runtime 则负责模块的注册和加载，协调 DVA 组件渲染，并提供了路由管理、埋点、Hook系统、异常处理、国际化支持及插件系统等丰富功能。

通过 SEF，我们不仅提升了开发效率，还增强了系统的灵活性和可维护性。

**个人职责**

- **A/B Testing**

  **项目描述**

  利用神策数据的 A/B 测试功能，对比分析不同版本的用户体验效果。通过对关键性能指标（如转化率、点击率）的数据收集与分析，为企业提供优化产品决策的支持。

  **个人职责**

  - 

  A/B Testing 包含 试验管理（编程试验、多链接试验、可视化试验、多人群试验、时间片试验、父子试验）、指标管理、试验层、空白域、调试设备管理、试验配置、试验报告等。从入职到离职，深度参与 A/B Testing 产品开发，技术调研，技术设计等。
  
  **重难点**
  
  


- **SensD UI  基础 UI 组件库**

  **项目描述**

  基于 Antd 4.18.2 fork 开发，以解决现有业务平台设计体验不一致的问题。该项目旨在替代 Antd 组件，减少因风格差异导致的设计还原难度和补丁代码累积，从而降低维护成本。同时，通过创建自定义组件库，确保向后兼容性，便于新功能的引入和缺陷修复，提升整体开发效率和产品质量。

  **个人职责**
  
  负责开发维护：Select、Tree、Tree Select、Select Panel、Select Transfer 等公共组件。
  
  **重难点**
  
  由于神策设计风格和 Antd 有差异性，开发之初，需要避免对组件原有 api 的影响。维护时，需要向下兼容，避免对业务线造成影响。比如 Select 下拉菜单 新增 全选、取消、确认功能，下拉中可以搜索等。




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

- admin-web

  使用 vue 2.0、vuex、vue-router、element-ui，实现后台管理系统。包含 登录注册、导航、权限管理、代码生成等。

