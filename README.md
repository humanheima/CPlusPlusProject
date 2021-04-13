### 快捷键

格式化代码：option + shift + F
选中多行：按住option键进行选择
全部替换：option + command + f  ，输入替换后的值 option + command + 回车。
格式化：option + shift + F
全局查找：command + shift + f

C++ 基础

最简单的编译方式：

```
g++ helloworld.cpp
```

### 命名空间？

### C++中的变量声明和变量定义

* [C++ 变量类型](https://www.runoob.com/cplusplus/cpp-variable-types.html)


### C++ 指针

什么是指针？

指针是一个变量，其值为另一个变量的地址，即，内存位置的直接地址。就像其他变量或常量一样，您必须在使用指针存储其他变量地址之前，对其进行声明。指针变量声明的一般形式为：

```
type *var-name;
```

在这里，type 是指针的基类型，它必须是一个有效的 C++ 数据类型，var-name 是指针变量的名称。用来声明指针的星号 * 与乘法中使用的星号是相同的。但是，在这个语句中，星号是用来指定一个变量是指针。以下是有效的指针声明：

```
int    *ip;    /* 一个整型的指针 */
double *dp;    /* 一个 double 型的指针 */
float  *fp;    /* 一个浮点型的指针 */
char   *ch;    /* 一个字符型的指针 */
```


### C++ 函数

* 函数声明：告诉编译器函数的名称、返回类型和参数。
* 函数定义：提供了函数的实际主体。