使用说明

程序右下角显示当前页面的图书总数。

程序一开始会读取当前数据库下的所有表（分类）并显示出来。

点击添加图书可以批量添加图书，添加表格可以自动增长。

分类、书名不可以为空。

出版时间是varchar类型。

可以先修改多个表格，然后再点击确认更改将所有更改上传到数据库去（编号自动生成，不允许更改）。

可以用选中多行图书一并删除。

查找结果全部放到总览中去了，除非全选了查找结果（默认全选或勾选了全选），否则不可以对查找结果进行更改。

在查找图书的表格里进行精确查找

升序降序是对升序降序下的下拉框进行操作的。

点击分类中的显示所有图书会刷新所有页面，任何更新操作也会刷新所有页面。

可以输入搜索条件进行搜索（价格>30），条件会直接加到数据库语句的where 后面（数据库注入漏洞）。


代码在 “src/图书管理系统” 下

如果有任何BUG或需要更改的地方，请与我联系！
