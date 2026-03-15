[中文版](docs/README.zh.md) · [日本語版](docs/README.ja.md)

# 🐾 無限貓報恩 | Infinite Gratitude | 無限の恩返し

[![GitHub stars](https://img.shields.io/github/stars/sstklen/infinite-gratitude?style=social)](https://github.com/sstklen/infinite-gratitude)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Dispatch 10 parallel research agents** — like having a team of researchers working for you simultaneously

## ⚡ Quick Start

```bash
# Install (one command!)
curl -sSL https://raw.githubusercontent.com/sstklen/infinite-gratitude/main/infinite-gratitude.skill.md \
  -o ~/.claude/skills/infinite-gratitude.skill.md

# Use in Claude Code
/infinite-gratitude "your research topic"
```

## 💡 What It Does

**Problem:** Deep research takes hours. Reading papers, comparing tools, analyzing competitors — one person can only do so much.

**Solution:** Dispatch multiple AI agents in parallel. Each agent researches a different angle, then brings findings back.

```
You: "Research pet AI recognition"
     ↓
🐱🐱🐱🐱🐱 5 agents go out (parallel)
     ↓
📊📊📊📊📊 Each brings back a report
     ↓
You: "Great! Now go deeper on ArcFace..."
     ↓
🔄 Loop until satisfied
```

**Like cats bringing gifts home** — mice, bugs, leaves. This skill keeps bringing research findings until you say stop.

## 📊 Real Results: Pet AI Research

We used this skill to research building an AI system for recognizing 28 cats & dogs.

| Metric | Result |
|--------|--------|
| Research Topics | 12 |
| Agents Deployed | 10 (parallel) |
| Reports Generated | 9 |
| Time | 30 minutes (vs 20+ hours manual) |
| Key Discovery | Petnow's 99% accuracy secret |

### Reports Produced

| # | Report | Key Finding |
|---|--------|-------------|
| 1 | Competitor Analysis | Petnow leads with 99% accuracy |
| 2 | Dataset Survey | Oxford-IIIT Pet is commercially safe |
| 3 | Technical Roadmap | ArcFace > Triplet Loss for stability |
| 4 | GitHub Projects | MegaDescriptor is the best pretrained model |
| 5 | HuggingFace Models | DINOv2 for general, MegaDescriptor for animals |
| 6 | Petnow Deep Dive | Siamese + Self-Attention + 200K data |
| 7 | Loss Function Guide | ArcFace vs Triplet comparison |
| 8 | Business Model | Pet insurance is the money maker |
| 9 | Data Formula | 10K→85%, 50K→92%, 200K→99% |

**Outcome:** Achieved 77.6% accuracy, with clear roadmap to 90%+.

## 🔧 Configuration

```bash
# Basic usage
/infinite-gratitude "topic"

# Deep research (more thorough)
/infinite-gratitude "RAG best practices" --depth deep

# Control agent count
/infinite-gratitude "vector databases" --agents 10

# Multiple waves
/infinite-gratitude "embedding models" --waves 5
```

| Parameter | Default | Description |
|-----------|---------|-------------|
| `--depth` | `normal` | `quick`, `normal`, `deep` |
| `--agents` | `5` | Parallel agents (1-10) |
| `--waves` | `3` | Research iterations |

## 🎯 Best Use Cases

| Use Case | Why It Works |
|----------|--------------|
| **Technical Research** | Compare 10 tools/libraries simultaneously |
| **Competitor Analysis** | Each agent analyzes a different competitor |
| **Literature Review** | Parallel paper reading and summarization |
| **Market Research** | Multi-angle industry analysis |
| **Due Diligence** | Comprehensive background checks |

## 📁 Files

```
├── infinite-gratitude.skill.md   # ← Install this!
├── infinite-gratitude-story.md   # Full origin story
└── docs/                         # Additional documentation
```

## 🐾 Origin Story

In Japan's Boso Peninsula, **Washin Village** is home to 28 cats and dogs. While building their AI recognition platform, there was too much research for one person.

So we made AI agents work like village cats: **go out, bring gifts back, repeat.**

The name "Infinite Gratitude" (無限報恩) comes from cats bringing "gifts" home — their way of saying thanks.

> Full story: [infinite-gratitude-story.md](infinite-gratitude-story.md)

---

## 📜 License

MIT License

## Pair With | 搭配使用 | 組み合わせ

- **YES.md** ([`sstklen/yes.md`](https://github.com/sstklen/yes.md)) — Keep your 10 research agents honest: safety gates, evidence rules, anti-slack detection. | 讓研究 Agent 守規矩：安全閘門 + 證據規則 | エージェントを規律正しく：安全ゲート＋証拠ルール
- **5x-cto** ([`sstklen/5x-cto`](https://github.com/sstklen/5x-cto)) — Done researching? Build it. Full dev pipeline from requirements to delivery. | 查完了？來蓋。完整開發流水線 | リサーチ完了？構築しよう。完全開発パイプライン

---

*Made with 🐾 by Washin Village — 和牠一起，療癒全世界*
