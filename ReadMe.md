
# 中文 Python 笔记

默认安装了 Python 3，以及相关的第三方包 `ipython`， `numpy`， `scipy`，`pandas`。推荐使用 Anaconda，这个IDE集成了大部分常用的包。

> life is short. use python.


笔记内容使用 Jupyter Notebook 来展示。安装好 Python 和相应的包之后，可以在命令行下输入：

```shell
jupyter notebook
```

也可以在[NBViewer](http://nbviewer.ipython.org/github/lijin-THU/notes-python3/blob/master/index.ipynb)中查看相关内容。

目录：
- [ch01-Python介绍](ch01-Python介绍)
	- [01-01Python简介](ch01-Python%E4%BB%8B%E7%BB%8D/01-01Python%E7%AE%80%E4%BB%8B.ipynb)
	- [01-02IPython解释器](ch01-Python%E4%BB%8B%E7%BB%8D/01-02IPython%E8%A7%A3%E9%87%8A%E5%99%A8.ipynb)
	- [01-03Jupyter Notebook](ch01-Python%E4%BB%8B%E7%BB%8D/01-03Jupyter%20Notebook.ipynb)
	- [01-04脚本模式与解释器模式](ch01-Python%E4%BB%8B%E7%BB%8D/01-04%E8%84%9A%E6%9C%AC%E6%A8%A1%E5%BC%8F%E4%B8%8E%E8%A7%A3%E9%87%8A%E5%99%A8%E6%A8%A1%E5%BC%8F.ipynb)
- [ch02-Python基础](ch02-Python基础)
	- [02-01Python演示](ch02-Python%E5%9F%BA%E7%A1%80/02-01Python%E6%BC%94%E7%A4%BA.ipynb)
	- [02-02数字](ch02-Python%E5%9F%BA%E7%A1%80/02-02%E6%95%B0%E5%AD%97.ipynb)
	- [02-03字符串](ch02-Python%E5%9F%BA%E7%A1%80/02-03%E5%AD%97%E7%AC%A6%E4%B8%B2.ipynb)
	- [02-04索引和分片](ch02-Python%E5%9F%BA%E7%A1%80/02-04%E7%B4%A2%E5%BC%95%E5%92%8C%E5%88%86%E7%89%87.ipynb)
	- [02-05列表](ch02-Python%E5%9F%BA%E7%A1%80/02-05%E5%88%97%E8%A1%A8.ipynb)
	- [02-06可变与不可变类型](ch02-Python%E5%9F%BA%E7%A1%80/02-06%E5%8F%AF%E5%8F%98%E4%B8%8E%E4%B8%8D%E5%8F%AF%E5%8F%98%E7%B1%BB%E5%9E%8B.ipynb)
	- [02-07元组](ch02-Python%E5%9F%BA%E7%A1%80/02-07%E5%85%83%E7%BB%84.ipynb)
	- [02-08字典](ch02-Python%E5%9F%BA%E7%A1%80/02-08%E5%AD%97%E5%85%B8.ipynb)
	- [02-09集合与不可变集合](ch02-Python%E5%9F%BA%E7%A1%80/02-09%E9%9B%86%E5%90%88%E4%B8%8E%E4%B8%8D%E5%8F%AF%E5%8F%98%E9%9B%86%E5%90%88.ipynb)
	- [02-10Python赋值机制](ch02-Python%E5%9F%BA%E7%A1%80/02-10Python%E8%B5%8B%E5%80%BC%E6%9C%BA%E5%88%B6.ipynb)
	- [02-11判断](ch02-Python%E5%9F%BA%E7%A1%80/02-11%E5%88%A4%E6%96%AD.ipynb)
	- [02-12循环](ch02-Python%E5%9F%BA%E7%A1%80/02-12%E5%BE%AA%E7%8E%AF.ipynb)
	- [02-13函数](ch02-Python%E5%9F%BA%E7%A1%80/02-13%E5%87%BD%E6%95%B0.ipynb)
	- [02-14模块与包](ch02-Python%E5%9F%BA%E7%A1%80/02-14%E6%A8%A1%E5%9D%97%E4%B8%8E%E5%8C%85.ipynb)
	- [02-15文件读写](ch02-Python%E5%9F%BA%E7%A1%80/02-15%E6%96%87%E4%BB%B6%E8%AF%BB%E5%86%99.ipynb)
	- [02-16异常与警告](ch02-Python%E5%9F%BA%E7%A1%80/02-16%E5%BC%82%E5%B8%B8%E4%B8%8E%E8%AD%A6%E5%91%8A.ipynb)
	- [02-17常用内置函数](ch02-Python%E5%9F%BA%E7%A1%80/02-17%E5%B8%B8%E7%94%A8%E5%86%85%E7%BD%AE%E5%87%BD%E6%95%B0.ipynb)
- [ch03-Python进阶](ch03-Python进阶)
	- [03-01函数进阶](ch03-Python%E8%BF%9B%E9%98%B6/03-01%E5%87%BD%E6%95%B0%E8%BF%9B%E9%98%B6.ipynb)
	- [03-02迭代器与生成器](ch03-Python%E8%BF%9B%E9%98%B6/03-02%E8%BF%AD%E4%BB%A3%E5%99%A8%E4%B8%8E%E7%94%9F%E6%88%90%E5%99%A8.ipynb)
	- [03-03装饰器](ch03-Python%E8%BF%9B%E9%98%B6/03-03%E8%A3%85%E9%A5%B0%E5%99%A8.ipynb)
	- [03-04上下文管理器](ch03-Python%E8%BF%9B%E9%98%B6/03-04%E4%B8%8A%E4%B8%8B%E6%96%87%E7%AE%A1%E7%90%86%E5%99%A8.ipynb)
	- [03-05变量作用域](ch03-Python%E8%BF%9B%E9%98%B6/03-05%E5%8F%98%E9%87%8F%E4%BD%9C%E7%94%A8%E5%9F%9F.ipynb)
- [ch04-Python面向对象编程](ch04-Python面向对象编程)
	- [04-01面向对象简介](ch04-Python%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%BC%96%E7%A8%8B/04-01%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%AE%80%E4%BB%8B.ipynb)
	- [04-02方法与属性](ch04-Python%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%BC%96%E7%A8%8B/04-02%E6%96%B9%E6%B3%95%E4%B8%8E%E5%B1%9E%E6%80%A7.ipynb)
- [ch05-Python标准库](ch05-Python标准库)
	- [05-01模块sys](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-01%E6%A8%A1%E5%9D%97sys.ipynb)
