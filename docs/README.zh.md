[English](../README.md) · [日本語](README.ja.md)

# 🐾 無限貓報恩 | Infinite Gratitude | 無限の恩返し

[![GitHub stars](https://img.shields.io/github/stars/sstklen/infinite-gratitude?style=social)](https://github.com/sstklen/infinite-gratitude)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **同時派出 10 個平行研究代理** — 就像有一整個研究團隊同時為你工作

## ⚡ 快速開始

```bash
# 安裝（一個指令搞定！）
curl -sSL https://raw.githubusercontent.com/sstklen/infinite-gratitude/main/infinite-gratitude.skill.md \
  -o ~/.claude/skills/infinite-gratitude.skill.md

# 在 Claude Code 中使用
/infinite-gratitude "你的研究主題"
```

## 💡 它做什麼

**問題：** 深度研究要花好幾個小時。讀論文、比較工具、分析競品 — 一個人能做的有限。

**解法：** 同時派出多個 AI 代理。每個代理研究不同角度，然後帶著發現回來。

```
你：「研究寵物 AI 辨識」
     ↓
🐱🐱🐱🐱🐱 5 個代理出去（平行）
     ↓
📊📊📊📊📊 每個帶回一份報告
     ↓
你：「很好！現在深入研究 ArcFace...」
     ↓
🔄 不斷循環直到滿意
```

**就像貓咪帶禮物回家** — 老鼠、蟲子、樹葉。這個 skill 會持續帶回研究發現，直到你說停。

## 📊 真實成果：寵物 AI 研究

我們用這個 skill 研究如何為 28 隻貓狗建立 AI 辨識系統。

| 指標 | 結果 |
|--------|--------|
| 研究主題 | 12 個 |
| 派出代理數 | 10（平行）|
| 產出報告 | 9 份 |
| 花費時間 | 30 分鐘（手動需 20+ 小時）|
| 關鍵發現 | Petnow 99% 準確率的秘密 |

### 產出的報告

| # | 報告 | 關鍵發現 |
|---|--------|-------------|
| 1 | 競品分析 | Petnow 以 99% 準確率領先 |
| 2 | 資料集調查 | Oxford-IIIT Pet 可商業使用 |
| 3 | 技術路線圖 | 穩定性方面 ArcFace > Triplet Loss |
| 4 | GitHub 專案 | MegaDescriptor 是最佳預訓練模型 |
| 5 | HuggingFace 模型 | DINOv2 適合通用，MegaDescriptor 適合動物 |
| 6 | Petnow 深度研究 | Siamese + Self-Attention + 20 萬筆資料 |
| 7 | 損失函數指南 | ArcFace vs Triplet 比較 |
| 8 | 商業模式 | 寵物保險是主要獲利點 |
| 9 | 資料公式 | 1 萬→85%，5 萬→92%，20 萬→99% |

**結果：** 達到 77.6% 準確率，有清晰路線圖可達 90%+。

## 🔧 參數設定

```bash
# 基本用法
/infinite-gratitude "主題"

# 深度研究（更徹底）
/infinite-gratitude "RAG 最佳實踐" --depth deep

# 控制代理數量
/infinite-gratitude "向量資料庫" --agents 10

# 多輪研究
/infinite-gratitude "嵌入模型" --waves 5
```

| 參數 | 預設值 | 說明 |
|-----------|---------|-------------|
| `--depth` | `normal` | `quick`（快速）、`normal`（正常）、`deep`（深度）|
| `--agents` | `5` | 平行代理數（1-10）|
| `--waves` | `3` | 研究迭代輪數 |

## 🎯 最佳使用場景

| 使用場景 | 為什麼有效 |
|----------|--------------|
| **技術研究** | 同時比較 10 個工具/函式庫 |
| **競品分析** | 每個代理分析不同競品 |
| **文獻回顧** | 平行閱讀並摘要論文 |
| **市場研究** | 多角度產業分析 |
| **盡職調查** | 全面性背景調查 |

## 📁 檔案結構

```
├── infinite-gratitude.skill.md   # ← 安裝這個！
├── infinite-gratitude-story.md   # 完整起源故事
└── docs/                         # 補充文件
```

## 🐾 起源故事

在日本房總半島，**和心村**住著 28 隻貓狗。在建立他們的 AI 辨識平台時，研究量超過一個人能負荷的。

所以我們讓 AI 代理像村裡的貓一樣工作：**出去、帶禮物回來、不斷重複。**

「無限報恩」這個名字來自貓咪把「禮物」帶回家 — 牠們表達謝意的方式。

> 完整故事：[infinite-gratitude-story.md](../infinite-gratitude-story.md)

---

## 📜 授權條款

MIT License

---

*由和心村用 🐾 打造 — 和牠一起，療癒全世界*
