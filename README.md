<p align="center">
  <a href="https://www.bright.cn/">
    <img src="https://mintlify.s3.us-west-1.amazonaws.com/brightdata/logo/light.svg" width="300" alt="Bright Data 标志">
  </a>
</p>

# 评论智能代理 Review Intelligence Agent 🕵️‍♂️✨

**一款强大的工具，使用 AI 代理在多个平台收集、分析并从客户评论中生成洞察。🤖💡**

<div align="center">
  <img src="https://img.shields.io/badge/python-3.8+-blue"/>
  <img src="https://img.shields.io/badge/License-MIT-blue"/>
</div>

---

## 功能 Features 🚀

- 多平台评论采集：从包括 Trustpilot 在内的多个平台采集评论 🌐
- 情感分析：围绕关键方面（支持、定价、易用性）进行情感分析 📊
- 可执行洞察：从评论数据生成商业智能 📈✨
- 方面级分析：对产品/服务的特定方面进行深入剖析 🔍

## 先决条件 Prerequisites 🛠️

- Python 3.8+ 🐍
- pip（Python 包管理器）📦
- [Bright Data](https://www.bright.cn/) API 令牌 🔑
- [Nebius](https://studio.nebius.com/) API 密钥 🔑

## 安装 Installation ⚙️

1. 克隆仓库：
    
        git clone <repository-url>
        cd review-intelligence-agent

2. 安装依赖：
    
        pip install -r requirements.txt

3. 在项目根目录创建 `.env` 文件并填入你的 API 密钥：
    
        NEBIUS_API_KEY=your_nebius_api_key
        BRIGHT_DATA_API_TOKEN=your_bright_data_token
        WEB_UNLOCKER_ZONE=your_web_unlocker_zone
        BROWSER_ZONE=your_browser_zone

## 使用 Usage ▶️

1. 在 `review_intelligence.py` 中更新 `product_urls` 列表为你的目标评论页面 📝
2. 运行脚本：
    
        python review_intelligence.py

## 输出 Output 📤

脚本将输出包含以下内容的 JSON 分析：
- 带有元数据的已提取评论 🗂️
- 关键方面的情感分析分数 🎯
- 业务洞察与建议 🧠💡

## 配置 Configuration ⚙️📝

你可以通过修改 `review_intelligence.py` 中的代理配置自定义分析：
- 调整 LLM 模型参数 🧩
- 修改方面类别与关键词 📝
- 配置任务参数与预期输出 🎛️
