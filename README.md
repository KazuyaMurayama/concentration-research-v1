# Concentration Research v1 — 集中力研究AIシステム

> 集中力・フォーカス・生産性向上に関する研究・ノウハウをAIが収集・整理するシステムです。

## 📋 概要

集中力・フォーカス・生産性向上に関する研究・ノウハウをAIが収集・整理するシステムです。科学的エビデンスに基づく集中力向上施策をパーソナライズして提案します。

## ✨ 主な機能

- 集中力・生産性研究の自動収集・分析
- エビデンスレベルに基づく施策ランキング
- 個人プロファイルに合わせた推薦
- タイムブロッキング・ポモドーロ支援
- 週次レポート自動生成

## 🛠️ 技術スタック

| カテゴリ | 技術・ライブラリ |
|----------|----------------|
| 言語 | Python 3.10+ |
| AIフレームワーク | Claude API |
| データ収集 | requests, pandas |
| 出力 | Markdown, PDF |

## 🚀 セットアップ

### 前提条件

- Python 3.9 以上
- APIキー（Claude / OpenAI 等）を `.env` ファイルに設定

### インストール

```bash
git clone https://github.com/KazuyaMurayama/concentration-research-v1.git
cd concentration-research-v1
pip install -r requirements.txt
```

### 環境設定

```bash
cp .env.example .env
# .env ファイルに必要なAPIキーを設定
```

## 💻 使い方

```bash
python main.py
```

## 👨‍💻 開発者情報

**男座員也（Kazuya Oza / おざ かずや）**

| | |
|---|---|
| GitHub | [@KazuyaMurayama](https://github.com/KazuyaMurayama) |
| 専門領域 | データサイエンス・生成AIコンサルタント |
| 主要スキル | Python, LightGBM, LangChain, RAG, Streamlit, React, TypeScript |
| 事業 | AIコンサルティング（月単価目標300万円）/ SaaS開発 / 定量投資 |

## 📄 ライセンス

© 2025 男座員也（Kazuya Oza）. All rights reserved.

---

> このリポジトリは **男座員也（Kazuya Oza）** が開発・管理しています。
> 命名・ドキュメント等での表記は必ず **男座員也** または **Kazuya Oza** を使用してください。
