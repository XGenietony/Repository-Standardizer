# repo_standardizer Skill（企业级架构版）

repo_standardizer 是一个企业级 ClaudeCode
Skill，用于自动将任意代码仓库重构为符合：

-   Clean Architecture（整洁架构）
-   DDD（领域驱动设计）
-   分层架构（Layered Architecture）
-   模块化架构（Modular Architecture）
-   AI Agent 原生架构（Agent-native Architecture）

的标准化生产级代码库。

适用于：

-   混乱仓库重构
-   单文件项目拆分
-   遗留系统重构
-   AI Agent 项目规范化
-   团队工程标准统一

------------------------------------------------------------------------

# 支持的语言和项目类型

## 后端

-   Python
-   Node.js
-   TypeScript
-   Java
-   Go
-   Rust

## 前端

-   React
-   Vue
-   Next.js
-   Vite

## AI 项目

-   LLM Agent
-   RAG 系统
-   多 Agent 系统
-   MCP / Tool 调用系统

## 通用

-   微服务架构
-   单体服务
-   CLI 工具
-   SDK 项目

------------------------------------------------------------------------

# 核心能力

## 1. 自动架构标准化

将任意仓库重构为：

-   分层架构
-   模块化结构
-   清晰依赖关系

消除：

-   单体文件（monolith）
-   结构混乱
-   循环依赖
-   职责混乱

------------------------------------------------------------------------

## 2. 自动拆分单体文件

例如：

原始：

    main.py （5000行）

自动拆分为：

    models/
    services/
    handlers/
    utils/
    configs/

------------------------------------------------------------------------

## 3. Clean Architecture 标准结构

    repo/
    │
    ├── configs/
    ├── models/
    ├── services/
    ├── handlers/
    ├── repositories/
    ├── agents/
    ├── middlewares/
    ├── utils/
    ├── core/
    ├── tests/
    │
    └── main.py

------------------------------------------------------------------------

# AI Agent 项目标准结构

    repo/
    │
    ├── agents/
    ├── services/
    ├── models/
    ├── handlers/
    ├── configs/
    ├── utils/

------------------------------------------------------------------------

# 前端项目标准结构

    src/
    │
    ├── components/
    ├── pages/
    ├── services/
    ├── hooks/
    ├── utils/
    ├── store/
    ├── contexts/
    └── layouts/

------------------------------------------------------------------------

# 强制执行的架构规则

## 禁止

禁止在以下位置编写业务逻辑：

-   main.py
-   handlers/
-   controllers/
-   routes/

## 业务逻辑必须位于

    services/

## 数据访问必须位于

    repositories/

## 数据结构必须位于

    models/

## Agent逻辑必须位于

    agents/

------------------------------------------------------------------------

# 自动修复的问题类型

repo_standardizer 自动修复：

-   超大文件（\>500行）
-   单文件项目
-   职责混乱
-   import 混乱
-   循环依赖
-   不可维护结构
-   缺失模块
-   非标准架构

------------------------------------------------------------------------

# 自动生成的组件

当缺失时自动生成：

-   logger
-   config loader
-   base service
-   base handler
-   repository base
-   dependency container
-   agent base class

------------------------------------------------------------------------

# 依赖规则（严格）

依赖方向必须为：

    handlers
       ↓
    services
       ↓
    repositories
       ↓
    models

禁止反向依赖。

------------------------------------------------------------------------

# 使用方法

在 ClaudeCode 中输入：

    standardize this repository

或：

    refactor this repo using repo_standardizer

或：

    modularize this codebase

------------------------------------------------------------------------

# 架构目标

repo_standardizer 强制仓库具备：

-   高可维护性
-   高可扩展性
-   清晰结构
-   清晰依赖关系
-   可测试性
-   可团队协作
-   AI Agent 原生支持

------------------------------------------------------------------------

# 设计原则

遵循：

-   Clean Architecture
-   SOLID 原则
-   DDD（领域驱动设计）
-   Separation of Concerns（关注点分离）
-   DRY（不要重复自己）
-   高内聚
-   低耦合

------------------------------------------------------------------------

# 架构级重构

repo_standardizer 不只是格式化代码，而是：

-   理解代码职责
-   重构架构
-   重建模块边界
-   建立正确依赖关系

属于：

架构级重构（Architectural Refactoring）
