## public, private, protect
  + https://blog.csdn.net/a1342504010/article/details/23394319
  + https://blog.csdn.net/ycf74514/article/details/49053041
 
## 析构函数
  + 为虚函数： https://www.cnblogs.com/icmzn/p/9165239.html
  + 抛出异常： http://cnblogs.com/KevinSong/p/3323372.html
  
## 构造函数
  + 抛出异常：https://blog.csdn.net/dbbaq24022/article/details/101331493

## 虚函数
  + 虚函数表： https://blog.csdn.net/primeprime/article/details/80776625
  + 不能为虚的几种函数：普通函数、友元函数、构造函数、静态成员函数、inline内联函数
  
## 内联inline函数
  + https://www.cnblogs.com/fnlingnzb-learner/p/6423917.html
  
## RAII
  + https://www.cnblogs.com/jiangbin/p/6986511.html
  
##  overload（重载，非类） 、override（覆盖）、overwrite（重写）
  + https://www.cnblogs.com/shenlanzifa/p/5288709.html

## static
  + https://blog.csdn.net/jsjwql/article/details/1788286
  
## 函数调用栈
  + https://blog.csdn.net/wangyezi19930928/article/details/16921927
  + 参数入栈顺序：https://blog.csdn.net/testcs_dn/article/details/48876771  （https://blog.csdn.net/own_ss/article/details/51559788)
  
## 默认参数值
  + https://www.cnblogs.com/jason2013/articles/4375771.html
  
## static_cast，dynamic_cast, const_cast, reinterpret_cast

## 进程和线程
  + https://www.jianshu.com/p/2dc01727be45

## 堆
  + https://www.cnblogs.com/sxkgeek/p/9662491.html
  
## 类定义的各种关键字
  + inline:（定义）可以在类的内部把inline作为声明的一部分显式地声明成员函数，也可以在类的外部用inline关键字修饰函数的定义。可以同时在声明和定义的地方说明inline，但是最好只在类外部定义的地方说明inline，这样做使类更容易理解。
  + explicit:（声明）只能在类内声明构造函数时使用explicit关键字，在类外部定义时不应重复。
  + static:（声明） 当在类的外部定义静态成员时，不能重复static关键字，该关键字只出现在类内部的声明语句
  + =default:（声明） 位于类内部默认构造函数声明语句的参数列表之后，要求编译器生成构造函数。
  + virtual: （声明）只能出现在类内部的声明语句之前而不能用于类外部的函数定义。如果基类把一个函数声明成虚函数，则该函数在派生类中隐式地也是虚函数。
  + override:（声明或定义） C++11新标准允许派生类显式地注明它使用某个成员函数覆盖了它继承的虚函数。具体做法是在形参后面、或者在const成员函数的const关键字后面，或者在引用成员函数的引用限定符后面添加一个关键字override。
