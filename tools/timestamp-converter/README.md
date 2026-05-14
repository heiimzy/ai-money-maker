# 时间戳转换工具 (Timestamp Converter)

在线 Unix 时间戳与日期时间互转工具，支持秒级和毫秒级自动检测。

## 功能特性
- 🔄 时间戳 ↔ 日期时间双向转换
- 📐 自动检测时间戳精度（秒级 / 毫秒级）
- 💻 实时转换（输入即转）
- 🌐 UTC 和本地时区同时显示
- 📋 点击复制任意结果值
- ⏰ 实时当前时间显示
- 📦 批量转换（每行一个时间戳）
- 🔗 支持 ISO 8601、YYYY-MM-DD、MM/DD/YYYY 多种日期格式
- 🌙 暗色/亮色主题切换
- ⌨️ Ctrl+Enter 快捷转换
- 📱 响应式设计（桌面 + 移动端）

## 技术栈
- 原生 JavaScript，无外部依赖
- CSS 自定义属性 + `data-theme` 暗色主题
- `Date` API 精确时间解析
- 纯客户端处理，数据不上传服务器

## 部署说明
部署到 GitHub Pages，确保 `index.html` 在 `tools/timestamp-converter/` 目录下。
