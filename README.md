# 公共用例集合

## 项目介绍

本项目包含了一系列展示系统核心功能的实用案例，涵盖了从基础查询到高级自动化工作流的各种应用场景。每个用例都提供了详细的中英文说明文档，帮助用户快速理解和掌握系统的使用方法。

## 用例概览

### 📊 基础查询类

#### 1. 股票价格查询
- **文件位置**: [chn/stock-price-query.md](chn/stock-price-query.md) | [eng/stock-price-query.md](eng/stock-price-query.md)
- **功能描述**: 展示系统默认的浏览器工具功能，支持Simple模式和Plan-Act增强模式
- **核心特性**: 
  - 简单聊天框查询
  - 可变参数查询不同公司股价
  - 详细的执行过程展示
- **适用场景**: 金融信息查询、股价监控

#### 2. IP查询
- **文件位置**: [chn/ip-query.md](chn/ip-query.md) | [eng/ip-query.md](eng/ip-query.md)
- **功能描述**: 展示MCP服务集成方法，通过外部服务扩展系统功能
- **核心特性**:
  - MCP服务配置和管理
  - SSE连接方式
  - 外部服务调用
- **适用场景**: 网络信息查询、IP定位服务

### 🔧 高级功能类

#### 3. 表单输入演示
- **文件位置**: [chn/form-input-demo.md](chn/form-input-demo.md) | [eng/form-input-demo.md](eng/form-input-demo.md)
- **功能描述**: 展示用户交互等待机制和登录状态保持功能
- **核心特性**:
  - Form-input工具使用
  - 异步用户交互处理
  - 浏览器会话状态保持
- **适用场景**: 需要用户登录的网站操作、交互式工作流

#### 4. 查询计划
- **文件位置**: [chn/query-plan.md](chn/query-plan.md) | [eng/query-plan.md](eng/query-plan.md)
- **功能描述**: 展示DeepResearch类应用的实现，体现"函数是第一公民"的设计理念和function-agent能力。通过将复杂任务分解为可复用的工具函数，实现智能化的深度调研搜索功能
- **核心特性**:
  - Function-agent能力：智能函数组合和自动任务分解
  - 函数组合和复用：支持将复杂任务分解为可复用的工具函数
  - 复杂任务分解：自动识别和拆分调研任务
  - 基于真实数据的回答生成：所有回答都基于实际访问的页面内容
  - 清晰的引用和依据展示：提供完整的引用链和证据支持
  - 智能调研策略：自动选择最佳调研路径和资源
- **适用场景**: 深度调研、学术研究、信息收集、智能分析

#### 5. 图片和PDF识别
- **文件位置**: [chn/image-pdf-recognition.md](chn/image-pdf-recognition.md) | [eng/image-pdf-recognition.md](eng/image-pdf-recognition.md)
- **功能描述**: 展示图片和PDF识别功能，支持批量识别和结构化输出，同时支持HTTP接口调用
- **核心特性**:
  - 文档解析和OCR技术
  - 结构化数据提取
  - HTTP服务发布和调用
  - 文件上传和批量处理
  - 异步任务执行
  - JSON格式标准化输出
- **适用场景**: 文档处理、内容提取、批量识别、API服务

#### 6. AI小说
- **文件位置**: [chn/ai-novel.md](chn/ai-novel.md) | [eng/ai-novel.md](eng/ai-novel.md)
- **功能描述**: 展示长内容一体化输出和function-agent实现，通过分而治之策略完成长篇内容创作，支持批量生产长文章
- **核心特性**:
  - 长内容一体化输出：突破上下文限制，实现连贯的长篇内容生成
  - Function-agent实现：智能任务分解和工具函数组合，体现"函数是第一公民"理念
  - 批量生产长文章：支持章节化写作流程，可重复用于不同主题的长文创作
  - 分而治之策略：将复杂创作任务分解为可管理的章节单元
  - 内容连贯性保证：确保各章节间的逻辑一致性和风格统一
- **适用场景**: 内容创作、创意写作、批量文章生产、长篇文档生成

## 技术架构

### 核心组件
- **Plan-Act模式**: 系统的主要工作模式，支持复杂任务规划和执行
- **工具集成**: 内置browser_use工具和外部MCP服务集成
- **函数组合**: 支持将复杂任务分解为可复用的工具函数
- **状态管理**: 支持浏览器会话和登录状态的持久化

### 支持的功能
- ✅ 简单查询模式
- ✅ 增强型计划执行
- ✅ 可变参数支持
- ✅ 外部服务集成
- ✅ 用户交互等待
- ✅ 函数发布和复用
- ✅ 深度调研搜索

## 快速开始

1. **选择用例**: 根据需求选择相应的用例文档
2. **阅读说明**: 仔细阅读中英文说明文档
3. **按步执行**: 按照文档中的步骤进行操作
4. **查看结果**: 观察系统执行过程和结果

## 文件结构

```
public-usecase/
├── README.md                    # 项目总览（本文件）
├── README_EN.md                # 英文版项目总览
├── chn/                        # 中文版用例文档
│   ├── stock-price-query.md    # 股票价格查询
│   ├── ip-query.md            # IP查询
│   ├── form-input-demo.md     # 表单输入演示
│   ├── query-plan.md          # 查询计划
│   └── ai-novel.md           # AI小说
└── eng/                       # 英文版用例文档
    ├── stock-price-query.md   # Stock Price Query
    ├── ip-query.md           # IP Query
    ├── form-input-demo.md    # Form Input Demo
    ├── query-plan.md         # Query Plan
    └── ai-novel.md          # AI Novel
```

## 贡献指南

欢迎贡献新的用例和改进现有文档。请确保：
- 提供中英文两个版本
- 使用清晰的步骤编号
- 包含预期结果和技术要点
- 保持文档格式的一致性

## 许可证

本项目采用开源许可证，具体信息请查看LICENSE文件。

## 交流讨论

点击这个链接加入钉钉群讨论：[https://qr.dingtalk.com/action/joingroup?code=v1,k1,PBuFX00snERuKcnnG4YAPK52FOXwAkLYlulUUD9KiRo=&_dt_no_comment=1&origin=11](https://qr.dingtalk.com/action/joingroup?code=v1,k1,PBuFX00snERuKcnnG4YAPK52FOXwAkLYlulUUD9KiRo=&_dt_no_comment=1&origin=11)