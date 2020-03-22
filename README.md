# 自定义导航栏

1. 创建自定义组件，使用 easyCom 的方式使用组件，这种方式的好处就是，组件可以直接 使用，不需要安装、引用、使用三个步骤，而且只有使用到的组件才会编译到项目中 [更多文档参考](https://uniapp.dcloud.io/collocation/pages?id=easycom)

2. 对于自定义导航栏，可以使用一个占位元素，是内容可以显示在正常的地方

3. h5 是没有状态栏的 ，所以在h5中不应该加上状态栏的高度 

4. 在 uni.scss 中去定义全局公用的颜色变量，方便我们在项目中批量使用
