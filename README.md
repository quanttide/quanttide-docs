# quanttide-docs

量潮文档工程

## 概述

量潮文档工程（quanttide-docs）是量潮知识管理体系中的**文档工程**领域，以工程化方式承载文档的写作、组织、发布与访问全生命周期。

## 领域边界

- **文档写作**：文档规范、写作流程、内容结构管理
- **文档组织**：文档分类、目录体系、关联关系管理
- **文档发布**：文档构建、站点发布、版本管理
- **文档访问**：检索、导航、阅读体验

> 与 write 领域的分工：本领域承载「文档工程化」（怎么写、怎么发），write 承载「写作内容与流程」。
> 与 knowl 领域的分工：本领域承载「文档载体与发布」，knowl 承载「知识抽取与应用」。

## 子模块

| 路径 | 说明 |
|------|------|
| `apps/qtcloud-docs` | QtCloud 文档工程云 (git submodule) |
| `apps/qtdocs` | 量潮文档中心 (git submodule → qtdocs，统一承载第二大脑文档发布与访问) |
| `packages/quanttide-docs-toolkit` | 文档工程工具集 (git submodule) |
| `examples/default` | 文档工程实验室 (git submodule → quanttide-laboratory-of-document-engineering) |
| `data/context` | 文档工程语境 (git submodule → quanttide-context-of-document-engineering) |
| `data/journal` | 文档工程日志 (git submodule → quanttide-journal-of-document-engineering) |
| `data/intention` | 文档工程意图 (git submodule → quanttide-intention-of-document-engineering) |
| `docs/bylaw` | 文档工程章程 (git submodule → quanttide-bylaw-of-document-engineering) |

## 许可

[CC BY 4.0](LICENSE)
