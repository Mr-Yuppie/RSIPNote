# Python和数据分析入门

​	对于接触深度学习而言，Python自然是避不开的基础。个人觉得如果是纯python，不加任何外部的库，那就需要做好准备半年时间去自己开发深度学习框架了。不过好在有很多大牛人或者机构已经开发好了很多可以拿来直接用的库，模块。下面介绍一下Python的快速入门。

## 一、Python安装配置

目前ubuntu系统已经自带Python版本，Windows也支持一键安装，在此不展开讲解。

## 二、Anaconda环境安装和使用

省时省心： Anaconda通过管理工具包、开发环境、Python版本，大大简化了你的工作流程。不仅可以方便地安装、更新、卸载工具包，而且安装时能自动安装相应的依赖包，同时还能使用不同的虚拟环境隔离不同要求的项目。之前组会也介绍过Anaconda的安装使用，在此不展开讲解。

## 三、Python编程速成

其实不太想用这个标题，因为代码的编程能力绝对不是一蹴而就的，也没有什么捷径可走，而是需要长时间的坚持与动手练习才会取得进步。在这里主要是想讲一下Python的一些基础概念和操作，实现对Python的快速入门。

### 1.Python 列表(List)

![](http://ww1.sinaimg.cn/large/005LCtBbly1fsfieqgjbvj30ki0kkt9s.jpg)

### 2.Python 字典(Dictionary)

![](http://ww1.sinaimg.cn/large/005LCtBbly1fsfieqgsqwj30kn0nrt9o.jpg)

### 3.Python 模块

![](http://ww1.sinaimg.cn/large/005LCtBbly1fsfieqgubzj30l20hhzl0.jpg)

## 四、常见库的安装和学习

当我们掌握Python并对机器学习有一定概念后，我们还要了解一些机器学习常用的开源库： 

- [Numpy](https://link.zhihu.com/?target=http%3A//www.numpy.org/)-主要提供矩阵运算的功能。 
- [Pandas](https://link.zhihu.com/?target=http%3A//pandas.pydata.org/)-提供了高效地操作大型数据集所需的工具。 
- [Matplotlib](https://link.zhihu.com/?target=http%3A//matplotlib.org/)-一个 Python 的 2D绘图库，它以各种硬拷贝格式和跨平台的交互式环境生成出版质量级别的图形。 
- [Scikit-learn](https://link.zhihu.com/?target=http%3A//scikit-learn.org/stable/)-用于数据分析和数据挖掘任务的机器学习算法。

### 1.Numpy

NumPy是Python语言的一个扩充程序库。支持高级大量的维度数组与矩阵运算，此外也针对数组运算提供大量的数学函数库。

核心数据结构：ndarray

例子：矩阵计算优化

### 2.pandas

Pandas 纳入了大量库和一些标准的数据模型，提供了高效地操作大型数据集所需的工具。pandas提供了大量能使我们快速便捷地处理数据的函数和方法。

核心数据结构：Series, DataFrame和index对象 

例子：pandas处理Excel文件

### 3.Matplotlib

绘图速成 例子：散点图、柱状图、3D图…

### 4.SciPy

SciPy是一种使用NumPy来做高等数学、信号处理、优化、统计和许多其它科学任务的语言扩展。

例子：最小二乘拟合