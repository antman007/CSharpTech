
## C#通用文章
#### CodeProject四篇介绍C#文章
作者介绍<http://www.codeproject.com/script/Membership/View.aspx?mid=3223592>
1. <http://www.codeproject.com/Articles/1094829/Professional-techniques-for-Csharp-Lecture-Notes-P> Part4
2. <http://www.codeproject.com/Articles/1094079/An-advanced-introduction-to-Csharp-Lecture-Notes-P> Part1
3. <http://www.codeproject.com/Articles/1094359/Mastering-Csharp-Lecture-Notes-Part-of> Part2 Master C#
4. <http://www.codeproject.com/Articles/1094625/Advanced-programming-with-Csharp-Lecture-Notes-Par> Part3

#### Jon Skeet C#文章
> C# Mvp 全球有影响力Coder

1. [目录](http://www.yoda.arachsys.com/csharp/index.html)

#### C#基础教程系列

1. [C#系列文章基础教程](http://www.codeproject.com/Tips/1032174/CsharpLectures-Lecture-Primitive-Types)
2. [C#委托，事件](http://www.codeproject.com/Articles/1061085/Delegates-Multicast-delegates-and-Events-in-Csharp)
3. [C#事件和委托最佳实践 推荐](http://www.codeproject.com/Articles/20550/C-Event-Implementation-Fundamentals-Best-Practices)
4. [位操作](http://www.codeproject.com/Articles/544990/Understand-how-bitwise-operators-work-Csharp-and-V)
5. [C#参数传递，值类型和引用类型讨论](http://www.yoda.arachsys.com/csharp/parameters.html)

## C# 代码最佳实践探讨

1. CodeProject大神两篇文章Part1
<http://www.codeproject.com/Articles/1083348/Csharp-BAD-PRACTICES-Learn-how-to-make-a-good-code>
2. Part2
<http://www.codeproject.com/Articles/1097145/Csharp-BAD-PRACTICES-Learn-how-to-make-a-good-co>
谈到了一些设计模式和思想，写博客解读加深理解
3. [Some Best Practices for C# Application Development (Explained)](http://www.codeproject.com/Articles/118853/Some-Best-Practices-for-C-Application-Development)
4. [内存](http://www.codeproject.com/Articles/42721/Best-Practices-No-Detecting-NET-application-memo)

## C#常用代码
> C#具体代码操作

#### C#爬虫
1. <http://www.codeproject.com/Articles/1041115/Webscraping-with-Csharp>
2. <http://www.codeproject.com/Articles/1087859/Web-crawling-with-Csharp-part-one>

## C#内存
> C#内存内容,包括GC,内存管理,拆箱装箱

1. [Delegate GetInvocationList Memory](http://weblogs.sqlteam.com/MLADENP/archive/2007/10/24/C-Care-about-Event-Memory-Leaks-with-Delegate.GetInvocationList.aspx)
2. [Best Practices No. 5: Detecting .NET application memory leaks](http://www.codeproject.com/Articles/42721/Best-Practices-No-Detecting-NET-application-memo)

#### 拆箱装箱boxing unboxing

1. <http://stackoverflow.com/questions/1249086/boxing-on-structs-when-calling-tostring>
2. <http://stackoverflow.com/questions/7995606/boxing-occurrence-in-c-sharp/7997560#7997560>
3. MSDN文档 <https://msdn.microsoft.com/zh-cn/library/system.reflection.emit.opcodes.constrained.aspx>

> the Key Rule:Boxing occurs for exactly one reason: when we need a reference to a value type. 

针对拆箱装箱操作，最直观的是通过反编译工具查看IL代码为依据分析，.exe文件和.dll文件

****
## C# 问题解析
> 针对C#的一些问题的回答，stackoverflow

1. [Struct New操作](http://stackoverflow.com/questions/7767669/why-is-it-possible-to-instantiate-a-struct-without-the-new-keyword/7769694#7769694)
针对值类型调用new操作，只是调用相应的构造函数，保证数据正确初始化，否则C#编译器会认为使用了未初始化的变量，仅此而已
2. [IEnumerable and IEnumerator Explained](http://stackoverflow.com/questions/558304/can-anyone-explain-ienumerable-and-ienumerator-to-me)
3. [C#强制转化问题](http://stackoverflow.com/questions/132445/direct-casting-vs-as-operator) 
[第二篇](http://stackoverflow.com/questions/983030/type-checking-typeof-gettype-or-is) []()


****
## C# 大师博客
#### CodeProject
1. [Shivprasad koirala](http://www.codeproject.com/script/Membership/View.aspx?mid=1335831)
2. [Florian Rappl](http://www.codeproject.com/script/Membership/View.aspx?mid=3223592)
3. [Sergey Kizyan](http://www.codeproject.com/script/Membership/View.aspx?mid=11072411)
4. [张善有](http://www.cnblogs.com/shanyou/category/431765.html)
5. [WorkTile技术](http://www.cnblogs.com/anytao/) MVP讲述了.Net中的IL介绍很不错
6. [Jon Skeet's C# 文章stackOverflow排名第一](http://yoda.arachsys.com/csharp/) [!!!!第二个博客](https://codeblog.jonskeet.uk/)
