# Lesson08 工作任务，开发《UOLab联合实验开发系统》项目原型界面
1. 提供模板
2. 该模板
3. 一个假期开发
4. 验收
## 对未来
1. Java web，ssm框架，Java研发工程师
# Lesson07  
## 一，JS表单验证
公司开发中，要使用正则表达式、JS函数，DOM

# Lesson06
## 一、JavaScript 
1. 对于Java研发工程师，JS是必须的，要熟练开发
2. Web开发要深入、精通
## 二，js是什么？
脚本语言，运行在浏览器中，不同浏览器的支持程度不同，运行浏览器的兼容性测试，不是W3C制定的标准
## 六、上网过程，代码执行情况
1. B/S 结构：Brower/server结构 教务系统
2. C/S结构：Client/Server结构  qq
3. 单机软件  word
## 七.JS学习提醒
1.JS调试比较麻烦，要用到Chorme或者FireFox的控制台
## 八.JS学习重点
1. 语法
2. 函数
3. 事件
4. 正则表达式与表单验证
5. DOM
## 十.JS的输出  便于调试代码
1. alert()
2. console.log();
- 补充：JS代码可以放在   1.网页内部  2.单独的文件中
## 十一、JS语法	
1. JS是弱类型语言
2. 严格区分大小写
3. JS中变量定义可以用var也可以不用
4. 语句结尾可以写；也可以不写
5. JS函数用function,函数名程序员自定形参由程序员自定，JS中的函数没有返回类型，因为JS是弱类型语言
- 编程的时候要先整理思路，确定实现步骤，再敲代码！

# Lesson05
## 一、Bootstrap表格 
```
<table class="table table-bordered text-center table-striped table-hover">
```
## 二、任务：个人存款计算软件界面



# Lesson04
## 昨日技术总结
1. CSS选择器(标记,id,class)
2. CSS代码放置的位置(页面内，外部文件，行内)
3. 边框样式(文本框变红)
4. 工作后网页界面由美工或者UI做，在他们基础上开发
5. 网站搭建   开发网页->购买Linux系统的主机，获得一个IP地址->把做好的网页，远程上传到主机
-》百度搜索域名注册，备案域名
## 一、CSS显示
1. display     隐藏后释放了区域
2. visibility  隐藏了，但区域不释放
## 二、CSS的浮动(float)
1. 网页美工必须精通(CSS+DIV)
2. 主要用于，网页布局(CSS+DIV)
3. (CSS+DIV)做网页布局离不开浮动float,要理解浮动的意思
## 三、学习Bootstrap技术
### 1.什么是 Bootstrap
- Twitter公司发明的技术
- 用Bootstrap做的网页，可以自适应屏幕大小
- 移动端优先
- Bootstrap基于:HTML,CSS,JavaScript
- Bootstrap本质：写好的CSS库，拿来用就行
- Bootstrap不是编程语言，而是一种技术 
### 2.如何使用 Bootstrap?
- 把 Bootstrap文件从官网下载下来，复制到自己的项目里面
- 直接使用CDN(放在公网上的) 要有网络
### 3.如何学？
- 看官方文档
### 4.工作原理
- 把屏幕分成12列，使用者自己按需自由组合
- CSS样式不用我们自己写了，直接用就行了
### 5.如何在github上搭建静态网站
- 创建一个项目
- 上传文件
- 在设置中找到pages，点击main，点sava
### 学CSS  临摹10个网站，相对熟练《CSS权威指南》
# Lesson03
## 一、CSS是什么？
1. 层叠样式表(Cascading Style Sheets)
2. 由W3C组织制定的标准，最新版 CSS3
3. 由浏览器执行
4. 作用：美化网页（HTML不具备美化网页的）
## 二、CSS选择器（5*****）
1. 标记选择器
2. id选择器  id值唯一
3. class选择器
## 三.CSS代码放置的位置
1. 页内样式：放在head之前，用style标记
2. 行内样式：放在标记的style属性里       优先级最高，越近越高
3. 外部样式：放在独立的.css文件中，
## 四、开发常用样式
1. 背景样式（background-color）
2. 文本样式 （color/text-decoraction/text-align）
3. 字体样式(font-family/font-size)
网页上的文字默认16px；  工程是12/14px
4. 链接样式 ()
```
a:hover {
				color: #FF0000;
				font-size: 30px
			}
```
5. 表格样式 细线表格(border-collapse)
```
table { 
				/*边框折叠起来，没由空心*/
			border-collapse: collapse;	
			}
```
6. 边框样式（边框变红）
```
border: 1px solid red;
```
## 五、CSS盒子模型
1. 与网页的布局密切相关
2. 美工必须精通
3. 开发工程师理解并使用
4. 重要： 外边距margin  内边距 padding;内外边距是相对的，有四个方向 上下左右
## 六、登录网页
1. HTML表单元素(用户名、密码、登录按钮)
2. 用到了盒子模型(内外边距等)
# Lesson02
## 总结
1.HTML只能做网页结构，大小写不区分由浏览器执行
2.开发重点  表单，表格、iframe、图片、超链接、列表
3.学到什么程度？把第二步写出来，
4。对开发人员的用途，做项目的界面
## 一、表格(*****)使用频率很高的
1.HTML表格怎么写
```
<table>表格标记</table>
<tr>表格行</tr>		
	表格列<td></td>
	合并单元格使用 colspan="2"
<table>
			行<tr>
				列<td>姓名</td>
				<td>年龄</td>
				<td>班级</td>
			</tr>						
		</table>
```

