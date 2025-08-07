# 🥋 nomuraya-dojo

> **Claudeアーティファクトから生まれるインタラクティブ教材道場**

[![Organization](https://img.shields.io/badge/GitHub-nomuraya--dojo-181717?logo=github)](https://github.com/nomuraya-dojo)
[![Repositories](https://img.shields.io/badge/dynamic/json?color=blue&label=Repositories&query=%24.public_repos&url=https%3A%2F%2Fapi.github.com%2Forgs%2Fnomuraya-dojo)](https://github.com/nomuraya-dojo?tab=repositories)
[![Total Tools](https://img.shields.io/badge/Tools-50+-green)](#current-dojos)

---

## 🎯 Mission

**従来の課題を解決する新しい学習プラットフォーム**

- 🔍 **課題**: Claudeアーティファクトがチャットスレッドに埋もれてしまう
- 🏗️ **解決**: 領域別に体系的にアーカイブ・ホスティング
- 🌐 **価値**: 安定した環境での実践的な学習体験を提供

```
Claude Chat → Artifact → GitHub Repository → Cloudflare Pages
     ↓            ↓            ↓                ↓
   対話生成    → HTML/React → 領域別管理    → 統合ホスティング
```

---

## 🏮 Current Dojos

| 道場 | 領域 | 教材数 | ホスティング | 状態 |
|------|------|--------|-------------|------|
| **ITpassport** | 情報処理基礎・資格対策 | 8+ | [itpassport-dojo.pages.dev](https://itpassport-dojo.pages.dev) | 🟡 準備中 |
| **Marketing** | マーケティング戦略・分析 | 12+ | [marketing-dojo.pages.dev](https://marketing-dojo.pages.dev) | 🟢 運用中 |
| **Programming** | 開発スキル・コーディング | 15+ | [programming-dojo.pages.dev](https://programming-dojo.pages.dev) | 🟡 準備中 |
| **Leadership** | チーム運営・DX推進 | 6+ | [leadership-dojo.pages.dev](https://leadership-dojo.pages.dev) | 🔴 計画中 |
| **DataAnalysis** | データ可視化・分析 | 10+ | [dataanalysis-dojo.pages.dev](https://dataanalysis-dojo.pages.dev) | 🔴 計画中 |

### 🚀 Quick Access
各道場の **ライブデモ** は上記リンクから直接アクセス可能です。ブラウザ上でインタラクティブに学習できます。

---

## 🛠️ Architecture

```
GitHub Organization (nomuraya-dojo)
├── .github                 # Organization設定・プロフィール
├── ITpassport             # ITパスポート試験対策
├── Marketing              # マーケティング教材
├── Programming            # プログラミング学習
├── Leadership             # リーダーシップ開発
└── DataAnalysis           # データ分析・可視化
         ↓
   Cloudflare Pages        # 自動デプロイ・ホスティング
         ↓  
    Public Web Access      # https://*.pages.dev
```

**Tech Stack**: Claude + GitHub + Cloudflare Pages + HTML5/CSS3/JavaScript/React/Vue.js

---

## 🎓 How to Use

### 1. 🎯 目的の道場を選択
上記の **Current Dojos** から、学習したい領域を選択

### 2. 🌐 ライブデモにアクセス  
各道場のホスティングURLをクリック

### 3. 🛠️ インタラクティブに学習
ブラウザ上で直接操作・実践

### 4. 📚 ソースコード確認
必要に応じてGitHubリポジトリでコード学習

---

## 🤝 Contributing

### 🆕 新しい教材を提案したい
- [🏮 新dojo提案](../../issues/new?template=dojo_request.yml) - 新しい領域の道場提案
- [✨ 機能要望](../../issues/new?template=feature_request.yml) - 既存教材の改善提案

### 🐛 不具合を報告したい  
- [🐛 バグ報告](../../issues/new?template=bug_request.yml) - 教材の動作不良報告

### 📖 詳細ガイド
- [📋 貢献ガイド](./docs/CONTRIBUTING.md) - 詳細な貢献方法
- [📘 教材作成ガイド](./docs/GUIDELINES.md) - 教材作成のベストプラクティス

---

## 🔗 Links & Resources

### 🏢 Organization
- **GitHub**: [nomuraya-dojo](https://github.com/nomuraya-dojo)
- **Issues**: [全道場横断的な要望・報告](https://github.com/nomuraya-dojo/.github/issues)
- **Discussions**: [コミュニティ](https://github.com/nomuraya-dojo/.github/discussions)

### 📚 Individual Repositories  
- [🖥️ ITpassport](https://github.com/nomuraya-dojo/ITpassport) - 情報処理基礎・資格対策
- [📈 Marketing](https://github.com/nomuraya-dojo/Marketing) - マーケティング戦略・分析
- [💻 Programming](https://github.com/nomuraya-dojo/Programming) - プログラミング学習
- [👑 Leadership](https://github.com/nomuraya-dojo/Leadership) - リーダーシップ開発
- [📊 DataAnalysis](https://github.com/nomuraya-dojo/DataAnalysis) - データ分析・可視化

---

## 🎊 Recent Updates

- **2025-08** `.github` 環境構築・Organization統合完了
- **2025-08** Marketing dojo 本格運用開始
- **2025-08** ITpassport dojo 準備完了間近  

---

<div align="center">

### 🌟 道場で技を磨き、実践で力を試す

**継続的な改善により、より良い学習体験を提供します** 🚀

---

*Built with ❤️ and Claude | Last Updated: 2025年8月*

</div>