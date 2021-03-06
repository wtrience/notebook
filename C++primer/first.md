20190301重温

https://www.shiyanlou.com/courses/405

第1：C++基础入门（第1章至第3章）

第2：表达式，语句及函数（第4章至第6章）

第3：类与IO库（第7章至第8章）

第4：容器与泛型算法（第9章至第11章）

第5：动态内存（第12章）

第6：拷贝控制与重载（第13章至第14章）

第7：面向对象程序设计（第15章至第16章）



《C++ Primer》该如何学习？

1.《C++ Primer》这本书一定要从头开始看，仔细阅读千万别跳，C++11穿插在书中的每一个角落，如果直接跳到后面你可能看到新标准又返回来看。而且这种经典的书籍反复看多遍每次也会有新收获。

2.一行一行的把书上的代码手敲一遍，边敲，边看效果，然后思考为什么这样做，这样做的效果是什么，遇到不懂的，再仔细的在书中寻找答案，书中都有很详细的解释。刚开始敲代码会遇到比较多语法错误，积累多了就能够很快改正过来。

3.做好学习笔记，书中的内容较多，而且大部分的内容不保证所有都常用，所以有一些忘记的会比较快，所以做好学习笔记快速记忆起来自己看，也可以作为以后查漏补缺的工具。



超实用的《C++ Primer》读书指南，以《C++ Primer》第五版为例：



Part1也就是前八章，除了6.6，6.7节，都要通读。尤其是第三章初步介绍了vector和string，简直就是新手福音，搞定这两个容器就能写一些简单的程序。



Part2基本就是数据结构和算法，如果有基础读起来很轻松。

9，11 两章介绍的容器，以及12.1节的智能指针要通读。多用智能指针和容器，远离segment fault. 第10章里的泛型算法可以慢慢读，读完以后可以写出高逼格的函数式风格C++。12.2节讲了怎么用new和delete分配空间，题主作为新手，知道这 种写法就行，写程序时尽量用容器代替原始数组，尤其是代码里最好不要有delete。



Part3是块硬骨头，标题就是Tools for Class Authors. 作为一个"class user"，有些部分第一次是可以略过的。

13章很重要，要细读。初始化，复制，赋值，右值引用是C++里很微妙很重要的部分，别的语言对于这些概念很少有区分得这么细的。这一章不但要精读，还要完全掌握。

14章的操作符重载第一次可以观其大略；14.9节第一次可以跳过。

15章讲OOP，重要性不言而喻。如果之前一点概念都没有，学起来会觉得比较抽象。网上关于OOP有很多通俗有趣的文章，可以一起看看。

16章讲泛型编程，第一次读16.1节，掌握最基本的函数模板和类模板就行了。



Part4 就更高档了，很多内容第一次就算啃下来，长久不用又忘了。第一次读推荐把18.2节读懂，命名空间简单易用效果好。别的内容可以观其大略，用时再看。 17.1节的tuple是个有趣的东东，可以读一读。17.3节的正则表达式和17.4节的随机数也许有用，也可以读一读。如果需要读写文件，要读一下 17.5.2节的raw I/O和17.5.3节的random I/O。

