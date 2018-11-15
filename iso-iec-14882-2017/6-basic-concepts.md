# 6 Basic concepts 基本概念

## 6.5 Program and linkage

一个程序由一个或多个编译单元（translation units）（条款5）链接组成。编译单元由一系列声明组成。

```text
translation-unit:
    declaration-seq_{opt}
```

当名称可能表示相同的对象、引用、函数、类型、模板、命名空间或值时，就称为有_联系（linkage）_，因为该名称是由另一个作用域内的声明引入的名称：



