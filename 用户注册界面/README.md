# 第二次作业：用户注册页面
## 作业内容
实现HTML5用户注册页面，综合练习表单、表格、列表、语义化标签。

## 使用主要标签
1. 语义标签：header、main、footer
2. 表单：form、input(text/password/radio/checkbox/file/email/tel/date)、select、option、textarea、button、label
3. 表格：table、thead、tbody、tr、th、td，使用colspan合并单元格
4. 列表：ul无序列表、ol有序列表、dl定义列表
5. JS：监听表单submit事件，控制台输出表单FormData数据

## 遇到的困难及解决方法
1. 问题：label不会两种写法，点击单选框文字不能选中；
解决：学会两种关联方式：①label的for属性绑定input的id；②label直接包裹input标签。

2. 问题：表单提交页面直接跳转，看不到控制台打印；
解决：js中使用 e.preventDefault()阻止表单默认提交跳转。

3. 问题：手机号正则pattern不生效；
解决：确认input type="tel"，pattern="[0-9]{11}"写完整。

4. 问题：忘记写name属性，表单无法收集对应字段；
解决：每一个需要提交的表单控件都加上name属性。
