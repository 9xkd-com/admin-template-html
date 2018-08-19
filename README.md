## 侠课岛后台Uikit
基于PHP/Yii2的通用后台UI工具包，仅关注UI层面，无过多业务逻辑，只需传入数据，即可快速实现常用功能；计划基于Composer封装，基于PHP/Yii2来快速引入调用UI资源，方便框架升级和扩展。
## 我们的思考：
1. 不造轮子，在市面主流的UI框架基础上，再进行组装，使得网站后台更加快速的成型；
2. 改善传统重前台，轻后台管理的体验，尽可能的提升管理人员的使用体验；我们使用过大量的后台管理系统，发现只有微信小程序管理面板的管理操作是最舒服、最清晰易用的，所以，我们将参考微信小程序的管理面板来做这个后台模板；
3. 后台使用前端为核心渲染的架构方案，体验虽然很好，但是工作量却是成倍的加大，所以，为加快后台开发，后台的前端都是以后端为主渲染，然后我们尽可能的加入主流的Vue、Webpack、ES6等前端技术来加速前端开发，通过PHP/YII2封装成方便重用的组件，需要按照规范引入UI代码，传入数据，马上就可以呈现出强大的功能界面，同时我们想在这个PHP/Yii2版本成熟后如果有精力再推出基于Laravel、Python、Node.js等框架/语言封装好的后台UI模板，让后台开发更方便快速。
## 关于开发
1. 后台一般为内部的管理人员使用，所以开发主要以PC的Chrome/Safari为测试浏览器，不会考虑IE之类的浏览器；
2. 初定使用Semantic UI+Bootstrap 4，外加各种开源的第三方小功能部件。之前备选基于如下框架：Ant Design、Uikit、layui、飞冰、iView、Element等来进行二次开发，由于都以前端渲染为主，加重后端人员使用成本，暂不使用。
## 界面大概长这样
![侠课岛后台Uikit](xkd.jpg)