## 二、HTML超链接
1.链接可以到自己的网页，也可以到别的网站
```
<a href="table.html">链接到我写的网页上面</a> <br />
		<a href="http://neuc.nuc.edu.cn/">友情链接：中北大学朔州校区官网</a> <br>
```
## 三、HTML图片
1.语法
```

<img src="01.png" width="500px" height="300px"> <br>
```
2.图片带链接
```
		<a href="link.html"><img src="03.png"></a> <br>
```
## 四、HTML列表
1.有序列表
```
<ol>有序列表</ol>
			<li>列表项</li>
```
2.无序列表
```
<ul> 无序列表
			<li>列表项</li>
		</ul>
```
## 五、标题
HTML一共六级标题
```
<h1>一级标题</h1>
		<h2>二级标题</h2>
		<h3>三级标题</h3>
		<h4>四级标题</h4>
		<h5>五级标题</h5>
		<h6>六级标题</h6>
```
## 六、DIV块和段落
```
	<p>这是一个段落</p>
		<div>这是一个DIV块</div>
```
## 七、HTML颜色
颜色名或者颜色的值（主要用它，16进制，以#开头，由三基色调配而成   rgb red green blue）
## 八、字符实体
```
	&yen;8000&nbsp;&nbsp;&nbsp;
		&copy;软件学院版权所有
```
HTML是 www 的标准，但不是强制标准，语法宽松，不同浏览器支持程度不一样

## 九、关于iframe框架(常用)
网页嵌套

## 十、高频面试题 post 和 get 有什么区别
1.post方式提交表单，表单数据在地址栏不显示，比较安全  数据量大小不限,一般使用Post
2.get方式提交表单，表单数据会在地址栏显示，不安全。    数据量一般最大为2K


 Lesson1-周一(7.22)
## 一.Markdown 
  写软件文档用的，软件工程师标配，浏览器可以识别，语法简单
##什么时候用
写专业软件文档用
##HTML 超文本标记语言
为什么用它  做项目需要用它
由谁执行？浏览器
谁用？后端开发、web开发网页美工
什么时候用？   做项目
用在网页上
按教程学，项目实战中使用
##HTML标准  
W3C制定 国际万维网组织
##HTML表单开发
0.表单怎么写
<form><form/>
1.文本框怎么写
```
<input type="text" /> 
```
2.密码框怎么写
```
<input type="password" /> 
```
3.单选框怎么写
```
<input type="radio" /> 
```
4.文本域怎么写
```
<textarea  rows="5" cols="50">
```
5.多选框框怎么写
```
<input type="checkbox" />
```
6.下拉选择怎么写
```
<select><option> <option>/select>
```
8.注册按钮怎么写
```
	<input type="submit" value="注册" />
```
8.重置按钮怎么写
```
	<input type="reset" value="重置" />
```
9.文件上传提交怎么写
```
	<input type="file"  />
```
```
10.如何跳转网页
	<form action="receive.html" >
	```
##提醒
1. 不要背代码  多写来永久记忆
2. 学编程最佳方式:多写  做会的
3. 多理解理解的越多,记得越少
- 课后任务:写12306注册表单(不考虑效果和样式)
