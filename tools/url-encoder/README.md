# URL 编码解码工具 (URL Encoder/Decoder)

## 描述
免费在线 URL 编码解码工具，支持 URL Encode/Decode 双向转换、自动检测编码、批量处理、实时转换。

## 功能特性
- ✏️ URL Encode — 将文本编码为 URL 安全格式（Percent Encoding）
- 📖 URL Decode — 将 URL 编码字符串解码为原始文本
- 📋 批量处理 — 每行一条 URL，批量编码/解码
- 🔄 自动检测 — 解码时自动检测是否为合法 URL 编码字符串
- ⚙️ 灵活选项 — 编码所有字符、空格用 + 替代、UTF-8/ISO-8859-1 切换
- ⌨️ Ctrl+Enter 快捷键快速执行
- 🌓 暗色/亮色主题支持
- 📎 一键复制结果
- 🔄 互换模式 — 一键切换编码/解码模式
- 🔒 隐私安全 — 所有处理在浏览器本地完成

## 使用场景
- 开发者调试 API 请求参数
- URL 参数编码/解码
- 网页开发中的查询字符串处理
- 处理 OAuth、JWT 等认证流程中的 URL 参数
- Web 爬虫和数据抓取中的 URL 处理

## 技术实现
- 纯前端 HTML + CSS + JavaScript
- 使用内置 `encodeURIComponent` / `decodeURIComponent` API
- 支持 UTF-8 和 ISO-8859-1 双编码模式
- 300ms 防抖自动处理
- 响应式设计，支持移动端

## 文件结构
```
tools/url-encoder/
├── index.html      # 主页面（含所有样式和逻辑）
└── README.md       # 本文件
```

## 部署
部署到 GitHub Pages，通过相对路径 `tools/url-encoder/` 访问。
