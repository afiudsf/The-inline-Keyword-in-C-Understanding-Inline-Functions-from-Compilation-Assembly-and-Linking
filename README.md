# The-inline-Keyword-in-C-Understanding-Inline-Functions-from-Compilation-Assembly-and-Linking
本文从编译、汇编与链接角度深入剖析 C 语言 inline 关键字。澄清 inline 仅为优化建议而非强制命令，受 -O0/-O2 影响；通过 Cortex-M 汇编对比函数调用与内联差异；重点探讨为何推荐 static inline 以避免链接错误与符号污染；最后对比宏定义，指出内联是“空间换时间”，适合寄存器操作等小函数，但需警惕代码膨胀。
