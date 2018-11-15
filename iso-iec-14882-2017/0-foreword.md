# Foreword 序言

ISO（the International Organization for Standardization，国际标准化组织）是世界范围内的国家标准组织联盟（ISO成员组织）。编制国际标准的工作通常通过ISO技术委员会进行。对已成立技术委员会的主题感兴趣的每一个成员机构都有权派代表参加该委员会。与ISO保持联系的国际组织，各国政府和非政府组织也参与了这项工作。ISO与国际电工委员会（IEC）就所有电子工程的技术标准化事宜进行密切合作。

ISO/IEC导则第1部分描述了开发本文档所用的程序以及用于进一步维护的程序。特别需要注意的是，不同类型的ISO文档需使用不同的审批标准。本文档是根据ISO/IEC导则第2部分的编辑规则起草的（参见：[www.iso.org/directive](www.iso.org/directive)）。

提请注意的是，本文档的某些内容可能是专利权的主题。ISO不负责识别任何或所有此类专利权。在本文档制定过程中确定的任何专利权的细节，将在引言及/或收到的ISO专利声明列表中（参见：[www.iso.org/patent](www.iso.org/patent)）。

本文档中使用的任何商标名都是为了方便用户而提供的信息，并不构成认可。

有关标准的自愿性说明，ISO特定术语的含义，与合格评定有关的表述，以及ISO在技术性贸易壁垒（TBT）中遵守世界贸易组织（WTO）原则的信息，请参阅以下URL：[www.iso.org/iso/foreword.html](www.iso.org/iso/foreword.html)。

本文档由ISO/IEC JTC 1 — Information Technology技术委员会，SC 22国际编程语言及环境和系统软件接口标准化小组委员会编写。

此第5版取消并替换了第4版（ISO/IEC 14882:2014），并进行了技术修订。

与上一版相比，主要变化如下：

* 更为严格的规范表达式的求值顺序
* 删除三字符组（三元组，trigraphs）
* 对值类别（value categories）进行了调整，导致了强制复制消除（copy elision）
* 增加字符和浮点字面量语法
* lambda表达式允许捕获`*this`，和用于常量表达式
* 用于`if`和`switch`语句的初始化语句（init-statement）
* 增加constexpr if语句
* 基于范围的 `for`循环（range-based for）可以支持不同的首尾类型
* 增加结构化绑定（structured bindings）
* 增加`inline`变量
* 扩展列表初始化（list initialization），支持枚举和使用聚合初始化（aggregate initialization）初始化基类
* `static_assert`的第二个message参数现在可省略
* 增加嵌套命名空间（nested namespace）语法
* 扩展属性（attributes）的支持范围
* 异常规范（exception specifications）现在是函数类型的一部分
* 模板实参推导（template argument deduction）现在可以支持类模板
* 增加折叠表达式（fold expressions）
* 可以在`using`声明中展开参数包（pack expansion）
* 模板形参和实参允许更为一般化的形式
* 动态内存分配支持过度对齐的类型（over-aligned types）
* 预处理器（preprocessor）可以通过`__has_include`检测头文件是否存在
* 标准库中增加了新的实用函数、类型和模板，包括以下内容：
  * 类型`any`
  * 类模板`optional`
  * 类模板`variant`
  * 函数`clamp`
  * 类型`std::byte`
  * 函数`not_fn`
  * 别名模板`void_t`
  * 模板`conjunction`、`disjunction`和`negation`
  * 函数`invoke`，及类型特征（type traits）`is_invocable`和`invoke_result`
  * 类型特征`is_swappable`
* 标准库中拓展了常量表达式的求值支持
* 增加数值类型和字符串之间的基本转换函数
* `pair`和`tuple`的构造函数改为“带条件的explicit（conditionally-explicit）”
* `shared_ptr`现在可以支持C风格数组类型
* 添加用于处理未初始化内存（uninitialized memory）的算法
* 增加运行时多态的内存资源（memory resources），及基于它的内存分配器
* 增加使用Boyer-Moore和Boyer-Moore-Horspool算法的子字符串（substring）搜索器
* 为类型特征（type traits）增加辅助变量模板（variable templates）
* 增加无字符串所有权（non-owning）的`string_view`模板
* `map`和`set`具有在容器之间拼接（splice）元素的能力
* 改进`map`和`unordered_map`的元素插入
* 容器对不完整类型（incomplete types）的支持
* 增加并行算法（parallel algorithms）
* 增加新算法`sample`
* 增加特殊数学函数，以及`gcd`、`lcm`和三参数的`hypot`函数
* 增加对文件系统的操作支持
* 增加共享互斥锁（`shared_mutex`）和基于变参模板的互斥包装器（`scoped_lock`）
* 移除弃用的（deprecated）特征



