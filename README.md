# daily_rr - Ruby/Rails 学習リポジトリ

![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)

## 📚 概要

本リポジトリは、Ruby/Railsの知識習得と定着を目的とした日々の学習記録です。Discord上で対話型AIアシスタントとクイズ形式で学習した内容をドキュメント化しています。

Ruby技術者認定試験（Silver）の対策や実務で必要な知識を中心に、毎日3問のドリル形式で学習を進めています。

## 🎯 学習の流れ

1. Discord上でAIアシスタント「cacao」（Clawdbot/Moltbotの愛称）にクイズ出題を依頼
2. 1セッション3問の問題に回答
3. 即時フィードバックと解説を受ける
4. 学習内容を`drills/YYYY-MM-DD-N.md`形式でドキュメント化
5. リポジトリにコミットしてナレッジベースを構築

## 📋 学習スタイル

- **学習形式**: クイズ形式（1問ずつ出題 → 回答 → 解説）
- **所要時間**: 1セッション約10分
- **難易度**: 基礎〜中級（Ruby Silver試験範囲 + Rails基礎）
- **学習テーマ**:
  - Ruby文法・メソッド
  - Rails規約・ヘルパー
  - よくあるミス・落とし穴

## 🔄 復習システム

本リポジトリでは、効果的な学習のため以下の復習システムを導入しています：

- **デイリーリプレイ**: 前日の学習内容、特に間違えた問題を再確認
- **ウィークリーチャレンジ**: 毎週日曜日に直近1週間の問題から5問をランダム出題
- **定期リマインダー**: 日曜06:00(JST)に週間復習の提案通知

## 📁 ディレクトリ構造

- **drills/**: 日別の学習記録（YYYY-MM-DD-N.md形式）
  - 問題、選択肢
  - 解答と詳細な解説
  - 関連する公式リファレンスへのリンク
  - セッション結果のまとめ

## 👨‍💻 運用ルール

- 新しい学習内容は必ずブランチを作成してPRで管理
- `main`ブランチへは直接プッシュしない
- 解説には可能な限り公式リファレンスへのリンクを含める
- ファイル命名規則: `drills/YYYY-MM-DD-N.md` (Nはその日のセッション番号)

## 📚 参考リソース

- [Ruby リファレンスマニュアル](https://docs.ruby-lang.org/ja/latest/doc/index.html)
- [Ruby on Rails ガイド](https://railsguides.jp/)

## ⚙️ 技術情報

- **AIアシスタント**: cacao (Clawdbot/Moltbotの愛称)
- **学習環境**: Discord上でのインタラクティブなセッション
- **ドキュメント化**: Markdownを使用した構造化されたドキュメント
- **品質管理**: Gemini Code Assistによる自動PRレビューで情報の正確性を向上

## 💡 このリポジトリの活用方法

- Rubyの基本文法の復習
- Rails開発の際のリファレンスとして
- プログラミングの面接対策
- Ruby技術者認定試験の準備

---

*このリポジトリは学習目的で作成されたものです。誤りや改善点があればIssueやPRでフィードバックいただけると幸いです。*