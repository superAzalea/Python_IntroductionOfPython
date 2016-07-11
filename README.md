# Python_day1-Introduction_of_Python
##－－－－－－－－－－－－－－－－
##  Python是什么 ？
     Python 是一种面向对象的解释型（边运行边解释）程序设计语言，号称胶水语言。
2016年全世界编程语言前20名如下，Python已排名第五。
![ABC](https://github.com/superAzalea/Python_day1-Introduction_of_Python/blob/master/images/1)
## Python的优缺点
     1 Python优点：
(1) 简单、优雅、明确；（Simple, elegant, clear）
(2) 强大的基础代码库，强大的模块第三方库；
          内置的库涵盖了网络、GUI、数据库、文本、文件等。用Python开发许多功能无需从0开始直接使用现成即可。
          你可以使用别人开发的第三方库，也可以封装自己的库给别人使用。
(3) 易移植；（跨平台的语言）
(4) 面向对象；
(5)可扩展（c\java\c#…），很容易通过库结合起来（胶水语言）。
     2 Python 缺点：
(1) 代码不能加密；
(2)速度慢。
## 用Python做什么：
### 软件开发：
     （1）游戏后台、搜索、图形界面的开发（qt支持Python）；
     （2）网站(YouTube\豆瓣等）；
     （3）c/s软件；
     （4）科学运算。
### 系统管理：
     （1）脚本；
     （2）IT自动化的工作。
## Python与其它语言（c/c++,java,python,PHP，ruby，go）对比：
### python、PHP、ruby：动态语言，解释型语言（边运行边解释）；
          c/c++,java，Go：编译型语言，静态语言。
### Python与Java的区别
　　学习起来Python要比Java简单快速的多，java从c++这样的系统语言中继承了很多语法和复杂性，而Python的语法非常简洁，大大提高编写效率。
### Python与C#语言的区别
### Python是解释型语言，不需要额外的编译过程，而C#必须编译后执行。另外，Python程序全部是开源的，但是C#就不是了，Python程序可以跨平台，不需要修改就可以运行在Windows和Linux等系统平台。
### Python & C++,Perl
### Python比C++等这类语言，更容易学习，语法规则简单，语意化，易读易懂，容易维护。
### Python & Ruby
　　Python与Ruby确实有些相似，但是前者比后者更加成熟，语法的可读性是后者没法比的。与Ruby和Java不同的是，面向对象编程在python里不是必选的，这就更加增加了这门语言的灵活性。Ruby语言只适合编写，但是维护的时候你会非常头疼，更不用说多人编写和维护的项目代码了。
## Python初使用
### python安装：
          http://www.runoob.com/python/python-install.html
### 版本   2.75，2.4，3.0，3.4
          2.4：最广泛应用

          2.75：工业版
          3.0：2008年，与2.4不兼容；

### unix\linux默认安装Python，在终端输入：Python，来查看版本：
    *1 Mac下：
     ![ABC](https://github.com/superAzalea/Python_day1-Introduction_of_Python/blob/master/images/2)
     *2 Ubuntu14.04下：
          ![ABC](https://github.com/superAzalea/Python_day1-Introduction_of_Python/blob/master/images/3)

     *3 Win7:
          无自带python.
     portable python:不需要安装
## 我的第一个Python程序（ hello world:）
### 交互器
         ![ABC](https://github.com/superAzalea/Python_day1-Introduction_of_Python/blob/master/images/4)
         退出可以输入exit()或者quit()或者Ctrl+D。

### 脚本
     *1 python解释器

          *  CPython:
               一种用C语言来完成Python的解释器。他把Python代码编译成字节码，然后再通过一个虚拟机去解释。CPython提供了最高水准的Python包和C语言扩展模块的兼容。
             加入你在用Python写开源软件，并想让他达到最广的受众。那么用CPython是最合适的。为了使用需要C扩展函数的程序包，CPython是最佳选择。
     * PyPy
          PyPy是一个Python解释器用来实现一种叫做RPyhton的受限静态Python子集。这种即时的编译器和解释器支持很多后段，比如C, CLI, JVM。
          PyPy旨在最大限度的用CPython的方式完成的情况下提高其性能。
          加入你想提高Python代码的性能，那么PyPy可以拿来一试。在标准集的测试上，他的速度是CPython的5倍以上.
     * Jython
          Jython是一种把Pyhton代码编译成Java字节码的解释器，它是通过JVM (Java Virtual Machine)来运行的。另外，你还能导入并使用Java的类。
          加入你想和你当前的Java程序配套起来，那么Jython是不二选择。
     * IronPython
          IronPython  是一个为了实现Python对.NET框架的解释器。它能够使用Python和.NET框架的库，并且能够把Python代码扩展成.NET框架中的其他代码。
          Python Tools for Visual Studio 直接把IronPython集成到了Visual Studio开发环境，使其对于Windows开发者来说是个不错的选择。
     *2  IndentationError:缩进错误
     *3 在unix/linux下先新建hello.py文件，输入：
            ![ABC](https://github.com/superAzalea/Python_day1-Introduction_of_Python/blob/master/images/5)
          并修改文件为可执行：
            ![ABC](https://github.com/superAzalea/Python_day1-Introduction_of_Python/blob/master/images/6)

          运行：
            ![ABC](https://github.com/superAzalea/Python_day1-Introduction_of_Python/blob/master/images/7)

