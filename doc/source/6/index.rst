============================
六.注释规范
============================

-----------------------------------------------------------------------------------------------------------------
1，	javascript注释需要表明作者，文件版本，创建时间、修改时间，重大版本修改记录，函数描述，功能等信息.
-----------------------------------------------------------------------------------------------------------------

::

	单行注释使用“//”,多行及块状注释使用“/**/”


中间可添加如下信息::

	@file 文件名
	
	@author 函数/类作者的姓名
	
	@base 如果类是继承得来，定义提供的类名称
	
	@class 用来给一个类提供描述，不能用于构造器的文档中
	
	@constructor 描述一个类的构造器
	
	@link 类似于@link标签，用于连接许多其它页面
	
	@member 定义随后的函数为提供的类名称的一个成员
	
	@private 表示函数/类为私有，不应包含在生成的文档中
	
	@return 描述一个函数的返回值
	
	@throws 描述函数/类可能产生的错误
	
	@version 函数/类的版本号
	
--------------------------------------------------------
2，	html注释；以“<！--”开始，以”-->”结束.
--------------------------------------------------------

例如::

	<!--html注释内容-->
	
-------------------
3，	css注释.
-------------------

例如::

	/*头部css定义*/
	.header{width:960px;height:120px;}




