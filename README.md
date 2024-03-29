<h2> -纵横小说数据可视化项目组-</h2>
【姓名：陈荣；学号：181013051】

***

>> 项目目标实现方式：从纵横中文网爬取排行榜数据，收集自2014年至2019年每月的榜单信息和作者收入信息—>运用flask框架实现各项交互，在web页面展现数据表和数据故事—>实现pythonanywhere部署和github上传


*部署的网页打开后可能需要一定时间加载，稍稍等待，将看到我们所做的完整页面* 🐌

<h3> 为实现网页可视化所作贡献🖥️：</h3>

- **主页** 
   + [点击查看主页home](http://chro.pythonanywhere.com/)
   + css样式设置：背景为颜色渐变；banner设置为轮播图；整体为响应式页面
   + 页面交互：使用三个蓝按钮，点击跳转至数据表或项目故事的页面
   
   
- **数据表页面**
   1.   + [“纵横数据汇总”](http://chro.pythonanywhere.com/data_sheet) （1份数据表）
        + [“历年数据查询”](http://chro.pythonanywhere.com/four) （6份年数据表） 
        + [“作家收入”](http://chro.pythonanywhere.com/income) （1份数据表）
      
   2. css样式设置：蓝色线格+鼠标悬浮至字体时颜色加深

   3. 页面功能：
      + 总表：左上角两个下拉框提供页面跳转+右上角搜索框+支持复制打印数据
      + 年份数据：左上角的返回按钮+右上角搜索框+支持复制打印数据


- **项目故事** [“纵横小说月票榜”+“作家收入分析”]
   1. [受欢迎的小说类型](http://chro.pythonanywhere.com/chart)
   2. [作家排榜](http://chro.pythonanywhere.com/2)


<h3>为前后端交互过程所作贡献🖥️：</h3>

   + 将数据excel表转化为csv文件，调整为utf-8格式，最后转换成html，形成数据表；
   
   + 增加页面样式css，部分页面部署js调整行为；*（此部分负责主页面home和数据表）*
   
   + 在flask框架的py文件中，调用函数和数据结构将调整好的HTML代入路径，尝试实现html的可视化网页；*（此部分主要为小组合作，并非所有都为个人完成）*
   
   + 实现项目web展现后，通过“下拉框“和“按钮”实现多个界面的跳转。


<h3>在pythonanywhere上实现部署🖥️: </h3>

   + 文件上传：安装git，将项目文件上传到github；从pythonanywhere中导入github中的文件
   
   + 实现部署：借助Bash Consoles执行命令，进入该项目文件—>创建虚拟环境—>安装模块，再根据报错调整绝对URL。

***
想要了解更多详细，到[Github-fiction](https://github.com/ChenRongnfu/fiction) 中查看更多代码😃
