# 📝 Copywriting — 专业文案撰写 Skill

[![Version](https://img.shields.io/badge/version-1.1.0-blue)](https://github.com/wxie0815-arch/copywriting)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Compatible-green)](https://openclaw.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> 将结构化写作计划转化为高质量文案初稿。专为加密货币、Web3领域内容创作优化，支持9种文章风格。

## 🎯 功能概述

`copywriting` 是三阶段专业写作流程的**第二阶段**，负责将 `writing-plans` 生成的结构化写作计划转化为完整的文章初稿。

```
writing-plans  →  copywriting  →  humanizer-zh
   (规划阶段)      (撰写阶段)       (优化阶段)
```

## ✨ 核心特性

- **计划驱动写作**：严格遵循 `writing-plans` 输出的 JSON 计划，确保文章结构清晰、论点完整
- **风格多样化**：支持日常快讯、深度分析、KOL观点、教程科普、交易信号、项目研究等9种风格
- **风格指纹融合**：支持注入用户历史写作风格，确保文章个性化
- **市场数据融合**：自动将热门代币、市场情绪等数据融入文章内容
- **Markdown输出**：输出标准Markdown格式，直接可用于发布

## 🚀 快速开始

### 安装

```bash
gh repo clone wxie0815-arch/copywriting
```

### 在 binance-square-oracle 中使用

`copywriting` 已内置于 [binance-square-oracle](https://github.com/wxie0815-arch/binance-square-oracle) 预言机中，通过三阶段写作流程自动调用。

### 独立使用

详细的 Prompt 指令、输入输出格式和示例，请参考 `SKILL.md`。

## 🔗 相关 Skill

| Skill | 说明 | 仓库 |
|-------|------|------|
| `writing-plans` | 生成结构化写作计划 | [wxie0815-arch/writing-plans](https://github.com/wxie0815-arch/writing-plans) |
| `humanizer-zh` | 去除AI味，优化中文表达 | [wxie0815-arch/humanizer-zh](https://github.com/wxie0815-arch/humanizer-zh) |
| `binance-square-oracle` | 集成三阶段写作的完整预言机 | [wxie0815-arch/binance-square-oracle](https://github.com/wxie0815-arch/binance-square-oracle) |

## 📄 许可证

MIT License

---

## 💰 赞助支持

如果这个项目对您有帮助，欢迎赞助支持！

**BSC（BEP-20）钱包地址：**
`0x3B74BE938caB987120C3661C8e3161CD838e5a1A` 

支持 USDT / BNB / 任意 BEP-20 代币。感谢每一位支持者 🙏

**作者：** 无邪Infinity | 币安广场 [@wuxie](https://www.binance.com/en/square/profile/wuxie) | X [@wuxie149](https://x.com/wuxie149)
