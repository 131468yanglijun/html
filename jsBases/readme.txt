一:什么是jquery?
jQuery 是一个 JavaScript 函数库。


二:jQuery 库包含以下特性
HTML 元素选取
HTML 元素操作
CSS 操作
HTML 事件函数
JavaScript 特效和动画
HTML DOM 遍历和修改
AJAX
Utilities


三:基础语法意义：
$(ducoment).ready(function(){
	$(selector).action(function(){
		......
	})
})

1:document ready 函数,是为了防止文档在完全加载（就绪）之前运行 jQuery 代码
2:$(selector).action():
美元符号定义 jQuery
3:选择符（selector）“查询”和“查找” HTML 元素
4:jQuery 的 action() 执行对元素的操作


四:jquery基本语法:
1:$(this).hide() :隐藏当前的html元素。
2:$("#test").hide() :隐藏 id="test"的元素。
3:$("p").hide() :隐藏所有 <p> 元素。
4:$(".test").hide() :隐藏所有 class="test" 的元素。


五:jQuery 的选择器举例:
1:$("p") 选取 <p> 元素。
2:$("p.intro") 选取所有 class="intro" 的 <p> 元素。
3:$("p#demo") 选取所有 id="demo" 的 <p> 元素。
4:$('p:first').css('background','red') :第一个<p>元素变为红色
5:$('tr:even').css('background','yellow') :偶数行会变为黄色


六:jQuery 事件函数
1:$(selector).click() :鼠标点击事件
2:$(selector).dblclick(function):鼠标双击事件
3:$(selector).focus(function) :获得焦点事件
4:$(selector).mouseover(function) :鼠标悬停事件
5:blur() :失去焦点事件
6:keydown() :按下键盘事件
7:keyup() :键盘抬起事件
8:toggle() :绑定一个事件,轮流执行这个事件


云平台品牌与ｍｉｓ系统品牌的关系？
描述流程：一个新商户如何实现卖商品？
描述流程：商户卖完商品后，钱如何到商户手里？
普通价签和特价价签的区别？
一个商户在蓝景丽家的租金包含哪些？







