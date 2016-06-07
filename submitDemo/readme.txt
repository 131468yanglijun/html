**submit 和 button 的区别

1:button-只是创建一个普通的按钮，至于这个按钮要做什么事不一定.
//submit-提交,一般是网页需要提交什么内容到服务器上的时候才使用；
2:submit需要有form表单时才可以提交数据;而button本身就是一个按钮，要想提交数据给后台，必须绑定事件.比如:onclick事件;

**submit 和 button的优缺点
1：如果有很多数据要提交的时候，submit（表单）提交要比button提交好，因为可以减少很多数据的获取动作，比如：js:$('#username').val();
2:
a:如果<input>里的type属性为：submit，而表单提交又必须要进行js验证，如果遇到用户屏蔽了js，点击提交则会出现：js没有对数据进行合法验证就传给了后台。而如果此时后台又没有对数据进行验证，就会导致一些不合法的数据进入后台，所以用button提交数据如果用户屏蔽了js，那么数据提交动作就不激活了，这样能够保证用户提交到后的数据是经过前台js验证的，是合法的;
b:如果<input>里的type属性为：submit就要改为button，这样防止提交两次，也就是对数据库操作两次;如果不改成button，就要验证submit return true还是false;

提交按钮demo


