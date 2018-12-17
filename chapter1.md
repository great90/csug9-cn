# 第一章 介绍

本书描述了Chez Scheme对Scheme第6版修改报告 \[[28](http://cisco.github.io/ChezScheme/csug9.5/bibliography.html#g176)\]（R6RS）的扩展。它还包含标准和Chez Scheme形式和过程的简明摘要，给出了每个形式的语法以及每个过程接受的参数的数量和类型。有关标准R6RS功能的详细信息，请参阅[Scheme程序设计语言第4版](http://www.scheme.com/tspl4/)（TSPL4）\[[11](http://cisco.github.io/ChezScheme/csug9.5/bibliography.html#g159)\]或Scheme第6版修改报告。Scheme程序设计语言第四版同样包含对Scheme语言的大量介绍以及许多简短和扩展的示例。

本文档的大部分内容同样适用于Petite Chez Scheme，它与完整的Chez Scheme系统完全兼容，但使用一个高速解释器代替Chez Scheme的增量本机代码编译器。为Chez Scheme编写的程序在Petite Chez Scheme中保持不变，只要它们不需要调用编译器即可。实际上，Petite Chez Scheme是与Chez Scheme相同的源码构建的，包含除了编译器代码之外的其他所有源代码。第2.8节将详细讨论这种区别的影响。

本章的其余部分包括Scheme语法的Chez Scheme扩展（第1.1节），本书中使用的符号约定（第1.2节），系统定制参数的使用（第1.3节），以及在哪里查找有关Chez Scheme的更多信息（第1.4节）。

