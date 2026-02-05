<div align="center">

# 🌾 CaCrFeedFormula

**智能饲料配方优化系统**

[![Version](https://img.shields.io/badge/version-1.1.9-blue.svg)](https://github.com/cacr92/cacrfeedformula)
[![Rust](https://img.shields.io/badge/rust-2021-orange.svg)](https://www.rust-lang.org/)
[![React](https://img.shields.io/badge/react-19.1-61dafb.svg)](https://reactjs.org/)
[![Tauri](https://img.shields.io/badge/tauri-2.9-24c8d8.svg)](https://tauri.app/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

*基于 Rust + React 构建的现代化、高性能饲料配方优化系统*

[功能特性](#-核心功能) •
[技术栈](#️-技术栈详解) •
[使用文档](#-使用文档) •
[应用场景](#-应用场景) •
[许可证](#-许可证)

</div>

---

## 📖 项目简介

**CaCrFeedFormula** 是一款专为畜牧业设计的专业饲料配方优化系统。系统采用工业级线性规划算法，集成AI智能助手，提供从原料管理、配方设计、优化计算到分析报告的全流程解决方案。

### 🎯 设计理念

- **🔬 科学严谨**：基于动物营养学原理和线性规划算法
- **💡 智能高效**：AI辅助决策，自动化优化计算
- **🎨 现代易用**：直观的用户界面，流畅的操作体验
- **🚀 高性能**：Rust后端保证计算速度和系统稳定性
- **🌐 跨平台**：支持Windows、macOS和Linux操作系统

### 🏆 核心优势

- ✅ **工业级优化引擎**：HiGHS 1.12求解器，支持大规模配方优化
- ✅ **AI智能助手**：上下文感知的专业配方咨询服务
- ✅ **预混料设计**：独创反向营养计算，智能配比推荐
- ✅ **盈亏测算**：全面成本核算和财务分析，精准决策支持
- ✅ **营养预测**：基于权威公式预测能量值，12种动物全覆盖
- ✅ **多工厂管理**：企业级多工厂数据隔离和同步
- ✅ **完整数据库**：内置中国饲料成分及营养价值表
- ✅ **Excel集成**：批量导入导出，无缝对接现有工作流

---

## ✨ 核心功能

### 🎯 配方优化系统

#### 线性规划优化
- **成本最小化算法**：在满足营养约束条件下，自动计算成本最优配方
- **多目标优化**：支持成本、营养密度、原料用量等多维度优化目标
- **约束灵活设置**：营养上下限、原料用量限制、原料互斥等复杂约束
- **敏感性分析**：影子价格分析，识别关键原料和瓶颈约束
- **批量优化**：支持多配方同时优化，提高工作效率

#### 手工配方设计
- **自主配比设计**：完全手动控制原料配比，适合专家经验设计
- **实时营养计算**：配比调整时自动计算营养成分和成本
- **营养平衡分析**：实时显示营养达标状态，辅助配比调整
- **模板支持**：基于现有配方快速创建新配方
- **试验友好**：适合配方研发和试验设计

#### 预混料设计（🆕 特色功能）
- **反向营养计算**：根据全价料标准和添加量，自动反推预混料营养需求
- **智能配比推荐**：基于营养需求自动计算原料最优配比
- **固定配比支持**：灵活锁定部分原料配比，优化其他原料
- **营养达标监控**：实时显示营养指标达标状态
- **配方导入转换**：从现有配方导入并转换为预混料

#### 配方管理
- **版本控制**：完整的配方版本历史追踪和对比
- **配方分析**：多维度营养分析、成本分析和性能对比
- **批量操作**：支持批量导入、导出和处理
- **智能搜索**：多条件搜索和筛选配方
- **配方复制**：基于现有配方快速创建新配方

#### 生产批次管理
- **批次管理**：完整的生产批次生命周期管理（草稿、已确认、生产中、已完成）
- **配方配置**：支持一个批次包含多个配方和版本
- **原料需求计算**：自动计算批次所需原料清单
- **状态跟踪**：实时跟踪批次生产状态
- **数据导出**：支持导出原料使用量到Excel，用于采购和库存管理

### 🤖 AI智能助手

- **专业问答**：基于大语言模型的饲料配方专业咨询服务
- **上下文感知**：自动获取当前页面数据，提供针对性建议
- **多轮对话**：支持连续对话和完整的会话历史管理
- **流式响应**：实时AI回复，打字机效果，随时停止
- **智能提示**：根据当前页面自动生成相关快捷问题
- **多平台支持**：兼容DeepSeek等AI服务
- **会话管理**：完整的对话历史、会话切换和数据压缩

### 📊 数据管理系统

#### 原料管理
- **完整数据库**：内置中国饲料成分及营养价值表
- **营养成分管理**：详细的营养成分数据录入和维护
- **价格管理**：历史价格跟踪和价格预警功能
- **批量导入导出**：Excel批量导入导出原料数据
- **智能搜索筛选**：多条件搜索和分类筛选

#### 品种管理
- **多品种支持**：支持畜禽、水产等多种动物品种
- **生长阶段管理**：科学的生长阶段划分和管理
- **营养标准设定**：精确的营养标准设置和管理
- **标准模板**：内置常见品种的营养标准模板
- **数据导入导出**：批量导入导出品种和营养标准

#### 工厂管理
- **多工厂支持**：企业级多工厂数据隔离和权限管理
- **数据复制**：工厂间原料、配方、标准等数据同步
- **状态监控**：实时监控工厂运营状态
- **批量操作**：支持批量数据同步和管理
- **权限控制**：精细的访问权限管理

### 💰 分析与决策

#### 盈亏测算
- **全面成本核算**：配方成本、包装费、运费等全部费用项自动计算
- **实时盈亏分析**：动态计算毛利和利润率，识别亏损配方
- **历史对比追踪**：记录价格和成本变化历史，趋势分析
- **批量价格更新**：支持Excel导入批量更新原料价格
- **财务决策支持**：为定价决策和成本控制提供数据依据

#### 营养预测
- **科学预测模型**：基于NRC等权威标准的能量预测公式
- **多动物支持**：涵盖猪、鸡、牛、鱼、虾等12种动物类别
- **实时计算**：毫秒级预测速度，即时显示能量值结果
- **对比分析**：自动对比预测值与数据库原值的差异
- **灵活保存**：支持更新现有原料或创建新原料
- **置信度评估**：智能评估预测结果的可靠性

### 🎨 用户体验

- **响应式设计**：基于Ant Design的现代化界面，适配各种设备
- **主题切换**：支持浅色、深色和跟随系统三种主题模式
- **数据可视化**：丰富的图表展示配方分析结果和趋势
- **拖拽操作**：直观的交互设计，支持拖拽排序和调整
- **实时更新**：数据变更实时反映到界面
- **个性化设置**：数值精度、界面主题等个性化配置

---

## 🛠️ 技术栈详解

### 🦀 后端核心 (Rust 2021)

#### 核心框架
- **[Tauri 2.9](https://tauri.app/)** - 现代化跨平台桌面应用框架
  - 基于Rust和Web技术构建
  - 更小的安装包体积（相比Electron）
  - 更高的性能和安全性
  - 原生系统API访问能力

- **[Tokio 1.37](https://tokio.rs/)** - 高性能异步运行时
  - 完整的异步IO支持
  - 高效的任务调度
  - 多线程工作窃取调度器

#### 数据库和存储
- **[SQLx 0.7](https://github.com/launchbadge/sqlx) + SQLite** - 编译时类型安全的异步数据库
  - 编译时SQL查询验证
  - 零成本抽象
  - 异步查询支持
  - 自动迁移管理

- **[Moka 0.12](https://github.com/moka-rs/moka)** - 高性能并发缓存
  - LRU/LFU缓存策略
  - TTL（生存时间）支持
  - 异步缓存API
  - 高并发场景优化

#### 优化引擎
- **[HiGHS 1.12](https://highs.dev/)** - 工业级线性规划求解器
  - 高性能单纯形法和内点法
  - 支持大规模问题求解
  - 对偶值和敏感性分析
  - 混合整数规划支持

#### AI服务集成
- **[Reqwest 0.11](https://github.com/seanmonstar/reqwest)** - 高性能HTTP客户端
  - HTTP/2支持
  - 流式响应处理
  - 连接池管理
  - GZIP/Brotli压缩

- **[eventsource-stream 0.2](https://github.com/launchbadge/eventsource-stream)** - SSE流解析
  - Server-Sent Events解析
  - 异步流处理
  - AI流式响应支持

#### 数据处理
- **[Calamine 0.24](https://github.com/tafia/calamine)** - Excel文件读取
- **[rust_xlsxwriter 0.62](https://github.com/jmcnamara/rust_xlsxwriter)** - Excel文件写入
- **[Rayon 1.8](https://github.com/rayon-rs/rayon)** - 数据并行计算
- **[Serde 1.0](https://serde.rs/)** - 高性能序列化/反序列化

#### 开发工具
- **[Specta 2.0](https://github.com/oscartbeaumont/specta) + [Tauri Specta 2.0](https://github.com/oscartbeaumont/tauri-specta)** - 自动类型生成
  - Rust类型自动导出为TypeScript
  - 类型安全的前后端通信
  - 减少手动类型维护

- **[Tracing](https://github.com/tokio-rs/tracing)** - 结构化日志
- **[Anyhow](https://github.com/dtolnay/anyhow) + [Thiserror](https://github.com/dtolnay/thiserror)** - 错误处理

### ⚛️ 前端技术 (React 19.1 + TypeScript 5.8)

#### 核心框架
- **[React 19.1](https://reactjs.org/)** - 现代化前端框架
  - 最新的并发特性
  - 自动批处理
  - 服务器组件支持
  
- **[TypeScript 5.8](https://www.typescriptlang.org/)** - 类型安全的JavaScript
  - 静态类型检查
  - 智能代码补全
  - 重构支持

#### UI框架
- **[Ant Design 5.26](https://ant.design/)** - 企业级UI组件库
  - 50+高质量React组件
  - 完整的设计规范
  - 国际化支持
  - 主题定制能力

- **[Tailwind CSS 4.1](https://tailwindcss.com/)** - 原子化CSS框架
  - 实用优先的CSS类
  - 响应式设计
  - 暗色模式支持
  - JIT编译

#### 状态管理和数据
- **[TanStack Query 5.17](https://tanstack.com/query)** - 强大的数据获取和缓存
  - 自动缓存管理
  - 后台重新获取
  - 乐观更新
  - 无限滚动支持

#### 可视化和动画
- **[Recharts 2.15](https://recharts.org/)** - React图表库
  - 声明式图表组件
  - 响应式设计
  - 可定制的图表样式

- **[Framer Motion 11](https://www.framer.com/motion/)** - 动画库
  - 流畅的动画效果
  - 手势支持
  - 布局动画

#### 开发工具
- **[Vite 7.0](https://vitejs.dev/)** - 极速前端构建工具
  - 秒级冷启动
  - HMR热模块替换
  - 生产优化构建

- **[ESLint 9](https://eslint.org/)** - 代码质量检查
- **[LightningCSS 1.30](https://lightningcss.dev/)** - CSS压缩和优化

### 🗄️ 数据库设计

- **SQLite** - 嵌入式关系数据库
  - 零配置
  - 文件数据库
  - ACID事务
  - 跨平台兼容

- **自动迁移**：基于SQLx的迁移系统
  - 版本化数据库schema
  - 自动升级机制
  - 回滚支持

### 🎯 系统要求

| 组件 | 最低要求 | 推荐配置 |
|------|---------|---------|
| **操作系统** | Windows 10+ / macOS 10.15+ / Ubuntu 18.04+ | Windows 11 / macOS 13+ / Ubuntu 22.04+ |
| **内存** | 4GB RAM | 8GB+ RAM |
| **磁盘空间** | 2GB 可用空间 | 5GB+ 可用空间 |
| **处理器** | 双核处理器 | 四核及以上处理器 |
| **显示器** | 1280x720 分辨率 | 1920x1080 及以上 |

---

## 📚 使用文档

完整的使用文档位于 `docs/` 目录下：

### 📁 用户数据目录
配置文件与运行数据默认存放在用户数据目录（非可执行文件目录）：
- **macOS**：`~/Library/Application Support/com.cacr92.cacrfeedformula/`
- **Windows**：`%APPDATA%\\com.cacr92.cacrfeedformula\\`
- **Linux**：`~/.local/share/com.cacr92.cacrfeedformula/`

### 📖 系统指南
- [📚 饲料配方管理系统完整使用说明书](docs/饲料配方管理系统使用说明书.md) - 系统完整使用指南，涵盖所有功能模块

该文档包含以下内容：

#### 第一部分：系统概述
- 系统简介、核心功能模块、用户角色与权限、快速入门指南

#### 第二部分：基础数据管理
- 原料管理、品种管理、工厂管理

#### 第三部分：配方设计与优化
- 配方优化、手工配方、预混料设计、配方管理

#### 第四部分：分析与决策
- 配方分析、盈亏测算、营养预测

#### 第五部分：生产与库存
- 生产批次管理、原料库存管理

#### 第六部分：智能助手与设置
- AI智能助手、系统设置

#### 第七部分：附录
- 常见问题汇总、快捷键参考、最佳实践总结

---

## 🌟 特色亮点

### 🆕 预混料设计模块

这是系统的创新功能之一，解决了预混料配方设计的痛点：

**传统方式的问题**：
- 需要手动计算预混料浓度
- 配比调整繁琐，容易出错
- 难以快速优化成本

**我们的解决方案**：
1. **反向营养计算**：输入全价料标准和添加量，系统自动计算预混料需求
2. **智能配比推荐**：根据营养需求自动推荐原料配比
3. **实时达标监控**：营养指标达标状态一目了然
4. **灵活优化**：支持固定部分原料配比，优化其他原料

### 🤖 AI智能助手

不是简单的聊天机器人，而是真正的配方专家助手：

**上下文感知**：
- 在配方优化页面，AI自动分析当前配方数据
- 在原料管理页面，AI基于原料库提供建议
- 智能识别用户意图，提供精准回答

**专业知识库**：
- 深度整合饲料配方专业知识
- 理解行业术语和专业概念
- 提供基于科学的营养建议

**流式响应**：
- 打字机效果，即时显示回复
- 可随时停止AI响应
- 支持连续多轮对话

### 📊 多维度配方分析

不只是简单的数据展示，而是深度的分析和洞察：

**营养分析**：
- 完整的营养成分表
- 与标准值对比
- 营养平衡雷达图
- 限制性营养素识别

**成本分析**：
- 总成本和单位成本
- 原料成本贡献分析
- 成本结构饼图
- 成本优化建议

**敏感性分析**：
- 影子价格分析
- 识别瓶颈约束
- 原料替代建议
- 价格波动影响评估

---

## 💼 应用场景

### 适用行业

- 🐔 **禽类养殖**：肉鸡、蛋鸡、鸭、鹅等
- 🐷 **畜类养殖**：猪、牛、羊等
- 🐟 **水产养殖**：淡水鱼、海水鱼、虾蟹等
- 🦊 **特种养殖**：毛皮动物、鹌鹑等

### 适用企业

- 🏭 **饲料生产企业**：配方设计、成本控制、质量管理
- 🏢 **集团化养殖企业**：多工厂管理、标准化配方
- 🔬 **研发机构**：配方研发、试验设计、数据分析
- 👨‍🏫 **教育机构**：教学演示、实训平台

---

## 📞 技术支持

遇到问题或需要帮助？我们提供多种支持渠道：

- 📧 **邮箱联系**：153687017@qq.com
- 🐛 **问题反馈**：[GitHub Issues](https://github.com/cacr92/cacrfeedformula/issues)
- 💬 **讨论交流**：[GitHub Discussions](https://github.com/cacr92/cacrfeedformula/discussions)

---

## 🙏 致谢

本项目的开发离不开以下优秀的开源项目：

<table>
<tr>
<td align="center"><b>后端技术</b></td>
<td align="center"><b>前端技术</b></td>
<td align="center"><b>核心算法</b></td>
</tr>
<tr>
<td>

- [Rust](https://www.rust-lang.org/)
- [Tauri](https://tauri.app/)
- [Tokio](https://tokio.rs/)
- [SQLx](https://github.com/launchbadge/sqlx)

</td>
<td>

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Ant Design](https://ant.design/)
- [Tailwind CSS](https://tailwindcss.com/)

</td>
<td>

- [HiGHS](https://highs.dev/)
- [Rayon](https://github.com/rayon-rs/rayon)
- [Moka](https://github.com/moka-rs/moka)

</td>
</tr>
</table>

感谢所有为开源社区做出贡献的开发者！

---

## 📄 许可证

本项目采用 **[MIT License](LICENSE)** 开源许可证。

### 您可以：

- ✅ **商业使用** - 用于商业项目
- ✅ **修改代码** - 根据需要修改源代码
- ✅ **分发** - 自由分发副本
- ✅ **私有使用** - 用于私有项目

### 您需要：

- 📋 包含原始许可证和版权声明
- 📋 说明对代码的重大修改

---

## 📮 联系我们

<table>
<tr>
<td align="center">
<b>👤 作者</b><br>
CaCr
</td>
<td align="center">
<b>📧 邮箱</b><br>
153687017@qq.com
</td>
<td align="center">
<b>🔗 GitHub</b><br>
<a href="https://github.com/cacr92/cacrfeedformula">cacrfeedformula</a>
</td>
</tr>
</table>

---

<div align="center">

---

### 🌟 如果这个项目对您有帮助，请给我们一个 Star！

[![GitHub stars](https://img.shields.io/github/stars/cacr92/cacrfeedformula?style=for-the-badge&logo=github)](https://github.com/cacr92/cacrfeedformula/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/cacr92/cacrfeedformula?style=for-the-badge&logo=github)](https://github.com/cacr92/cacrfeedformula/network/members)
[![GitHub issues](https://img.shields.io/github/issues/cacr92/cacrfeedformula?style=for-the-badge&logo=github)](https://github.com/cacr92/cacrfeedformula/issues)

---

### 💡 项目愿景

**让饲料配方设计更简单、更智能、更高效！**

用科技赋能传统农业，用智能优化生产效率

---

Made with ❤️ by [CaCr](https://github.com/cacr92) | © 2025 All Rights Reserved

</div>
