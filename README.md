# LED 大屏模组组装工具

> 🖥️ 专为音视频工程师、显示屏厂商、项目设计人员打造的 LED 大屏模组智能布局与尺寸计算工具。  
> 实现快速配置、图像预览、尺寸估算、PDF/Excel 报告导出等一站式功能。

## 📌 项目简介

该工具旨在帮助用户根据 LED 点间距与模组尺寸，快速构建 LED 大屏的布局草图，并提供精确的分辨率、尺寸和比例计算。支持常规预设和自定义输入，并可导出为 PDF 报告和 Excel 表格。

## ✨ 功能亮点

- 💡 **多种计算模式**：支持行列输入、自定义尺寸、屏幕宽高比计算等方式
- 📐 **实时尺寸计算**：根据模组规格与点间距自动计算分辨率与物理尺寸
- 🖼️ **图片叠加预览**：上传背景图，辅助布局可视化设计
- 📤 **导出功能**：一键导出布局方案为 PDF 或 Excel 文件
- 🎨 **美观 UI**：响应式设计，支持桌面与移动端访问，科技感十足

## 🚀 在线预览

你可以通过部署在本地或服务器上的 HTML 文件访问工具。  
浏览器直接打开 `index.html` 文件即可使用，无需后端支持。

## 🛠️ 使用说明

1. 打开 `index.html`
2. 选择 LED 点间距（如 P1.25、P2 等）
3. 选择模组尺寸（如 320x160 mm）
4. 选择计算模式（预览模式、自定义尺寸、比例模式）
5. 输入相应参数（如行列数、屏幕尺寸或宽高比）
6. 点击 **生成布局** 查看大屏结构
7. 可选择上传背景图辅助预览
8. 点击 **导出 PDF** 或 **导出 Excel** 下载方案

## 🧱 技术栈

- HTML5 + CSS3 + JavaScript
- [Bootstrap 5](https://getbootstrap.com/)
- [XLSX.js](https://github.com/SheetJS/sheetjs) — 用于导出 Excel
- [jsPDF](https://github.com/parallax/jsPDF) — 用于导出 PDF
- FontAwesome + Google Fonts
- 自定义响应式 UI 和 Canvas 绘图逻辑

## 📦 本地部署

无需构建或依赖环境，直接通过浏览器打开即可：

```bash
git clone https://github.com/your-username/led-layout-tool.git
cd led-layout-tool
open index.html
或使用 VS Code Live Server 插件进行本地访问。
