

# LemonUI 🍋 

我吃柠檬,总的来说就是一个UI组件库, 本人想把自己写的一些通用组件给放在这个上面 



说一说接下来的步骤

**steps**

1. 完成整体项目的结构以及构建配置(不包括一些高级配置,如按需加载等...)
2. 完成一些较为简单的基础组件
3. 完成功能比较复杂的组件 
4. 慢慢的完善这个Vue 组件库 
5. Complate ( 4 - 5 一直徘徊 )



## 项目说明 

这个项目用 Vue2.x 来进行基础框架, 构建配置是采用的 webpack4.x 和 babel 来进行构建 等等 , 因为刚刚开始 主要还是得慢慢完善, 希望自己也能坚持下去 !!! 



## preview 

![](https://github.com/xiangxinji/LemonUI/tree/master/images/v1.png)



# 运行 

在这个项目中目前只有三种功能 , test ,build , dev , 我们来一个一个进行说明 

1.  test  ( 采用的 jest 测试框架, 如果有些同学觉普通使用webpack 继承jest 测试比较麻烦的话,可以clone 一下这个库来进行学习 , 如果要编写测试的话,请进入组件文件夹里面来进行编写)
2. build ( 这里会进行构建, 然后采用umd的方式, 会将各组件给整合至一个入口文件中,使用的话应该是常用方式都支持 Vue.use , 或者 CDN 等等 )
3. dev (因为我也不太清楚到底如何更好更快的进行视觉展现, 就单独写了另外一个配置来进行SPA 的预览, 这里直接去App.vue 中将你要预览的组件给显示上去就行了)



## 关于构建配置

如果要去更改构建配置,请自行去更改build 目录中的webpack构建配置文件 , 但是有些变量配置在 config 目录中!请自行去寻找



## 关于引用

当前没有存放至 Npm 中, 也只供本人学习,练习作用 ,在本地上 npm link 这个项目, 本人测试成功的 

main.js中  
```javascript
import LemonUI from 'lemon-ui' ; 
import 'lemon-ui/dist/index.css';
Vue.use(LemonUI) 
```
以上使用即可,与ElementUI相同 



## 20-7-15
希望能更加了解完善单元测试,希望能整合出一种方案



## List 🚦

status : 0  未完成, 1 即将完成 , 3 完成 , 4 追加中 , 5 修复中    

| 组件名 | 描述   | 状态 |
| ------ | ------ | ---- |
| Link   | 链接   | 1    |
| Button | 按钮   | 1    |
| Input  | 输入框 | 0    |
| Icon  | 图标 | 1    |
| Alert  | 弹框 | 0    |
| NavMenu  | 导航 | 0    |
| Tabs  | 标签页 | 0    |
| Tag  | 标签 | 0    |
| Switch | 开关 | 1 |






















