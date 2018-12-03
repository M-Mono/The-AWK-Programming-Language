# The AWK Programming Language ／ AWK 程序设计语言
Alfred V. Aho, Brian W. Kernighan，and Peter J. Weinberger

---
我认为这本书是学习 AWK 的最好书籍，语言发明人写的，肯定不同寻常。因为他们对 AWK 是最了解的，所以简明扼要却不乏深入。我们从中可以读到他们为什么发明 AWK，AWK 的长处和短处，AWK 的简单发展史等。这本书对AWK的编程模型、基本语法有简单明了的介绍，在进行数据处理、文本处理、报表、试验算法方面的应用也有很多好的实例。

由于是 1988 年的老书，其中对 GAWK 最新版本对 AWK 的扩展没有提及，但这并不妨碍其称为一本经典。

和 The C Programming Language 类似，翻翻这本书的目录，你会发现，它只用了两个章节的篇幅介绍 AWK 的语法，而剩下的篇幅都是用 AWK 做为一个简洁紧凑的玩具语言，通过各种通俗易懂的程序，来向你展示从关系型数据库到编译器以及 Unix 系统上各种常用程序实现的基本原理。凭借几位大牛的深厚功力，这些内容的讲解真是深入浅出、举重若轻，让人大呼过瘾。如果你轻信了书中前言所说的，学 AWK，只要看了前两章就可以了，那么你的损失可就大了。

此外，由于 AWK 的语法设计上和 C 保持了一致，你应该可以从书中的 AWK 程序实例中见到很多熟悉的 C 的编码范式（Coding Idiom）。

倒数第二章，作者利用AWK实现了三种排序算法和两种图遍历算法，对于大多数读者而言，可能这一章的内容会显得更加亲切一些。

最后一章，作者介绍了 AWK 从最初的版本到书中介绍的版本之间的发展历程，简单说来就是，作者们最初也没想到 AWK 还可以做这么多事情（比如写关系型数据库和编译器）。在这一章中，作者介绍了一下 AWK 中 Function 定义里那个诡异的 Local Variable 的声明方式的设计由来。

![The AWK Programming Language](https://github.com/M-Mono/The-AWK-Programming-Language/raw/master/Frontmatter.jpg)

---
编译环境：
+ Fork
  - [wuzhouhui](https://github.com/wuzhouhui/awk)


+ Apple OS X & macOS
  - [MacTeX /2018](https://www.tug.org/mactex/)


+ GNU/Linux & Microsoft Windows
  - [TeX Live /2018](https://www.tug.org/texlive/) 


+ Fonts
  - [Source Han Sans /2.000](https://github.com/adobe-fonts/source-han-sans)
  - [Source Code Pro /2.030](https://github.com/adobe-fonts/source-code-pro)


+ Editor
  - [TeXstudio /2.12.12](http://texstudio.sourceforge.net/)

+ XeLaTeX 编译 PDF 1.7 版本使用参数 --output-driver="xdvipdfmx -q -E -V 7"