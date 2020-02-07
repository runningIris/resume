## 个人信息

- 个人信息: 冯嘉慧/女/1994
- 期望职位：前端开发工程师
- 工作年限：2 年
- 毕业院校：本科/广东外语外贸大学/英文学院/英美文学专业 2017 届
- 英语水平: 专业八级
- Github：https://github.com/runningiris

## 工作经历

金山软件有限公司 - 西山居工作室 - Web 研发中心 前端开发工程师 ( 2017 年 3 月 ~ 2017 年 6 月)

### 专题业务类开发

在职期间负责了近 40 个专题活动的前端工作，其中一半以上是 H5 功能类，以下是三个比较典型的项目经历

#### React H5 功能类: 剑侠世界 2 手游传功专题(2018.11.1 -- 2018.11.8)
- 项目描述: 微信好友
- 技术选型: react, redux, react-router,ant-design
- 专题功能: 单页面应用, 微信授权, 微信自定义分享, 判断页面状态(路由), 帮好友助力, 给自己加分, 自动跟新数据

#### jQuery 功能类: 剑网 3 大美江湖 PC 端活动专题 (2017.12.17 -- 2017.12.23)

- 项目描述: 功能包括选项卡, 列表分页, 活动进度条, canvas 动画植入(createJS), 关键词搜索, 注册登录, 配合后台七牛图片上传, 点赞, 领奖, 微博自定义分享等。页面功能多, 页面多, 开发周期短(不足一周时间)。

- 工作分配: 我负责项目全部的前端工作

- 遇到的棘手问题：列表内容页用户一刷新页面, 就会丢失当前选中的选项卡以及页码状态。

- 已解决, 思路如下:
    - 创建一个全局对象并使用 Object.defineProperties 来定义对象属性(处理属性描述符的 getter 和 setter), 处理页面数据, 使 url/数据/页面展示三者处于互相绑定的状态 (有点像)
    - 手动写了基于 window.location.hash 的路由器, 实现页面无刷新跳转, 以及从 url 中获取数据的功能。

#### jQuery 展示类: 剑网 3 外观月销专题
- 项目描述: 用于展示剑网 3 每月新出的外观, 功能包括, 点开查看大图, 轮播图, 选项卡, 视差动画, 飘花飘叶子等

### React 业务通用组件开发

1. 注册登录组件 -- 提供日常开发专题使用, 适配性好，可以纯 react, 或者配合 redux, dva, mobx 等状态处理器使用

2. 移动端表单组件 -- 根据 Ant-Design 进行二次封装的一系列常用表单组件
   - Input 输入框: 封装了错误处理机制及常见的验证规则
   - 短信验证组件(点击获取短信验证码并倒数读秒)
   - 游戏区服角色名联动选择组件
   - 省市区地址选择组件
   - 图片上传组件(配合七牛上传使用)

## 知识技能

能快速熟练地制作前端页面

- JavaScript 基础知识:
    - 掌握 Typescript, ES6+ 语法, promise
    - 理解面向对象编程思维、函数式编程思维

- 前端框架:

    - React 全家桶: 在实际项目中熟练使用
        - UI库: ant-design
        - 状态管理: Redux, dva
        - 路由: react-router

    - jQuery 库:
        - 能在实际项目中熟练使用 jQuery 及其各种插件(swiper 轮播图, 视差动效, lightbox, 视频播放等)
        - 读过最外层的代码: 了解 jQuery 的防冲突机制, 理解 jQuery 对象本身的构造及其原型链的扩展

    - 了解 Vue, 可快速上手

- 代码管理工具: 熟练使用 git 进行协同开发, 对线上和本地分支进行操作, 解决冲突等

- 前端工具:
    - 了解 Webpack 如何打包处理项目, 如何处理文件模块
    - 了解 Babel 如何进行语法降级
    - 平时能使用 node.js 写小工具来处理重复性工作，提高开发效率

- 计算机基础:
    - 算法: 学习过排序
    - 数据结构: 学习过数组, 链表, 栈, 队列, 优先队列, 二叉树(平衡查找树, 2-3 树, 红黑树), 散列表等;
    - 计算机网络知识:
        - 能读懂请求/响应报文的内容
        - 了解各阶段缓存/各种状态码的含义
        - 理解网络传输的大致过程
    - 会 c++/java/python 的简单语法
