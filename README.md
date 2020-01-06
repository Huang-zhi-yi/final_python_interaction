# 2019第一学期python交互项目
### [pythonanywhere页面](http://xintaolee.pythonanywhere.com/)
### 基本介绍：
* 网页有7个URl：endpoint分别是 / 、/world、/world_hbl、/world_death_person、/world_lung、/tobacco、/field
## 后端
1. 使用if、elif的条件判断语句以打开不同的图表文件功能
2. 使用for循环，遍历含有复杂数据的嵌套列表，并返回一个表格
3. 使用with语句和open()函数以打开图表文件
4. 使用csv模块并利用csv.reader()函数读取csv文件，利用.readlines()函数读取html文件
5. 使用python内置函数list()使csv文件转化为嵌套列表
6. 使用flask模块的request.form()接受前端页面传来的表单数据，render_template()函数返回一个HTML页面和页面标题、表格数据
7. 引用了pandas、pyecharts、prettytable第三方模块
8. 利用''.join()函数把列表转化为字符串
9. 使用下拉框功能可以实现在同一个url下查看不同的表
## 前端
1. 使用了flask框架和jinji2模板，通过extends指令实现模板继承，实现了python后端与前端页面分离
2. 使用了boostrap前端框架的按钮、网格系统、导航栏下拉框和轮播图
3. 使用了jQuery的Javascript库实现下拉框功能
4. 使用了css3过渡效果实现页面右边插件
5. 使用font-awesome的字体图标库
6. HTML新语义元素使用
     * td、tr、th等表格元素渲染嵌套列表
     * 使用\<section>块级元素使代码分层、\<nav>实现顶部导航栏、\<h1>-\<h6>元素使网页标题字体大小改变
     * 使用\<i>元素添加字体图标、使用\<b>元素为一些文字加粗
7. 利用HTMl5优点，在\<a>标签中放入多个元素
8. 利用css3实现响应式网页 
9. 在index.html页面使用了多个\<form>标签，发送表单数据到python后端

##	HTML档描述(更详细的注释已写在每个html档里)
* index.html是“基文档”所有html页面的都是基于此拓展的
* field.html
* base.html是“基模板”所有html页面的都是基于此继承的
* result2.html
* tabacco.html

## Python档描述(webapp.py档中每个函数每一行代码都给出了注释，请移步到webapp.py档查看)
* webapp.py
## Web App动作描述(webapp.py档中每个函数每一行代码都给出了注释，请移步到webapp.py档查看)
