# M3U8 视频下载器 🎬

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/Website-www.m3u8dl.org-green.svg)](https://www.m3u8dl.org)
[![GitHub Stars](https://img.shields.io/github/stars/yourusername/m3u8dl-github.svg)](https://github.com/yourusername/m3u8dl-github)

> 🚀 **免费在线M3U8视频下载工具** - 安全、简单、高效的流媒体视频下载解决方案

**中文** | [English](README_EN.md)

## 📖 项目简介

M3U8 视频下载器是一个功能强大的在线工具，专门用于下载和转换M3U8格式的流媒体视频。无需安装任何软件，直接在浏览器中使用，支持多种分辨率选择，让您轻松获取高质量的视频文件。

## 🖼️ 项目截图

### 主界面
![M3U8下载器主界面](https://www.m3u8dl.org/assets/img/screenshot-main.png)

### 多分辨率选择
![分辨率选择界面](https://www.m3u8dl.org/assets/img/screenshot-quality.png)

### 在线播放器
![M3U8播放器界面](https://www.m3u8dl.org/assets/img/screenshot-player.png)

## 🎯 在线演示

- **🏠 主页演示**: [https://www.m3u8dl.org](https://www.m3u8dl.org) - 体验完整的下载功能
- **🎮 播放器演示**: [https://www.m3u8dl.org/m3u8-player.html](https://www.m3u8dl.org/m3u8-player.html) - 在线播放M3U8视频
- **🔍 解析器演示**: [https://www.m3u8dl.org/m3u8-parser.html](https://www.m3u8dl.org/m3u8-parser.html) - 解析M3U8文件详情
- **📚 文档中心**: [https://www.m3u8dl.org/documentation.html](https://www.m3u8dl.org/documentation.html) - 详细使用教程

### ✨ 核心功能

- 🎯 **一键下载** - 输入M3U8链接即可快速下载
- 📱 **多分辨率支持** - 自动识别并提供多种清晰度选择
- 🔄 **格式转换** - 将M3U8流媒体转换为MP4格式
- 🎮 **在线播放** - 内置播放器支持预览功能
- 🔍 **链接解析** - 详细解析M3U8文件结构
- 📱 **响应式设计** - 完美适配桌面端和移动端
- 🌐 **多语言支持** - 中文/英文界面切换
- 🛡️ **安全可靠** - 纯前端处理，保护用户隐私

## 🌟 主要特点

### 🚀 简单易用
- **三步完成下载**：输入链接 → 选择分辨率 → 立即下载
- **拖拽支持**：直接拖拽M3U8文件到页面
- **智能识别**：自动检测链接格式和可用分辨率

### 🎨 现代化界面
- **美观设计**：采用现代化UI设计，用户体验优秀
- **响应式布局**：完美适配各种设备屏幕
- **直观操作**：清晰的视觉反馈和操作指引

### ⚡ 高性能
- **快速处理**：优化的下载算法，提升处理速度
- **进度显示**：实时显示下载进度和状态
- **错误处理**：完善的错误提示和解决方案

## 🛠️ 技术栈

- **前端框架**: 纯HTML5 + CSS3 + JavaScript
- **UI框架**: Tailwind CSS
- **图标库**: Font Awesome
- **视频处理**: HLS.js + M3U8-Parser
- **构建工具**: 无需构建，直接部署

## 📁 项目结构

```
m3u8dl-github/
├── index.html              # 主页面
├── m3u8-player.html        # M3U8播放器页面
├── m3u8-parser.html        # M3U8解析器页面
├── documentation.html      # 使用文档
├── contact-us.html         # 联系我们
├── privacy-policy.html     # 隐私政策
├── terms-conditions.html   # 服务条款
├── assets/                 # 静态资源
│   └── img/
│       └── logo.webp      # 网站Logo
├── js/                     # JavaScript文件
├── favicon.ico            # 网站图标
└── README.md              # 项目说明
```

## 🚀 快速开始

### 在线使用
直接访问：[https://www.m3u8dl.org](https://www.m3u8dl.org)

### 本地部署

1. **克隆项目**
```bash
git clone https://github.com/yourusername/m3u8dl-github.git
cd m3u8dl-github
```

2. **启动本地服务器**
```bash
# 使用Python
python -m http.server 8000

# 或使用Node.js
npx serve .

# 或使用PHP
php -S localhost:8000
```

3. **访问应用**
打开浏览器访问：`http://localhost:8000`

## 📋 使用说明

### 基本使用流程

1. **输入M3U8链接**
   - 在输入框中粘贴您的M3U8视频链接
   - 支持拖拽M3U8文件到页面

2. **选择视频分辨率**
   - 系统自动解析可用分辨率
   - 从下拉菜单选择所需清晰度

3. **开始下载**
   - 点击"立即下载"按钮
   - 等待处理完成并自动保存

### 高级功能

- **🎮 在线播放**: 点击"测试播放"预览视频
- **🔍 链接解析**: 使用"解析地址"查看详细信息
- **📱 移动端**: 完整支持手机和平板设备

## ❓ 常见问题

### 网络连接问题
- 确保网络连接稳定
- 尝试刷新页面重新下载
- 更换网络环境

### CORS跨域限制
- 使用支持CORS的M3U8链接
- 尝试使用代理服务器
- 联系视频提供方开启跨域支持

### 链接格式错误
- 确认链接以`.m3u8`结尾
- 在浏览器中直接访问链接测试
- 检查链接完整性

## 🤝 贡献指南

我们欢迎所有形式的贡献！

1. Fork 本项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🔗 相关链接

- **官方网站**: [https://www.m3u8dl.org](https://www.m3u8dl.org)
- **在线播放器**: [https://www.m3u8dl.org/m3u8-player.html](https://www.m3u8dl.org/m3u8-player.html)
- **链接解析器**: [https://www.m3u8dl.org/m3u8-parser.html](https://www.m3u8dl.org/m3u8-parser.html)
- **使用文档**: [https://www.m3u8dl.org/documentation.html](https://www.m3u8dl.org/documentation.html)

## 📞 联系我们

- **网站**: [https://www.m3u8dl.org](https://www.m3u8dl.org)
- **邮箱**: hb494974108@g
- **联系页面**: [https://www.m3u8dl.org/contact-us.html](https://www.m3u8dl.org/contact-us.html)

---

⭐ 如果这个项目对您有帮助，请给我们一个星标！

**免责声明**: 本工具仅供学习和研究使用，请遵守相关法律法规，尊重版权。用户使用本工具下载的内容应符合当地法律要求。