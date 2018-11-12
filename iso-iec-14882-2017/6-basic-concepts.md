# 6、基本概念

## 6.5 Program and linkage

1. 一个_程序_由一个或多个联系在一起的_翻译单元（translation units）_（条款5）组成。翻译单元由一系列声明组成。

   ```text
   translation-unit:
       declaration-seq_{opt}
   ```

2. 当名称可能表示相同的对象、引用、函数、类型、模板、命名空间或值时，就称为有_联系（linkage）_，因为该名称是由另一个范围内的声明引入的名称:



