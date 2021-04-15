# Dragable-Components-Demo

实现通过拖拽组件来生成功能页面。类似于[GrapesJS](https://grapesjs.com/)这样的功能。

## Functions

主要实现功能点如下：

- 编辑器
- 自定义组件
- 拖拽

## Specification

- [Element UI](https://element.eleme.io/#/zh-CN)
- Vue(2.x) + Vuex + Vue Router
- Typescript
- less

## Build Setup

Requires Node.js 6+

## Prepare to run in local environment

- yarn install dependencies / npm install
- yarn serve / npm run serve
- visit http://localhost:8080/

## Others

- 在项目中加入了[Cypress V6.6.0](https://www.cypress.io/)进行端到端的自动化测试
- 启动Cypress自动化测试: npm run cypress / yarn cypress
- 所有的测试用例都位于根目录下面的<code>cypress</code>文件夹下面
- 如需要自动化测试的视频录制，请使用`npm run cy:video`,成功之后保存在`cypress/videos/`文件夹之下

