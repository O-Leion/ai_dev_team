# 仮想 AI 開発チーム (Virtual AI Development Team)

このプロジェクトは、AI エージェントと連携して高品質なソフトウェアを開発するための、高度に構造化された「仮想開発チーム」の基盤リポジトリです。

## プロジェクトの目的

個人開発者が、プロジェクトマネージャー（PM）やエンジニア、デザイナーといった専門家チームを AI エージェントとして「召集」し、Python / Docker / オンプレミス 環境で効率的かつ堅牢に開発を進めるための土台を提供します。

## 標準技術スタック (Tech Stack)

クライアント（ユーザー）が内容を把握・メンテナンスしやすい構成を採用しています。

- 言語: Python 3.12+ (Type Hinting 必須)
- パッケージ管理: uv (Fast & Modern)
- 実行環境: Docker / Docker Compose (On-premise 優先)
- 品質管理: Ruff (Lint/Format), Pytest (Testing), Pyright/Mypy (Type Check)
- 開発手法: ハイブリッド・スクラム (設計は堅実に、開発は柔軟に)

## チーム構成 (Team Roles)

プロジェクトの要件に応じて、チーム選定ガイドライン (docs/team/SELECTION_GUIDE.md) に従い、以下の役割をアサインします。

- PM (Project Manager): 全体進行・要件定義・メイン窓口 (docs/team/roles/PM.md)
- PL (Project Leader): 技術選定・設計・コード品質・技術窓口 (docs/team/roles/PL.md)
- AI Engineer: LLM統合・RAG実装・AI精度評価 (docs/team/roles/AI_ENGINEER.md)
- Backend: Python/FastAPI による API 開発・DB設計 (docs/team/roles/BACKEND.md)
- Frontend: UI実装・API連携・状態管理 (docs/team/roles/FRONTEND.md)
- DevOps: Docker環境構築・オンプレ運用・CI/CD (docs/team/roles/DEVOPS.md)
- Security: 脆弱性診断・認証認可設計・安全性担保 (docs/team/roles/SECURITY.md)
- QA: テスト計画・自動テスト・品質保証 (docs/team/roles/QA.md)
- Designer: UI/UX設計・プロトタイプ作成 (docs/team/roles/DESIGNER.md)

## ガイドライン (Standard Documents)

- 標準技術ガイドライン (docs/standard/GUIDELINE.md): 使用技術の詳細
- 開発手法ガイドライン (docs/standard/METHODOLOGY.md): プロセスの進め方
- 品質管理ガイドライン (docs/standard/QUALITY_CONTROL.md): テストと静的解析の基準

## AI 連携 (AI Compatibility)

以下の AI ツール向けに最適化された指示ファイルが同梱されています。

- Gemini CLI: GEMINI.md
- Claude Code: CLAUDE.md
- GitHub Copilot: .github/copilot-instructions.md
- Codex / AI Editors: .codex

## 開発の始め方

1. 要件定義: PM/PL に「何を作りたいか」を伝えます。
2. メンバー選定: SELECTION_GUIDE.md に基づき、必要な役割を特定します。
3. 環境構築: uv sync で依存関係をインストールし、docker compose up -d でインフラを起動します。
4. 実装: スプリント単位で開発を進め、pytest と ruff で品質をチェックします。

## ライセンス (License)

This project is licensed under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2026 O-Leion

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---
© 2026 [O-Leion](https://github.com/O-Leion)
