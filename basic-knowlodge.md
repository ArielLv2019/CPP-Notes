## public, private, protect
  + https://blog.csdn.net/a1342504010/article/details/23394319
  + https://blog.csdn.net/ycf74514/article/details/49053041

## 友元类 && 友元函数
  + http://c.biancheng.net/view/169.html
  + https://blog.csdn.net/c_base_jin/article/details/75206177
 
## 析构函数
  + 为虚函数： https://www.cnblogs.com/icmzn/p/9165239.html
  + 抛出异常： http://cnblogs.com/KevinSong/p/3323372.html
  + 抛出异常： https://zhuanlan.zhihu.com/p/65454580
  
## 构造函数
  + 抛出异常：https://blog.csdn.net/dbbaq24022/article/details/101331493
  + 是否可以为虚函数：https://blog.csdn.net/lmsnju/article/details/5386617?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.control&dist_request_id=1331978.12431.16186453632358255&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.control
  + 为什么构造与析构函数不能调用虚函数： https://blog.csdn.net/linpengbin/article/details/51560276
## copy构造函数
  + http://c.biancheng.net/view/151.html
  + 
## 虚函数
  + 虚函数表： https://blog.csdn.net/primeprime/article/details/80776625
  + 不能为虚的几种函数：普通函数、友元函数、构造函数、静态成员函数、inline内联函数
  
## 内联inline函数
  + https://www.cnblogs.com/fnlingnzb-learner/p/6423917.html
  + https://blog.csdn.net/shltsh/article/details/45999947?utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EOPENSEARCH%7Edefault-1.control&dist_request_id=1331988.179.16187337877635457&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EOPENSEARCH%7Edefault-1.control
  
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
  + https://blog.csdn.net/u014624623/article/details/79837849

## 不可复制类 && 只能在堆 || 栈上创建的类 && 不可被继承的类
  + https://blog.csdn.net/weixin_45818891/article/details/115288297?utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~aggregatepage~first_rank_v2~rank_aggregation-1-115288297.pc_agg_rank_aggregation&utm_term=c%2B%2B%E7%B1%BB+%E4%B8%8D%E8%83%BD%E5%9C%A8%E5%A0%86%E4%B8%8A%E5%88%9B%E5%BB%BA%E5%AF%B9%E8%B1%A1&spm=1000.2123.3001.4430
  + https://blog.csdn.net/qq_42837885/article/details/101156049?utm_term=c++%E7%B1%BB%E4%B8%8D%E8%83%BD%E5%9C%A8%E5%A0%86%E4%B8%8A%E5%88%9B%E5%BB%BA%E5%AF%B9%E8%B1%A1&utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~all~sobaiduweb~default-1-101156049&spm=3001.4430

## 进程和线程
  + https://www.jianshu.com/p/2dc01727be45
  + https://linux.cn/article-10826-1.html
  + https://zhuanlan.zhihu.com/p/65479611 

## 堆
  + https://www.cnblogs.com/sxkgeek/p/9662491.html

## 单例模式
  + https://www.cnblogs.com/sunchaothu/p/10389842.html

## C++11多线程
  + https://zhuanlan.zhihu.com/p/194198073

## 类定义的各种关键字
  + inline:（定义）可以在类的内部把inline作为声明的一部分显式地声明成员函数，也可以在类的外部用inline关键字修饰函数的定义。可以同时在声明和定义的地方说明inline，但是最好只在类外部定义的地方说明inline，这样做使类更容易理解。
  + explicit:（声明）只能在类内声明构造函数时使用explicit关键字，在类外部定义时不应重复。
  + static:（声明） 当在类的外部定义静态成员时，不能重复static关键字，该关键字只出现在类内部的声明语句
  + =default:（声明） 位于类内部默认构造函数声明语句的参数列表之后，要求编译器生成构造函数。
  + virtual: （声明）只能出现在类内部的声明语句之前而不能用于类外部的函数定义。如果基类把一个函数声明成虚函数，则该函数在派生类中隐式地也是虚函数。
  + override:（声明或定义）作用：确保该函数为虚函数并覆写来自基类的虚函数。C++11新标准允许派生类显式地注明它使用某个成员函数覆盖了它继承的虚函数。位置：在形参后面、或者在const成员函数的const关键字后面，或者在引用成员函数的引用限定符后面，函数体或纯虚函数标识 “= 0” 之前，添加一个关键字override。

