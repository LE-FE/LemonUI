

# LemonUI 🍋 

我吃柠檬,总的来说就是一个UI组件库, 本人想把自己写的一些通用组件给放在这个上面 

## 文档 
这次用的实时预览工具叫做 story book , 可以集合一些插件来完成实施预览,即展示源码等等的一个工具 

[文档地址](http://39.106.123.79/)





说一说接下来的步骤

**steps**

1. 完成整体项目的结构以及构建配置(不包括一些高级配置,如按需加载等...)
2. 完成一些较为简单的基础组件
3. 完成功能比较复杂的组件 
4. 慢慢的完善这个Vue 组件库 
5. Complate ( 4 - 5 一直徘徊 )



## 项目说明 

这个项目用 Vue2.x 来进行基础框架, 构建配置是采用的 webpack4.x 和 babel 来进行构建 等等 , 因为刚刚开始 主要还是得慢慢完善, 希望自己也能坚持下去 !!! 


## 运行 
1. test  ( 采用的 jest 测试框架如果要编写测试的话,请进入组件文件夹里面来进行编写)
2. build ( 这里会进行构建, 然后采用umd的方式, 会将各组件给整合至一个入口文件中,使用的话应该是常用方式都支持 Vue.use , 或者 CDN 等等 )
3. 进行打包分析 
4. storybook  进行预览  
5. build-storybook 进行预览文档构建




## 关于构建配置
如果要去更改构建配置,请自行去更改build 目录中的webpack构建配置文件 , 但是有些变量配置在 config 目录中!请自行去寻找



## 关于引用
当前没有存放至 Npm 中, 也只供本人学习,练习作用 ,在本地上 npm link 这个项目, 本人测试成功的 

main.js中  
```javascript
import LemonUI from 'ui-lemon' ; 
import 'ui-lemon/dist/index.css';
Vue.use(LemonUI) 
```
以上使用即可,与ElementUI相同 


## 20-7-15
希望能更加了解完善单元测试,希望能整合出一种方案



## 将要处理 
1. submenu 垂直组件的 open / close 样式 
2. submenu 水平组件的基本使用


## 所有弹框式组件进行延后
1. Dialog 


## 未开发功能
1. upload 的上传列表组件 

## npm link 
[UI-LEMON](https://www.npmjs.com/package/ui-lemon)




























