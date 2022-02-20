在 Modernizing 里，针对于单个编程语言的工具有：

* 针对于 Java 语言的系统重构、系统迁移和系统分析的工具：[Coca](https://github.com/modernizing/coca)，Go 语言，GitHub stars：691。Coca 是一个“全功能”的重构工具，基于 Antlr 进行语法分析的，除了常规的可视化、调用分析，还可以进行自动化重构。Coca 一名的由来是：对标新哥写的 [Tequila](https://github.com/modernizing/tequila) —— 龙舌兰酒 vs 快乐水。
* 针对于 CSS/LESS/CSS 的分析和自动化重构工具：[Lemonj](https://github.com/modernizing/lemonj)，TypeScript 语言，GitHub stars：128。当时设计的主要目的是：用来对 CSS 中的颜色进行提取，基于 Antlr 的语法树分析，可以用于进行自动化的重构。
* 针对于 MySQL 代码进行自动化分析，并从中构建中 UML，并生成其关系的：[SQLing](https://github.com/modernizing/sqling)，Go 语言，使用 PingCap 的 SQL 解析器解析。当然了，还有一个初始化的针对于 PL/SQL 的版本：[pling](https://github.com/modernizing/pling)。
* 适用于 Ant 转 Maven 的半自动化工具：[Merry](https://github.com/modernizing/merry)，Go 语言 + Antlr。
* 前端规范化改造工具：[Clij](https://github.com/modernizing/clij)，用于一键添加 eslint、husky、lint-staged 等，TypeScript 语言。

针对于多语言的工具，我们有：

* 基于 Antlr 的多语言的语言模型分析工具：[Chapi](https://github.com/inherd/chapi)，Kotlin 语言。其设计的初衷是用于生成 Coca 相同的数据结构，以接入更多的可视化工具。在语法分析上，采用的是 Antlr 进行分析。
* 基于 Doxygen 的多语言分析和可视化工具：Go mod 版本的新哥的 Tequila。其中，还有一系列的迷之代码，需要重构掉。
* 基于 Ctags 的多语言模型分析和可视化工具：[Modeling](https://github.com/modernizing/modeling)，Rust 语言。分析源码，并生成基于模型的可视化依赖。
* 基于 Tree-sitter 的多语言架构守护工具：[Guarding](https://github.com/modernizing/guarding)，Rust 语言。通过自制的 DSL，来对系统架构进行守护。
