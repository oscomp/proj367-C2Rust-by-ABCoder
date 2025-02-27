# proj367-C2Rust-by-ABCoder
## 项目名称
基于ABCoder结合大语言模型实现内核代码的C to Rust自动化转义。

## 项目描述
随着大语言模型（以下简称LLM）所展示出对语言本身理解和生成能力的「涌现」，人们一度对其在解决数学和复杂编程问题方面寄予厚望。探索LLM能力和软件工程更好的结合成为一个高价值但又富有挑战的任务。

ABCoder是字节跳动-基础架构团队自研的LLM原生编程解决方案，其目的在于实现一套LLM亲和的项目解析能力（在内部目前已经实现了对Golang/Rust的支持），解决LLM在处理生产级编程任务时遇到的诸如准确性、编程语言-自然语言联结、工程泛化等痛点问题。

项目旨在实现ABCoder C语言解析能力基础之上构建一套语言转义系统，实现对内核C项目的LLM辅助转义，最终将其迁移为Rust项目。

## 所属赛道
2025全国大学生操作系统比赛的“OS功能设计”赛道

## 参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生。
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖。
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求。

## 项目导师
- 高文举（gaowenju@bytedance.com）
- 段仪（duanyi.aster@bytedance.com）
- 范广宇（fanguangyu.fgy1995@bytedance.com）

## 赛题分类
- AI for System
- 操作系统工具

## 难度
- 中等偏难

## 特征
- 需要了解C/Rust/Go编程语言。
- 需要了解并灵活应用编译器前端基础知识（词法、语法、语义）。
- 需要了解LLM基础知识。
- 需要了解LLM在编程领域的应用情况。

## 文档


## License
Apache 2.0 (https://www.apache.org/licenses/LICENSE-2.0.html)

## 初步效果
- 分析负责Rust项目，并生成代码分析文档
  - 面向[rCore-Tutorial-v3操作系统源码](https://github.com/rcore-os/rCore-Tutorial-v3)自动生成的[rCore-Tutorial-v3操作系统的代码分析文档](https://github.com/rcore-os/rCore-Tutorial-v3-api-doc/blob/main/rCore-Tutorial-v3.md)
## 预期目标
1. 为ABCoder支持C项目的解析能力。
2. 基于C项目的解析能力构建语义化理解LLM Agent，实现LLM辅助项目文档自动化编写功能。
3. 构建C2Rust迁移系统，实现将指定OS（C语言实现）最大程度自动化迁移至Rust语言实现，且结果可复现、能力可迁移至其他C项目。 
