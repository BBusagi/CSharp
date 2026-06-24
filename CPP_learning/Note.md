# 
### 95 How to REALLY learn C++
+ 学习cpp之后，去查看真实的opensource cpp项目
+ 除了教材之外，还需要真实环境和使用
+ 从自己感兴趣的部分开始
+ 可以尝试bug bounty program
+ PVS studio 静态代码分析

### 2 How to Setup C++ on Windows
+ VS IDE
+ Visual Assist
+ VS setting

### 4 How to Setup C++ on Linux
+ WSL
+ sudo / apt-get / update - 管理员 / 包管理 / 更新
+ 安装包推荐 vim g++ codelite cmake
+ touch - 更新时间戳并创建
+ CMakeLists.txt - 如何构建项目
+ build.sh - 如何执行构建流程
+ codelite进行build并执行

### 8/9/12/14/15 基础语法
+ unsigned 无符号位为32位，正常为符号位+31位
+ char short int long longlong float double bool
+ sizeof → byte
+ pointer* reference&
+ 通过debug模式和关闭优化来通过反汇编(disassembly)查看是否存在优化方法
+ 可以通过if来判断空指针的问题

### 5 How C++ Works
+ << 左移 / console output
+ 重要的两个参数
  + 模式 Debug / Release
  + 平台 x86 / x64
+ cpp --Compiler-> obj --Linker-> exe

#6 Compiler
#7 Linker（链接对 SDK 工作尤其重要）
#16 Pointers
#17 References（"指针 vs 引用"是经典追问）
#42 Object Lifetime
#54 Stack vs Heap（经典追问）
#38 new
#25/#68 Destructor/Virtual Destructor
#43 Smart Pointers（RAII 核心）
#44 Copy Constructor
#85 lvalue/rvalue
#89 Move Semantics + #90 std::move（经典追问）
#33 const
#35 Member Initializer List
#53 Templates
#46/#47/#106 vector 三连
