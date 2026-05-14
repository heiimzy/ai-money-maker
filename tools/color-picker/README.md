# 颜色选择器/转换器 (Color Picker/Converter)

## 功能
- 可视化取色器：通过色相滑块 + 饱和度/明度面板选择颜色
- 五种颜色格式互转：HEX、RGB、HSL、HSV、CMYK
- 配色方案生成：互补色、邻近色、三色配色、四色配色
- 实时预览：大色块实时显示当前颜色
- 一键复制：每个颜色值旁都有复制按钮
- 暗色/亮色主题切换

## 技术
- 纯 HTML + CSS + JavaScript，客户端本地处理
- Canvas 驱动的饱和度/明度取色面板
- 响应式设计，支持移动端触摸操作
- 所有计算在浏览器中完成，数据不上传服务器

## 部署
- 路径: `tools/color-picker/`
- 访问: [color-picker/index.html](index.html)
