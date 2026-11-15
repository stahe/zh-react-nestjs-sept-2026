# RdvMedecins - 使用 NestJS 和 React 的客户端/服务器示例

本仓库配套一门课程，该课程使用现代工具重建一个客户端/服务器架构的医疗预约应用（`RdvMedecins`）。仓库只包含本 README；完整课程可在线阅读。

## 📖 阅读课程

**[https://stahe.github.io/zh-react-nestjs-sept-2026](https://stahe.github.io/zh-react-nestjs-sept-2026)**

## 简介

本文档将 2014 年的原始课程（*客户端/服务器示例 - AngularJS 1.x / Spring 4*）改编为当前的技术：
- 用 Java 和 Spring MVC 编写的服务器，被 **NestJS** 服务器（TypeScript）取代；
- **AngularJS 1.x** 客户端被 **React** 客户端（函数组件、hooks）取代；
- 核心功能和数据库原则上保持不变，并增加了基于角色的身份验证（JWT），这是原版所没有的。

本课程是在 AI Claude（Anthropic）的协助下编写的，大部分代码和讲解由它生成；作者按照生成的文档对整个课程进行了测试和验证。

## 课程内容

1. **引言** - 目标、先决条件、应用的总体架构
2. **第 1 章** - 搭建开发环境
3. **第 2 章** - NestJS 入门
4. **第 3 章** - RdvMedecins 应用的 NestJS 服务器
5. **第 4 章** - React 入门
6. **第 5 章** - RdvMedecins 应用的 React 客户端
7. **第 6 章** - 结论与后续步骤

## 涉及的技术

- **服务器**：NestJS、TypeORM、MySQL、JWT 身份验证（`@nestjs/passport`、`@nestjs/jwt`）、基于角色的访问控制
- **客户端**：React 19、Vite、TypeScript、hooks、i18next（法语/英语国际化）、Bootstrap

## 先决条件

无需事先了解 NestJS 或 React。具备 JavaScript、HTTP 和命令行的基础知识，就足以顺利完成本课程。

## 作者

AI Claude（主要作者）和 Serge Tahé（代码测试与课程审阅）
