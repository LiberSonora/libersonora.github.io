---
title: 欢迎使用 LiberSnora
sticky: 2
date: "2025-01-26"
---

![LiberSonora Logo](/images/logo-head.jpg)

开源项目仓库，欢迎 Star 支持：
<div class="text-center">
  {% btn https://github.com/LiberSonora/LiberSonora, GitHub, fab fa-github fa-fw fa-lg, GitHub %}
  {% btn https://gitee.com/LiberSonora/LiberSonora, Gitee, fab fa-git-square fa-fw fa-lg, Gitee %}
</div>

# 🌟 项目亮点

📚 **开源自由**
- 采用 MIT 许可证，真正的开源免费
- 音频处理与大模型推理全程本地离线运行
- 自主可控，数据安全有保障

🚀 **便捷部署**
- 项目容器化，开发与部署便利
- 支持 API，轻松集成到个人工作流

🧩 **模块化设计**
- 各功能模块独立
- 可单独启动特定服务（如音频增强、字幕识别等）

🔧 **灵活定制**
- 支持自定义大模型，针对特定任务提升效果
- 配置灵活多样，满足不同需求

💡 **创新功能**
- 持续更新，引入最新AI技术
- 提供独特的音频处理与文本生成能力

# 🚀 LiberSonora 发展规划

项目的愿景是打造一个全方位的有声书生态系统，分三个阶段逐步实现：

## 🎯 第一期：智能字幕提取、标题生成与多语言支持（代码放于本仓库，已完成）
🎯 解决的核心问题：
- 📁 智能重命名：摆脱"第001集_xxxx.mp3"、"Chapter_001.mp3"等无意义命名，轻松找到感兴趣的内容
- 📄 自动字幕生成：为无字幕音频添加精准字幕，实现文字内容快速定位
- 🗣️ 多语言学习辅助：借助大模型翻译，提供多语言字幕，助力语言学习

✨ 功能：
- 🎙️ 有声书音频字幕提取
- 🏷️ AI 智能命名工具
- 🌐 AI 驱动的多语言翻译
- 🇬🇧 英语有声书全面支持
- 🧠 子任务维度灵活的大模型配置
- 🏠 项目官网搭建


## 🎵 第二期：全平台有声书播放器（功能和技术栈规划中，开始时间待定）

如果您对此感兴趣，可以到 [🎧 全平台有声书播放器需求整理](https://github.com/LiberSonora/LiberSonora/discussions/2) 提出想法

🎯 解决的核心问题：
- 🎧 商业播放器本地功能薄弱
- 🗂️ 文件管理不便，界面不够美观
- 🚫 频繁弹窗广告干扰用户体验

✨ 功能：
- 💻🍎📱 跨平台支持
- ☁️ 采用 WebDAV 等开放协议，实现本地同步，避免复杂的服务端开发
- 🖥️ 服务端 NAS 友好，支持 docker、飞牛、群晖等
- 📚 有声书专属逻辑：
   - 🚫 纯净无广告体验
   - 🖼️ 自动抓取网络封面
   - 📊 基于有声书维度的进度管理、倍速管理、独立音量管理
- 🔗 支持 WebDAV、SMB 等协议，便捷接入 ALIST 或 NAS 资源
- 📴 离线模式与下载功能，节省存储空间，适应各种使用场景
- 🔊 超大音量模式：
   - 适应嘈杂环境（如通勤、散步）
   - 用手机释放更大的音量，无需耳机或便携音箱
   - 解决部分有声书音量过小的问题
   - 牺牲部分音质换取更大音量输出


## 🔮 第三期：AI 辅助创作工具（暂无规划）

✨ 功能：
- 🗣️ 整合声音克隆技术
- 👶🏻 AI 生成内容，并用父母的声音讲故事，导入到火火兔
- 📑 智能内容生成、拆分与排版
- 🔗 与第二期播放器深度联动



## 致谢如下开源项目

| 项目名称 | 项目地址 | 用途 |
|----------|----------|------|
| ClearerVoice-Studio | https://github.com/modelscope/ClearerVoice-Studio | 移除背景音 |
| FFmpeg | https://github.com/FFmpeg/FFmpeg | 音频转码 |
| FunASR | https://github.com/modelscope/FunASR | 字幕提取 |
| Ollama | https://github.com/ollama/ollama | 大模型推理 |
| Qwen2.5 | https://github.com/QwenLM/Qwen2.5 | 大模型推理 |
| MiniCPM | https://github.com/OpenBMB/MiniCPM | 大模型推理 |
| Sanic | https://github.com/sanic-org/sanic | 对外暴露 API 接口 |
| Streamlit | https://github.com/streamlit/streamlit | 页面交互 |
| StreamlitAntdComponents | https://github.com/nicedouble/StreamlitAntdComponents | 页面交互，实现步骤条 |

> ⏳ 受个人时间和精力限制，项目进展可能较为缓慢。计划先实现一二期的核心功能，再逐步完善细节。

💖 如果您喜欢这个项目，欢迎赞助支持开发！
<img src="/images/wechatpay.png" width="400" alt="赞助二维码" style="display: inline">

## 问题反馈

如果您在使用过程中遇到任何问题或有改进建议，欢迎通过以下方式反馈：

在 GitHub 上提交 Issue：
   - 访问我们的 [GitHub Issues 页面](https://github.com/LiberSonora/LiberSonora/issues)
   - 点击 "New Issue" 按钮
   - 选择适当的 issue 模板（如果有）
   - 详细描述您遇到的问题或建议

## 开源许可

本项目采用 [MIT 许可证](https://opensource.org/licenses/MIT)。

您可以在项目根目录的 `LICENSE` 文件中查看完整的许可证文本。
