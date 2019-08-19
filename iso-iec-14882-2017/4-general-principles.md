# 4 General principles 总则

## 4.1 Implementation compliance

1 The set of **diagnosable rules** consists of all syntactic and semantic rules in this document except for those rules containing an explicit notation that “no diagnostic is required” or which are described as resulting in “undefined behavior”.  
**可诊断规则**集由本文档中的所有语法和语义规则组成，除了那些被明确说明了包含“不要求诊断（no diagnostic is required）”或被描述为导致“ 未定义行为（ undefined behavior ）”的规则。

2 Although this document states only requirements on C++ implementations, those requirements are often easier to understand if they are phrased as requirements on programs, parts of programs, or execution of programs. Such requirements have the following meaning:  
尽管本文档只陈述了对C++实现的需求，但是如果将这些需求描述为对程序、程序的一部分或程序的执行的需求，那么这些需求通常更容易理解。这些要求具有以下含义：
 - If a program contains no violations of the rules in this document, a conforming implementation shall, within its resource limits, accept and correctly execute that program.  
 如果一个程序没有违反本文档中的规则，那么符合标准的实现应在其资源的限制内，接受并正确执行该程序。
 - If a program contains a violation of any diagnosable rule or an occurrence of a construct described in this document as “conditionally-supported” when the implementation does not support that construct, a conforming implementation shall issue at least one diagnostic message.  
 如果程序违反了任何一条可诊断的规则，或者其包含一个在本文档中被描述为“有条件地支持”，但该实现不支持的概念，那么符合规范的实现应发出至少一条诊断消息。
 - If a program contains a violation of a rule for which no diagnostic is required, this document places no requirement on implementations with respect to that program.  
 如果程序违反了一条不需要诊断的规则，则本文档对关于该程序的实现没有具体要求。

\[ Note: During template argument deduction and substitution, certain constructs that in other contexts require a diagnostic are treated differently; see 17.8.2. —end note \]
\[ 注：在模板参数推导和替换期间，其他上下文中需要诊断的某些概念会有不同的处理；参考 17.8.2。 \]