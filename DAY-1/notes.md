#第一天 开始系统学习python；需求：学习一个编程语言加上pytest自动化所需

##今天学习了：
我开始系统规划学习 Python：

02：运行了第一个代码；

03：程序：是数据和指令的有序集合，写程序就是让我们通过数据和指令来控制电脑做工作，第一课：
变量：变量名由字母、数字和下划线构成，数字不能开头

## 练习代码
Windows 系统可以在命令提示符或 PowerShell 中输入python --version检查 Python 环境是否安装成功；macOS 系统可以在终端中输入python3 --version进行检查。

进入python内后，便可写入代码；写quit()，便退出与python的交互环境

更好的交互式环境 - IPython
可以用 IPython 来替换掉它，因为 IPython 提供了更为强大的编辑和交互功能。我们可以在命令提示符或终端中使用 Python 的包管理工具pip来安装 IPython
pip install ipython
接下来可以使用下面的命令启动 IPython，进入交互式环境。
ipython


接下来，写伟大的丹尼斯·里奇（C 语言之父，和肯·汤普森一起开发了 Unix 操作系统）和布莱恩·柯尼汉（awk 语言的发明者）在他们的不朽著作《The C Programming Language》中写的第一段代码::
print('hello,world')
print('goodbye,world')

print  --输出指定内容；'hello,world'是一串字符串，代表一串文本内容

a = 100
b = 123.45
c = '123'
d = '100'
e = '123.45'
f = 'hello, world'
g = True
print(float(a))         # int类型的100转成float，输出100.0
print(int(b))           # float类型的123.45转成int，输出123
print(int(c))           # str类型的'123'转成int，输出123
print(int(c, base=16))  # str类型的'123'按十六进制转成int，输出291
print(int(d, base=2))   # str类型的'100'按二进制转成int，输出4
print(float(e))         # str类型的'123.45'转成float，输出123.45
print(bool(f))          # str类型的'hello, world'转成bool，输出True
print(int(g))           # bool类型的True转成int，输出1
print(chr(a))           # int类型的100转成str，输出'd'
print(ord('d'))         # str类型的'd'转成int，输出100
## 我遇到问题 
