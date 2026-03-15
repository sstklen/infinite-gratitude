[English](../README.md) · [中文版](README.zh.md)

# 🐾 無限貓報恩 | Infinite Gratitude | 無限の恩返し

[![GitHub stars](https://img.shields.io/github/stars/sstklen/infinite-gratitude?style=social)](https://github.com/sstklen/infinite-gratitude)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **10個の並列リサーチエージェントを派遣する** — 研究チームが同時に働いてくれるような体験

## ⚡ クイックスタート

```bash
# インストール（コマンド1つ！）
curl -sSL https://raw.githubusercontent.com/sstklen/infinite-gratitude/main/infinite-gratitude.skill.md \
  -o ~/.claude/skills/infinite-gratitude.skill.md

# Claude Codeで使用
/infinite-gratitude "あなたの調査テーマ"
```

## 💡 何をするのか

**問題：** 深いリサーチには何時間もかかります。論文を読んだり、ツールを比較したり、競合を分析したり — 一人でできることには限りがあります。

**解決策：** 複数のAIエージェントを並列で派遣します。各エージェントが異なる角度でリサーチし、結果を持ち帰ります。

```
あなた：「ペットAI認識をリサーチして」
     ↓
🐱🐱🐱🐱🐱 5つのエージェントが出発（並列）
     ↓
📊📊📊📊📊 それぞれがレポートを持ち帰る
     ↓
あなた：「いいね！ArcFaceをもっと深く調べて...」
     ↓
🔄 満足するまでループ
```

**猫がプレゼントを持って帰るように** — ねずみ、虫、葉っぱ。このスキルは、あなたが止めるまでリサーチの発見を持ち帰り続けます。

## 📊 実際の結果：ペットAIリサーチ

28匹の猫と犬を認識するAIシステムの構築リサーチにこのスキルを使いました。

| 指標 | 結果 |
|--------|--------|
| リサーチトピック | 12件 |
| 派遣エージェント数 | 10（並列）|
| 生成レポート | 9件 |
| 所要時間 | 30分（手動なら20時間以上）|
| 重要な発見 | Petnow 99%精度の秘密 |

### 作成されたレポート

| # | レポート | 主な発見 |
|---|--------|-------------|
| 1 | 競合分析 | Petnowが99%の精度でリード |
| 2 | データセット調査 | Oxford-IIIT Petは商用利用可能 |
| 3 | 技術ロードマップ | 安定性ではArcFace > Triplet Loss |
| 4 | GitHubプロジェクト | MegaDescriptorが最高の事前学習モデル |
| 5 | HuggingFaceモデル | 汎用にDINOv2、動物にMegaDescriptor |
| 6 | Petnow深堀り | Siamese + Self-Attention + 20万件データ |
| 7 | 損失関数ガイド | ArcFace vs Tripletの比較 |
| 8 | ビジネスモデル | ペット保険が収益の要 |
| 9 | データ公式 | 1万→85%、5万→92%、20万→99% |

**結果：** 77.6%の精度を達成。90%以上への明確なロードマップあり。

## 🔧 設定

```bash
# 基本的な使い方
/infinite-gratitude "トピック"

# 深いリサーチ（より徹底的）
/infinite-gratitude "RAGのベストプラクティス" --depth deep

# エージェント数の制御
/infinite-gratitude "ベクターデータベース" --agents 10

# 複数ウェーブ
/infinite-gratitude "埋め込みモデル" --waves 5
```

| パラメーター | デフォルト | 説明 |
|-----------|---------|-------------|
| `--depth` | `normal` | `quick`（素早い）、`normal`（通常）、`deep`（深い）|
| `--agents` | `5` | 並列エージェント数（1-10）|
| `--waves` | `3` | リサーチの繰り返し回数 |

## 🎯 最適なユースケース

| ユースケース | なぜ効果的か |
|----------|--------------|
| **技術リサーチ** | 10のツール/ライブラリを同時に比較 |
| **競合分析** | 各エージェントが異なる競合を分析 |
| **文献レビュー** | 論文の並列読書と要約 |
| **市場調査** | 多角的な業界分析 |
| **デューデリジェンス** | 包括的な背景調査 |

## 📁 ファイル構成

```
├── infinite-gratitude.skill.md   # ← これをインストール！
├── infinite-gratitude-story.md   # 誕生の全ストーリー
└── docs/                         # 追加ドキュメント
```

## 🐾 誕生ストーリー

日本の房総半島に、**和心村**という28匹の猫と犬が暮らす場所があります。そのAI認識プラットフォームを構築する際、一人でこなせる量を超えたリサーチが必要でした。

そこで、村の猫のようにAIエージェントに働いてもらうことにしました：**出かけて、プレゼントを持ち帰って、また繰り返す。**

「無限の恩返し」という名前は、猫が「プレゼント」を持ち帰る行動から — 感謝を伝える猫なりの方法です。

> 全ストーリー：[infinite-gratitude-story.md](../infinite-gratitude-story.md)

---

## 📜 ライセンス

MIT License

---

*和心村が 🐾 を込めてお届けします — 和牠一起，療癒全世界*