## const
  + 1.const 修饰类的成员变量，表示成员常量，不能被修改。
  + 2.const修饰函数承诺在本函数内部不会修改类内的数据成员，不会调用其它非 const 成员函数。
  + 3.如果 const 构成函数重载，const 对象只能调用 const 函数，非 const 对象优先调用非 const 函数。
  + 4.const 函数只能调用 const 函数。非 const 函数可以调用 const 函数。
  + 5.类体外定义的 const 成员函数，在定义和声明处都需要 const 修饰符
  + 6.const在*的左边，则指针指向的变量的值，不可直接通过指针改变（可以通过其他途径改变）；在*的右边，则指针的指向不可变。简记为“左定值，右定向”。

## 将“引用”作为函数返回值类型的格式、好处和需要遵守的规则?
```
格式：类型标识符 &函数名（形参列表及类型说明）{ //函数体 }

好处：在内存中不产生被返回值的副本；（注意：正是因为这点原因，所以返回一个局部变量的引用是不可取的。因为随着该局部变量生存期的结束，相应的引用也会失效，产生runtime error! 

注意事项：

（1）不能返回局部变量的引用。这条可以参照Effective C++[1]的Item 31。主要原因是局部变量会在函数返回后被销毁，因此被返回的引用就成为了"无所指"的引用，程序会进入未知状态。

（2）不能返回函数内部new分配的内存的引用。这条可以参照Effective C++[1]的Item 31。虽然不存在局部变量的被动销毁问题，可对于这种情况（返回函数内部new分配内存的引用），又面临其它尴尬局面。例如，被函数返回的引用只是作为一个临时变量出现，而没有被赋予一个实际的变量，那么这个引用所指向的空间（由new分配）就无法释放，造成memory leak。

（3）可以返回类成员的引用，但最好是const。这条原则可以参照Effective C++[1]的Item 30。主要原因是当对象的属性是与某种业务规则（business rule）相关联的时候，其赋值常常与某些其它属性或者对象的状态有关，因此有必要将赋值操作封装在一个业务规则当中。如果其它对象可以获得该属性的非常量引用（或指针），那么对该属性的单纯赋值就会破坏业务规则的完整性。

（4）流操作符重载返回值申明为“引用”的作用：

流操作符<<和>>，这两个操作符常常希望被连续使用，例如：cout << "hello" << endl;　因此这两个操作符的返回值应该是一个仍然支持这两个操作符的流引用。可选的其它方案包括：返回一个流对象和返回一个流对象指针。但是对于返回一个流对象，程序必须重新（拷贝）构造一个新的流对象，也就是说，连续的两个<<操作符实际上是针对不同对象的！这无法让人接受。对于返回一个流指针则不能连续使用<<操作符。因此，返回一个流对象引用是惟一选择。这个唯一选择很关键，它说明了引用的重要性以及无可替代性，也许这就是C++语言中引入引用这个概念的原因吧。 

赋值操作符=。这个操作符象流操作符一样，是可以连续使用的，例如：x = j = 10;或者(x=10)=100;赋值操作符的返回值必须是一个左值，以便可以被继续赋值。因此引用成了这个操作符的惟一返回值选择。

＃include<iostream.h>

int &put(int n);

int vals[10];

int error=-1;

void main()

{
put(0)=10; //以put(0)函数值作为左值，等价于vals[0]=10; 

put(9)=20; //以put(9)函数值作为左值，等价于vals[9]=20; 

cout<<vals[0]; 

cout<<vals[9];

} 

int &put(int n)

{
if (n>=0 && n<=9 ) return vals[n]; 

else { cout<<"subscript error"; return error; }

}

（5）在另外的一些操作符中，却千万不能返回引用：+-*/ 四则运算符。它们不能返回引用，Effective C++[1]的Item23详细的讨论了这个问题。主要原因是这四个操作符没有side effect，因此，它们必须构造一个对象作为返回值，可选的方案包括：返回一个对象、返回一个局部变量的引用，返回一个new分配的对象的引用、返回一个静态对象引用。根据前面提到的引用作为返回值的三个规则，第2、3两个方案都被否决了。静态对象的引用又因为((a+b) == (c+d))会永远为true而导致错误。所以可选的只剩下返回一个对象了。
```
