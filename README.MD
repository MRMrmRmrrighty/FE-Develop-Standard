# 前端开发规范
1. 方法必须添加注释
2. 减少或避免使用行内样式
3. 减少或避免使用`!important`
4. 样式建议使用scoped+全局的形式，私有样式写在scoped内
5. 文档单行长度避免过长，尽量保持在100个字符以内
6. 模板数据尽量抽离到单个文件后`import`引入，也可以通过局部组件注册`extend`实现
7. boolean类型的变量请以`is`开头，如`isVideoShow`
8. css属性书写顺序, 建议遵循 布局定位属性-->自身属性-->文本属性-->其他属性
9. css3的相关属性使用时要提前考虑兼容性问题
10. css使用伪类时，重定义的最先，伪类其次，自定义最后
11. 引入时保证绝对路径文件在相对文件之前
12. 使用对象属性之前一定要先判断该对象及属性是否存在
####页面命名规范：

(1)页面结构
```
  容器: container
  页头：header
  内容：content/container
  页面主体：main
  页尾：footer
  导航：nav
  侧栏：sidebar
  栏目：column
  页面外围控制整体布局宽度：wrapper
  左右中：left right center
  ```
(2)导航
```
  导航：nav
  主导航：mainbav
  子导航：subnav
  顶导航：topnav
  边导航：sidebar
  左导航：leftsidebar
  右导航：rightsidebar
  菜单：menu
  子菜单：submenu
  标题: title
```
