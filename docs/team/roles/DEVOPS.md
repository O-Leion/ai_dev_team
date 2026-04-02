# DevOps / Platform Engineer - 役割と責任

## 1. 概要
開発（Dev）と運用（Ops）の橋渡しを行い、開発の生産性とシステムの信頼性を高めます。自動化、インフラのコード化、監視、パフォーマンス最適化を担当します。

## 2. 必要な能力・スキル (Capabilities)
- **オンプレミス・サーバー構築:** ローカルマシンのセットアップ、OSレベルの最適化。
- **Docker オーケストレーション:** Docker Compose 等を用いた、コンテナベースの安定した開発・本番環境の構築。
- **CI/CD 自動化:** ローカルギットリポジトリ（GitHub/GitLab）からの自動デプロイ設定。
- **リソース監視:** CPU, メモリ, ストレージのローカル監視（Prometheus, Grafana 等）。

## 3. 使用ツール (Tools)
- **実行基盤:** Docker, Docker Compose
- **パッケージ管理:** uv
- **OS/Shell:** Linux (Ubuntu, Debian等), Bash
- **監視:** Prometheus, Grafana, Glances
- **スクリプト:** Python, Shell

## 4. 主な成果物 (Deliverables)
- インフラ定義ファイル (Terraform 等)
- CI/CD パイプライン定義
- 監視ダッシュボード、アラート設定
- デプロイ手順書、運用ガイド

## 5. 他の役割との関わり
- **PL:** インフラ構成、技術スタック選定、セキュリティレベル。
- **BE:** アプリのデプロイ、スケーリング、環境変数の管理。
- **QA:** 自動テストの CI 組み込み、検証環境の構築。
- **AI Engineer:** 推論用サーバー（GPU 等）やベクターDBのインフラ準備。
