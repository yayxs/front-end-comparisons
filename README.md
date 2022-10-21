|   主类别   | 子类别 |       A       |                         B                          |C|
| :--------: | :----: | :-----------: | :------------------------------------------------: |:--:|
| JavaScript |  ES6   | let vs const |                       代码块                       ||
|     ^      |   ^    |       ^       |                  for 循环的计数器                  ||
|     ^      |   ^    |       ^       |                    变量提升现象                    ||
|     ^      |   ^    |       ^       |      暂时性死区 temporal dead zone，简称 TDZ       ||
|     ^      |   ^    |       ^       |               作用域：全局 函数 块级               ||
|     ^      |   ^    |       ^       | 声明变量的方法 var function let const import class ||
|     ^      |   ^    |     async     |                 谈谈`ES2017`中的`async` 函数         |    《ECMAScript 6 教程》    |
|     ^      |   ^    |     ^     |                 async函数对 Generator 函数的改进之处体现在              |   《ECMAScript 6 教程》|
|     ^      |   ^    |     ^     |                 async 函数的实现原理              |   《ECMAScript 6 教程》|
|     ^      |   ^    |     class     |                 constructor() 方法                 ||
|     ^      |   ^    |       ^       |               extends 关键字实现继承               ||
|     ^      |   ^    |       ^       |      为什么子类的构造函数，一定要调用 super()      ||
|     ^      |   ^    |       ^       |          ES6 的继承机制与 ES5 的继承机制           ||

### 记录一次面试官

考察点 （部分关键词）
主要考察 候选人 前端相关的专业技能 
- HTML
  - 了解html的文档模型吗 
    - <!DOCTYPE html>  不了解
    - 几种模式 浏览器标准模式 (standards mode) 、几乎标准模式（almost standards mode）和怪异模式 (quirks mode) 之间的区别是什么？ 不了解
    - Src 下载完毕 onload un
    - Doctype 做什么用的
  -  <script>、<script async> 和 <script defer> 的区别 
    - 标签上的属性 记得吗
      - 有src 
      - 还有什么 type async 作用是什么
    - 差异是什么
  - html5 新增了哪些内容
    - ans 音视频 video audio 定位 地址定位 websoctet 表单空间 存储 canvas 
    - 语义化的标签 路径 control
    - Video 标签的属性
      -  不了解 
    - 浏览器存储的异同
    - Vuex 公共的 里边
      - Vuex token  延伸问题
  - 使用 data- 属性的好处是什么
  - \“attribute” 和 “property” 的区别是什么？
  - 页面生命周期：DOMContentLoaded，load，beforeunload，unload
  - 标签相关：
    - Img 的所有属性 srcset 
      - Src 访问地址异常
    - Src href 的区别
    - 行内元素 块级元素
- CSS + CSS3
  - css重置问题 ：reset 和 normalizing
    - Ans 全局样式统一一下 去除一下 
  - 选择器有哪些 优先级怎么计算的
    - Ans 选择器的 群组选择器 兄弟选择器 后代选择器 伪类选择
    - 伪类和伪元素有什么区别
  - css3 弹性盒子 动画 新增了圆角边框 选择器 阴影渐变 过渡 媒体查询
    - 样式比较简单 点击动画 
    - 简单一点的 难一点的
    - transition 据中华
    - Transform 是做什么的
  - 居中 
    - Margin auto 怎么实现居中的
  - 盒模型
    - Border-box 几个值 
  - 清除浮动
  - BFC 块级BFC 
  - 高度坍塌 
  - Css的单位 
  - css的颜色
  - css的预处理器 
  - Vue 的scoped
  - 盒模型
  - Display 的值
  -  CSS 动画和 JavaScript 动画的优缺点
  - 媒体查询 
  - 定位相关
  - css3 布局
    - 居中 p
- JS + ES6
  - 怎么理解JS的
    - 代码的注入灵魂
  - 你所了解的JS
    - 宿主环境啊等等 
  - 变量
  - 怎么理解ES6
    - Const let var class 类 模块字符串 箭头函数
    - 不会挂载到window 暂时性死区 
    - 构造函数和普通函数的区别 
      - New 具体做了什么
      - es6的理解 新增的内容
      - 你怎么理解前端的模块化
        - module.exports = { }
  - 数据类型
    基本的类型 复杂的类型
    -  === == null undefined 判断是数组啊等等
  - 几种循环的方式 有什么不同 怎么终止循环 遍历对象 遍历数组
  - 事件代理
  - js中的this
  - es6参考阮老师
  - 解释 Ajax 的工作原理
  - 事件循环 (event loop)
  - 继承
  - Call apply 
  - 你对promise 
    - 状态
    - 过程
- 浏览器
  - 浏览器存储的不同
  - 输入 URL 到整个网页加载完毕及显示在屏幕上的整个流程
  - 重绘回流
- 主框架 VUE
  - 什么时候接触到的vue 怎么学习的 完整的vue文档有没有读过
- 主UI
  - 有没有看过 elementui 的源码
  - Vue 的理解 双向数据绑定
- 技术生态：
  - 移动H5的适配
  - 微信小程序 uniapp 的开发遇到的问题
- 工具相关
  - 工作流 git 
  - 构建webpack 模块化 
- 做自己的业务
  - 
- 扩展
  - 前端发展很快，怎么保持学习
    - 读过哪些前端相关的书籍，包括不限于JS ,对你的技术有哪些帮助
    - 有没有博客，有结识社区里一些前辈吗，对你的前端认知有哪些提升
    -  对vue最新的生态，有哪些关注，有没有尝试应用在项目中，或者工作之余有没有自己写过案例demo
  - 业务棘手问题
    - 有没有遇到过，场景是什么，是怎么处理的
    - 技术挑战怎么解决的
  - 协作问题
    - 如果你参与到一个项目中，发现他们使用 Tab 来缩进代码，但是你喜欢空格，你会怎么做