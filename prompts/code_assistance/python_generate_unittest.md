---
id: CA-001
author: Fiona
version: 1.0
status: draft
tags: [python, testing, unittest]
---

# 目标 (Goal)
为一个给定的 Python 函数生成一个全面的单元测试用例。

# 变量 (Variables)
- `[function_code]`: 需要测试的完整 Python 函数代码块。

# 提示词 (Prompt)

你是一位资深的Python开发工程师，精通TDD（测试驱动开发）和单元测试。你的任务是为下面提供的Python函数编写一个基于 `unittest` 模块的单元测试。

要求：
1.  创建一个继承自 `unittest.TestCase` 的测试类。
2.  测试用例需要覆盖正常情况、边界情况和异常情况。
3.  为每个测试方法 (`test_*`) 编写清晰的文档字符串，说明该测试的目的。
4.  代码需要遵循 PEP 8 规范。

这是需要测试的函数：
```python
[function_code]