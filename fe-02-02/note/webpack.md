## 模块化

### 问题
1.Es modules 存在环境兼容问题
2.模块化文件过多，网络请求频繁
3.所有的前端资源都是需要模块化的

为了解决上述问题 以及 解决在开发阶段 写的高级代码的兼容性 我们 可以通过webpack 进行打包和兼容

## 模块打包工具

### webpack

模块化打包工具

模块加载器（loader)

代码拆分 code splitting

资源模块

-- 打包工具解决的是前端工程的模块化 而不是js的模块化

### webpack 也是需要loader来支持打包的

按照功能区分一共可以分为三类

1. 编译转换加载器
2. 文件操作
3. 代码检查

在安装webpack插件后 要在webpack.config.js 里面使用他

自动清除 编译目录的插件 -- `yarn i clean-webpack-plugin`

devtool:"source-map" 可以追踪打包后的源码

