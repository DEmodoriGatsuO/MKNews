# AI Tech Trends Digest (2025-10-05)


## Top Tech Articles from Qiita


### [M5Stack LLM8850 モジュールを Raspberry Pi 5 で動かしてみた(LLM編)](https://qiita.com/uzuki_aoba/items/78e1944b8ccb60107d5c)
**Published:** 2025-10-05 02:30:47 UTC
**Likes:** 2
**Tags:** RaspberryPi, M5stack, LLM

**Digest:**
Maker Faire Tokyo 2025 でスイッチサイエンスのブースで見かけた M5Stack LLM8850 モジュールは、AXERA AX8850 チップ搭載の AI アクセラレータ。Raspberry Pi 5 に M.2 HAT+ を介して接続し、公式手順で環境設定。ドライバインストール後、モデルベンチマークで動作確認。Qwen3-0.6B モデルを実行し、約13-14トークン/秒の速度を確認。

---

### [一次情報で政治を知る：日本語RAGシステムで高市早苗新総裁の公式サイトを分析](https://qiita.com/shinonome_taku/items/92abee445fe2804b8430)
**Published:** 2025-10-05 00:44:30 UTC
**Likes:** 1
**Tags:** Python, AI, OpenAI, rag, duckdb

**Digest:**
高市早苗氏の公式ウェブサイト情報を基にした、RAGシステム構築プロジェクト。一次情報へのアクセス困難を解決するため、**RAGLite**と**DuckDB**を採用し、**日本語対応**に特化した。**EmbeddingとReranker**の最適化、丁寧な**スクレイピング**で、一次情報を効率的に検索・質問できるWeb UIを開発。

---

### [AutoGen の進化の歴史を見てきたアーキテクトが分析する Microsoft Agent Framework の改良ポイント](https://qiita.com/nohanaga/items/2ed726f9a0ff092b3f36)
**Published:** 2025-10-04 15:44:35 UTC
**Likes:** 1
**Tags:** Microsoft, Azure, OpenAI, AutoGen

**Digest:**
Microsoft Agent Framework が発表。AutoGen の革新性と Semantic Kernel の安定性を目指し、2025年10月1日に登場。オープンソースで、チームは本番環境を気にせず展開可能。AutoGen の課題を解決する、統一ワークフロー、型安全性、Human-in-the-Loop ネイティブサポートなど、多数の改良を実現。コンテキストエンジニアリングの観点から、スレッドによる会話状態管理や、データフローベースのワークフローが特徴。

---

### [Claude Code に GitHub MCP サーバーを設定してみた](https://qiita.com/ymtdir/items/4d17b5ebac0b025eb825)
**Published:** 2025-10-04 14:12:09 UTC
**Likes:** 1
**Tags:** GitHub, AI, MCP, LLM, ClaudeCode

**Digest:**
Claude Code Proで**GitHub MCP**を設定し、IssueやPR管理を試みた。GitHub Personal Access Tokenを取得後、環境変数設定と`.mcp.json`ファイル作成で連携。Claude CodeでGitHub情報取得やIssue作成に成功。MCPで**外部ツール**との連携可能性を感じ、データベースやSlackなど他のMCPサーバーとの組み合わせにも期待。

---

### [Claude Desktop（Win）にAWS Knowledge MCP Serverを導入してみる](https://qiita.com/eiji-noguchi/items/d050715ee4c07131a6f8)
**Published:** 2025-10-04 12:43:26 UTC
**Likes:** 1
**Tags:** AWS, MCP, Claude, ClaudeDesktop, MCPサーバー

**Digest:**
AWS Knowledge MCP Serverが10/1にGAとなり、費用やAWSアカウント不要で利用可能になりました。Claude Desktopに設定を追加し、fastmcpユーティリティを利用します。`claude_desktop_config.json`を編集し、再起動後にサーバーが追加されていることを確認。AWSドキュメント検索ツールを活用し、Amazon Bedrockに関する質問への回答も生成されました。

---