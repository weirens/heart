# Heart Programming Language / Heart 编程语言

<div align="center">
  <h1>❤️ Heart Programming Language</h1>
  <p><em>Making Chinese Beat in the Code World / 让中文在代码世界跳动</em></p>
  
  <div>
    <button onclick="showEnglish()">English</button>
    <button onclick="showChinese()">中文</button>
  </div>
</div>

---

<!-- English Version -->
<div id="english-version">

## Overview

Heart is an innovative programming language that uses **Chinese as its base syntax**. Currently implemented in Python as a proof-of-concept, our ultimate goal is to develop a complete, high-performance Chinese programming language using assembly language, providing a more natural coding experience for native Chinese speakers.

## Project Vision

### 🎯 Core Philosophy
- **Chinese-First**: Chinese syntax as foundation, lowering programming barriers for Chinese speakers
- **Progressive Development**: Concept validation with Python first, then high-performance assembly implementation
- **Cultural Adaptation**: Syntax design aligns with Chinese thinking patterns

### 🔄 Development Roadmap
```
Phase 1: Python Prototype → Phase 2: Syntax Specification → Phase 3: Assembly Implementation → Phase 4: Ecosystem Building
```

## Technical Architecture

### Current Prototype (Python Implementation)
```
Chinese Source Code → Python Parser → Intermediate Representation → Interpretation/Code Generation
```

### Target Architecture (Assembly Implementation)
```
Chinese Source Code → Lexer(Assembly) → Parser(Assembly) → Assembly Code Generation → Native Execution
```

## Syntax Features

### Basic Syntax Examples
```heart
let count = 42
let name = "张三"
let is_active = true

if count > 10 then
    print("Count is large")
else
    print("Count is small")
end

for i from 1 to 5 do
    print("Iteration: ", i)
end
```

### Function Definition
```heart
function greet(name)
    return "Hello, " + name + "!"
end

# Usage
message = greet("李四")
print(message)
```

## Current Status

### ✅ Implemented
- Chinese keyword recognition (让/let, 如果/if, 循环/for, 函数/function, etc.)
- Basic variable declaration and assignment
- Conditional statements and loops
- Simple function definitions

### Assembly Development Plan
- **Phase 1**: Lexical Analysis (Assembly implementation)
- **Phase 2**: Syntax Analysis and Parser
- **Phase 3**: Code Generation and Optimization

## Unique Advantages

```heart
# Natural expression for Chinese speakers
let user_count = get_user_count()
if user_count > 100 then
    send_notification("User count exceeds 100")
end
```

## Get Started

```bash
# Clone repository
git clone https://github.com/your-username/heart-lang.git
cd heart-lang

# Run example
python heart_compiler.py examples/hello.heart
```

## Contributing

We welcome contributions in:
- Chinese programming syntax design
- Assembly language development
- Compiler construction
- Documentation and examples

---

*Starting from Python prototype, advancing toward high-performance assembly!*

</div>

<!-- Chinese Version -->
<div id="chinese-version" style="display: none;">

## 概述

Heart 是一门**以中文为基础语法**的创新编程语言。目前使用 Python 实现概念验证，我们的最终目标是使用汇编语言开发完整的、高性能的中文编程语言，为中文母语者提供更自然的编码体验。

## 项目愿景

### 🎯 核心理念
- **中文优先**：以中文语法为基础，降低中文母语者的编程门槛
- **渐进式开发**：先用 Python 验证概念，最终用汇编实现高性能版本
- **文化适配**：语法设计符合中文思维习惯

### 🔄 开发路线
```
阶段1：Python 原型验证 → 阶段2：语法规范制定 → 阶段3：汇编实现 → 阶段4：生态建设
```

## 技术架构

### 当前原型（Python 实现）
```
中文源代码 → Python 语法解析器 → 中间表示 → 解释执行/代码生成
```

### 目标架构（汇编实现）
```
中文源代码 → 词法分析器(汇编) → 语法分析器(汇编) → 汇编代码生成 → 本地执行
```

## 语法特色

### 基础语法示例
```heart
让 数量 = 42
让 姓名 = "张三"
让 是否激活 = 是

如果 数量 > 10 则
    打印("数量较大")
否则
    打印("数量较小")
结束

从 i=1 到 5 循环
    打印("第", i, "次迭代")
结束
```

### 函数定义
```heart
函数 问候(姓名)
    返回 "你好，" + 姓名 + "！"
结束

# 使用
消息 = 问候("李四")
打印(消息)
```

## 当前状态

### ✅ 已实现特性
- 中文关键字识别（让、如果、循环、函数等）
- 基础变量声明和赋值
- 条件判断和循环结构
- 简单的函数定义

### 汇编开发计划
- **第一阶段**：词法分析（汇编实现）
- **第二阶段**：语法分析和解析器
- **第三阶段**：代码生成和优化

## 独特优势

```heart
# 更符合中文思维的表达
让 用户数量 = 获取用户数量()
如果 用户数量 > 100 则
    发送通知("用户数超过100")
结束
```

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/your-username/heart-lang.git
cd heart-lang

# 运行示例
python heart_compiler.py examples/hello.heart
```

## 参与贡献

我们欢迎在以下方面的贡献：
- 中文编程语法设计
- 汇编语言开发
- 编译器构造
- 文档和示例编写

---

*从 Python 原型出发，向汇编高性能迈进！*

</div>

<script>
function showEnglish() {
    document.getElementById('english-version').style.display = 'block';
    document.getElementById('chinese-version').style.display = 'none';
}

function showChinese() {
    document.getElementById('english-version').style.display = 'none';
    document.getElementById('chinese-version').style.display = 'block';
}

// Default to English
showEnglish();
</script>

<style>
button {
    background-color: #f0f0f0;
    border: 1px solid #ccc;
    padding: 10px 20px;
    margin: 5px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #e0e0e0;
}

button:active {
    background-color: #d0d0d0;
}
</style>

---

**Note**: This project is currently in the concept validation phase. We welcome anyone interested in Chinese programming and compiler development to join us!  
**注**: 本项目目前处于概念验证阶段，欢迎对中文编程和编译器开发感兴趣的朋友一起参与建设！
