
# 中文 Python 笔记

Python 3版本的实体书：[《自学Python 编程基础、科学计算及数据分析 第2版》(李金)](https://item.jd.com/13403155.html)，京东/淘宝/当当等各平台均可购买，喜欢实体书的可以看看。

默认安装了 Python 3，以及相关的第三方包 `notebook`，`ipython`， `numpy`， `scipy`，`pandas`。推荐使用 Anaconda，这个IDE集成了大部分常用的包。

> life is short. use python.


笔记内容使用 Jupyter Notebook 来展示。安装好 Python 和相应的包之后，可以在命令行下输入：

```shell
jupyter notebook
```

也可以在[NBViewer](http://nbviewer.ipython.org/github/lijin-THU/notes-python3/blob/master/ReadMe.ipynb)中查看相关内容。

目录：
- [ch00-Python2与3的核心区别](ch00-Python2与3的核心区别)
	- [00-01Python2和3的核心区别](ch00-Python2%E4%B8%8E3%E7%9A%84%E6%A0%B8%E5%BF%83%E5%8C%BA%E5%88%AB/00-01Python2%E5%92%8C3%E7%9A%84%E6%A0%B8%E5%BF%83%E5%8C%BA%E5%88%AB.ipynb)
- [ch01-Python介绍](ch01-Python介绍)
	- [01-01Python简介](ch01-Python%E4%BB%8B%E7%BB%8D/01-01Python%E7%AE%80%E4%BB%8B.ipynb)
	- [01-02IPython解释器](ch01-Python%E4%BB%8B%E7%BB%8D/01-02IPython%E8%A7%A3%E9%87%8A%E5%99%A8.ipynb)
	- [01-03Jupyter Notebook](ch01-Python%E4%BB%8B%E7%BB%8D/01-03Jupyter%20Notebook.ipynb)
	- [01-04脚本模式与解释器模式](ch01-Python%E4%BB%8B%E7%BB%8D/01-04%E8%84%9A%E6%9C%AC%E6%A8%A1%E5%BC%8F%E4%B8%8E%E8%A7%A3%E9%87%8A%E5%99%A8%E6%A8%A1%E5%BC%8F.ipynb)
- [ch02-Python基础](ch02-Python基础)
	- [02-01Python演示](ch02-Python%E5%9F%BA%E7%A1%80/02-01Python%E6%BC%94%E7%A4%BA.ipynb)
	- [02-02数字](ch02-Python%E5%9F%BA%E7%A1%80/02-02%E6%95%B0%E5%AD%97.ipynb)
	- [02-03字符串](ch02-Python%E5%9F%BA%E7%A1%80/02-03%E5%AD%97%E7%AC%A6%E4%B8%B2.ipynb)
	- [02-04索引和切片](ch02-Python%E5%9F%BA%E7%A1%80/02-04%E7%B4%A2%E5%BC%95%E5%92%8C%E5%88%87%E7%89%87.ipynb)
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
	- [04-03继承与复用](ch04-Python%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%BC%96%E7%A8%8B/04-03%E7%BB%A7%E6%89%BF%E4%B8%8E%E5%A4%8D%E7%94%A8.ipynb)
	- [04-04公有、私有、特殊以及静态方法和属性](ch04-Python%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%BC%96%E7%A8%8B/04-04%E5%85%AC%E6%9C%89%E3%80%81%E7%A7%81%E6%9C%89%E3%80%81%E7%89%B9%E6%AE%8A%E4%BB%A5%E5%8F%8A%E9%9D%99%E6%80%81%E6%96%B9%E6%B3%95%E5%92%8C%E5%B1%9E%E6%80%A7.ipynb)
	- [04-05多重继承](ch04-Python%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%BC%96%E7%A8%8B/04-05%E5%A4%9A%E9%87%8D%E7%BB%A7%E6%89%BF.ipynb)
- [ch05-Python标准库](ch05-Python标准库)
	- [05-01模块sys：系统相关](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-01%E6%A8%A1%E5%9D%97sys%EF%BC%9A%E7%B3%BB%E7%BB%9F%E7%9B%B8%E5%85%B3.ipynb)
	- [05-02模块os：与操作系统进行交互](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-02%E6%A8%A1%E5%9D%97os%EF%BC%9A%E4%B8%8E%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E8%BF%9B%E8%A1%8C%E4%BA%A4%E4%BA%92.ipynb)
	- [05-03模块re：正则表达式](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-03%E6%A8%A1%E5%9D%97re%EF%BC%9A%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F.ipynb)
	- [05-04模块datetime：日期时间](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-04%E6%A8%A1%E5%9D%97datetime%EF%BC%9A%E6%97%A5%E6%9C%9F%E6%97%B6%E9%97%B4.ipynb)
	- [05-05模块json：处理JSON数据](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-05%E6%A8%A1%E5%9D%97json%EF%BC%9A%E5%A4%84%E7%90%86JSON%E6%95%B0%E6%8D%AE.ipynb)
	- [05-06模块glob：文件模式匹配](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-06%E6%A8%A1%E5%9D%97glob%EF%BC%9A%E6%96%87%E4%BB%B6%E6%A8%A1%E5%BC%8F%E5%8C%B9%E9%85%8D.ipynb)
	- [05-07模块math：数学](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-07%E6%A8%A1%E5%9D%97math%EF%BC%9A%E6%95%B0%E5%AD%A6.ipynb)
	- [05-08模块random：随机数](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-08%E6%A8%A1%E5%9D%97random%EF%BC%9A%E9%9A%8F%E6%9C%BA%E6%95%B0.ipynb)
	- [05-09模块pathlib：路径操作](ch05-Python%E6%A0%87%E5%87%86%E5%BA%93/05-09%E6%A8%A1%E5%9D%97pathlib%EF%BC%9A%E8%B7%AF%E5%BE%84%E6%93%8D%E4%BD%9C.ipynb)
- [ch06-NumPy模块](ch06-NumPy模块)
	- [06-01NumPy模块简介](ch06-NumPy%E6%A8%A1%E5%9D%97/06-01NumPy%E6%A8%A1%E5%9D%97%E7%AE%80%E4%BB%8B.ipynb)
	- [06-02数组基础](ch06-NumPy%E6%A8%A1%E5%9D%97/06-02%E6%95%B0%E7%BB%84%E5%9F%BA%E7%A1%80.ipynb)
	- [06-03数组广播机制](ch06-NumPy%E6%A8%A1%E5%9D%97/06-03%E6%95%B0%E7%BB%84%E5%B9%BF%E6%92%AD%E6%9C%BA%E5%88%B6.ipynb)
	- [06-04数组操作](ch06-NumPy%E6%A8%A1%E5%9D%97/06-04%E6%95%B0%E7%BB%84%E6%93%8D%E4%BD%9C.ipynb)
	- [06-05数组的读写](ch06-NumPy%E6%A8%A1%E5%9D%97/06-05%E6%95%B0%E7%BB%84%E7%9A%84%E8%AF%BB%E5%86%99.ipynb)
	- [06-06数组索引进阶](ch06-NumPy%E6%A8%A1%E5%9D%97/06-06%E6%95%B0%E7%BB%84%E7%B4%A2%E5%BC%95%E8%BF%9B%E9%98%B6.ipynb)
	- [06-07随机数组](ch06-NumPy%E6%A8%A1%E5%9D%97/06-07%E9%9A%8F%E6%9C%BA%E6%95%B0%E7%BB%84.ipynb)
	- [未命名](ch06-NumPy%E6%A8%A1%E5%9D%97/%E6%9C%AA%E5%91%BD%E5%90%8D.ipynb)
- [ch07-Matplotlib模块](ch07-Matplotlib模块)
	- [07-01Matplotlib模块简介](ch07-Matplotlib%E6%A8%A1%E5%9D%97/07-01Matplotlib%E6%A8%A1%E5%9D%97%E7%AE%80%E4%BB%8B.ipynb)
	- [07-02基于函数的可视化操作](ch07-Matplotlib%E6%A8%A1%E5%9D%97/07-02%E5%9F%BA%E4%BA%8E%E5%87%BD%E6%95%B0%E7%9A%84%E5%8F%AF%E8%A7%86%E5%8C%96%E6%93%8D%E4%BD%9C.ipynb)
	- [07-03基于对象的可视化操作](ch07-Matplotlib%E6%A8%A1%E5%9D%97/07-03%E5%9F%BA%E4%BA%8E%E5%AF%B9%E8%B1%A1%E7%9A%84%E5%8F%AF%E8%A7%86%E5%8C%96%E6%93%8D%E4%BD%9C.ipynb)
	- [07-04图像中的文本处理](ch07-Matplotlib%E6%A8%A1%E5%9D%97/07-04%E5%9B%BE%E5%83%8F%E4%B8%AD%E7%9A%84%E6%96%87%E6%9C%AC%E5%A4%84%E7%90%86.ipynb)
- [ch08-SciPy模块](ch08-SciPy模块)
	- [08-01SciPy模块简介](ch08-SciPy%E6%A8%A1%E5%9D%97/08-01SciPy%E6%A8%A1%E5%9D%97%E7%AE%80%E4%BB%8B.ipynb)
	- [08-02插值模块](ch08-SciPy%E6%A8%A1%E5%9D%97/08-02%E6%8F%92%E5%80%BC%E6%A8%A1%E5%9D%97.ipynb)
	- [08-03概率统计模块](ch08-SciPy%E6%A8%A1%E5%9D%97/08-03%E6%A6%82%E7%8E%87%E7%BB%9F%E8%AE%A1%E6%A8%A1%E5%9D%97.ipynb)
	- [08-04优化模块](ch08-SciPy%E6%A8%A1%E5%9D%97/08-04%E4%BC%98%E5%8C%96%E6%A8%A1%E5%9D%97.ipynb)
	- [08-05线性代数模块](ch08-SciPy%E6%A8%A1%E5%9D%97/08-05%E7%BA%BF%E6%80%A7%E4%BB%A3%E6%95%B0%E6%A8%A1%E5%9D%97.ipynb)
- [ch09-Pandas模块](ch09-Pandas模块)
	- [09-01Pandas模块简介](ch09-Pandas%E6%A8%A1%E5%9D%97/09-01Pandas%E6%A8%A1%E5%9D%97%E7%AE%80%E4%BB%8B.ipynb)
	- [09-02一维数据结构Series对象](ch09-Pandas%E6%A8%A1%E5%9D%97/09-02%E4%B8%80%E7%BB%B4%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84Series%E5%AF%B9%E8%B1%A1.ipynb)
	- [09-03二维数据结构DataFrame对象](ch09-Pandas%E6%A8%A1%E5%9D%97/09-03%E4%BA%8C%E7%BB%B4%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84DataFrame%E5%AF%B9%E8%B1%A1.ipynb)
	- [09-04Pandas对象的索引](ch09-Pandas%E6%A8%A1%E5%9D%97/09-04Pandas%E5%AF%B9%E8%B1%A1%E7%9A%84%E7%B4%A2%E5%BC%95.ipynb)
	- [09-05缺失值的处理](ch09-Pandas%E6%A8%A1%E5%9D%97/09-05%E7%BC%BA%E5%A4%B1%E5%80%BC%E7%9A%84%E5%A4%84%E7%90%86.ipynb)
	- [09-06数据的读写](ch09-Pandas%E6%A8%A1%E5%9D%97/09-06%E6%95%B0%E6%8D%AE%E7%9A%84%E8%AF%BB%E5%86%99.ipynb)
- [ch10-一些好玩的应用](ch10-一些好玩的应用)
	- [10-01获取必应桌面壁纸](ch10-%E4%B8%80%E4%BA%9B%E5%A5%BD%E7%8E%A9%E7%9A%84%E5%BA%94%E7%94%A8/10-01%E8%8E%B7%E5%8F%96%E5%BF%85%E5%BA%94%E6%A1%8C%E9%9D%A2%E5%A3%81%E7%BA%B8.ipynb)
