# rust-course 维护说明

Rust 语言圣经的中文课程和练习资源。

- 上游：https://github.com/sunface/rust-course
- 在线文档：https://xiaoshecode.github.io/xiaoshecode/repos/rust-course/
- 检查日期：2026-10-30

## 环境与使用

- 安装 Rust、mdBook 及 book.toml 声明的预处理器。

使用/检查入口（需先满足依赖条件）：

- `mdbook serve`
- `mdbook build`

## 目录职责

- src/ — 正文与目录
- book.toml — mdBook 配置
- theme/ — 页面主题
- assets/rustlings-zh/ — Rust 练习

## 本次整理

- 新增维护文档和在线文档入口，补全用途、目录、使用路径及验证边界。

## 检查记录

- **仓库目录与入口盘点**（passed）：检查 Git 索引中的 543 个路径、README 和项目配置；不等于功能验收。
- **JavaScript syntax**（passed）：2 个文件通过解析；不导入依赖、不执行应用。
- **TOML parse**（passed）：7 个文件通过解析；不导入依赖、不执行应用。
- **XML parse**（passed）：7 个文件通过解析；不导入依赖、不执行应用。
- **完整构建与端到端运行**（not_run）：保留教学题目和已有目录；本机未安装 Rust/mdBook，未验证所有代码示例和构建。

## 验证边界与待办

- 保留教学题目和已有目录；本机未安装 Rust/mdBook，未验证所有代码示例和构建。

## 后续维护约定

保留上游许可证与作者信息。沿用现有模块边界和格式配置；修复功能时同步最小回归验证。依赖或接口变更需写明迁移步骤，避免仅为目录美观搬动公开入口。
