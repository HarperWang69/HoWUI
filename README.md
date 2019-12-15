# 基于react + TS 封装的UI组件库

### 介绍

- 基于 ts 搭建的用于将项目封装的插件发布 npm 的模版。
- 其内置了静态服务 测试用例 和 持续集成。
- 先进行本地开发，确认功能和测试全部通过后再发布到 npm。

### 目录相关

- doc 相关文档
- example 本地开发相关目录 本地开发测试的目录。 注：其中引用的组件来自于根目录的 src 中的组件
- src 编写将要发布的插件目录 注：该目录用于编写将要发布的组件
- lib 最终打包后的目录，用于发布到 npm

### 相关命令

- npm run start 启动本地服务开发
- npm run build 是根据根目录的 tsconfig.json 文件来执行 tsx 解析并最终打包到根目录的 lib/文件夹内
- npm run lint 运行 tslint 检测代码格式问题
- npm run test 运行 Jest 进行代码测试 测试用例在/src/test/目录中 以 xxx.test.tsx 命名
- npm login 登录 npm（没有的话就去注册一个）
- npm publish 推送的代码到 npm

