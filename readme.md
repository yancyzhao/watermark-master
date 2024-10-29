# 加水印.com - 可能是最简易的图片加水印网页工具

## 项目简介

加水印.com 是一个简单易用的网页应用，允许用户快速为多张图片添加自定义水印。这个工具完全在浏览器中本地运行，不需要将图片上传到服务器，保证了用户数据的隐私和安全。

简单加水印，特别适合私域的素材加水印使用的场景。

## 主要特性

- 支持批量处理多张图片（最多20张）
- 自定义水印文字
- 灵活的水印位置选择（整体平铺、右下角、左下角、右上角、左上角）
- 可调节水印密度（1x1 到 6x6，仅适用于整体平铺模式）
- 自定义水印颜色（支持颜色选择器）
- 可调节水印大小（字号）
- 支持拖拽上传和粘贴上传图片
- 实时预览处理后的图片
- 支持放大预览
- 支持直接复制处理后的图片到剪贴板
- 一键下载所有处理后的图片（打包为ZIP文件）
- 支持中英文界面切换

## 如何使用

1. 访问 [加水印网站](https://jiashuiyin.com) 或在本地环境打开 `index.html` 文件。
2. 通过点击上传区域或直接粘贴来选择需要添加水印的图片（最多20张）。
3. 在 "水印文字" 输入框中输入想要的水印内容。
4. 选择水印位置（整体平铺或四个角落之一）。
5. 如果选择整体平铺，可以调整水印密度。
6. 调整水印颜色和大小。
7. 点击 "处理图片" 按钮。
8. 在预览区查看处理后的图片，可以点击图片放大预览。
9. 对于每张处理后的图片，您可以选择下载到电脑或直接复制到剪贴板。
10. 点击 "一键全部下载" 按钮保存所有处理后的图片。

## 技术栈

- HTML5
- CSS3 (使用 Tailwind CSS 框架)
- JavaScript (原生，无需其他框架)

## 本地开发

1. 克隆此仓库到本地：
   ```
   git clone https://github.com/pdmaker/watermark-master.git
   ```
2. 进入项目目录：
   ```
   cd watermark-master
   ```
3. 本地开发运行预览
   
   方案A：使用 NodeJs 运行本地开发服务器：
   ```
   node preview-node.js
   ```
   方案 B：使用 Python 环境运行服务器：
   ```
   python3 preview-python.py
   ```

## 贡献

欢迎提交 Pull Requests 来改进这个项目。对于重大变更，请先开 issue 讨论您想要改变的内容。

## 许可证

本项目采用 MIT 许可证。

## 联系方式

如果您有任何问题或建议，请在 GitHub 上开 issue 或直接联系项目维护者。

---

感谢您使用加水印网站！希望这个工具能够帮助您更方便地处理图片水印需求。
