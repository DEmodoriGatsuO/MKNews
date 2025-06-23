# AI Tech Trends Digest (2025-06-23)


## Top Tech Articles from Qiita


### [AI Agent Manager (AAM) として生きていく : 作業環境とワークフローの設計](https://qiita.com/icoxfog417/items/f15e92f05b14411fd642)
**Published:** 2025-06-22 15:37:26 UTC
**Likes:** 19
**Tags:** 機械学習, GenerativeAI, Claude, AmazonQ, ClaudeCode

**Digest:**
20XX年、AI Agentが開発の中心となり、AI Agent Manager（AAM）の役割が重要に。著者は、AI Agent をマネジメントするAAMとして、環境整備（コンテキスト付与、MCP Server活用）とワークフロー設計（タスクの明確化、PDCAサイクル）を実践。最終的には、AIエージェントの振る舞いを学習させるFine Tuningが重要になると提唱。AAMには、並行作業環境設計、コマンド設計、ナレッジ統合など、多様なスキルが求められる。

---

### [Snowflake Cortex AISQLのAI_AGG関数を試してみる](https://qiita.com/abe_masanori/items/18b143193c9f84a15a6c)
**Published:** 2025-06-22 14:01:53 UTC
**Likes:** 2
**Tags:** Snowflake, LLM, SnowflakeCortex, AI_AGG

**Digest:**
Snowflake Cortexの**AISQL**、特に**AI_AGG関数**を試用。レビューコメント要約、レビュー点分析など、SQL内でLLM機能を活用。AI_AGGは複数テキストの集約に有効だが、**プロンプト**にデータの意味を明記する必要あり。**null**は除外、複数列分析はJSON化で対応可能。Llama系LLM利用の可能性を示唆。大規模データへの対応も興味深い。消費トークンは確認可能で、0.2ドル程度のコストだった。

---

### [AIは、コーヒーの「心」を読めるか？- FlutterとGeminiで、最強の「AI焙煎メンター」を創る話【アプリ設計全公開】](https://qiita.com/takutosat/items/b157468eca9b2f412979)
**Published:** 2025-06-23 04:00:55 UTC
**Likes:** 1
**Tags:** AI, Firebase, Flutter, 個人開発, Gemini

**Digest:**
手回し焙煎ログアプリ開発の記録。FlutterとFirebase、Gemini APIを使い、CRUD、AI分析、UI更新、入力体験を実装。設計はシンプルで拡張性あるFirestore、AI連携は非同期UXとStreamBuilder。Xcode警告やカレンダー表示問題も解決。M1/M2 Macでのpod、非同期UIの注意点などFlutter, Firebase開発のTipsを紹介。

---

### [【Claude Code】Vibe Codingで自分用のQiita分析ツールを作ってみた](https://qiita.com/ryu-ki/items/783397f8955acf8cd1f9)
**Published:** 2025-06-22 23:50:04 UTC
**Likes:** 1
**Tags:** 初心者, やってみた, 個人開発, Claude, VibeCoding

**Digest:**
Claude Codeを使用して、Qiita投稿分析ツールを開発した体験を紹介。**Claude Code**でPython、DuckDB、Streamlitを活用し、CLI版とWeb版ダッシュボードを完成。技術的なハードルを乗り越え、**アイデア具現化**の喜びを実感。開発者の役割は「How」から「What/Why」へシフト。CLAUDE.mdでのルール設定や段階的な指示が重要。**個人開発**の可能性を広げるAIツールとして、今後の活用に期待。

---

### [TDD（テスト駆動開発）を自動化するAIエージェント](https://qiita.com/ymgc3/items/185ae41978f83f0c4152)
**Published:** 2025-06-22 08:53:23 UTC
**Likes:** 1
**Tags:** Python, TDD, AI, LLM, AIエージェント

**Digest:**
TDD自動化エージェントシステムは、自然言語での開発目標から、テスト生成、実装、リファクタリング、品質分析を自動化するAIです。unittest/pytest対応で、テストケース生成、最小実装、コード品質分析、自動リファクタリング、テスト実行・カバレッジ測定、レポート生成などを行います。設定ファイルで、最大サイクル数や品質閾値をYAML形式で管理します。

---

## Latest News from RSS Feeds


### [Surface のセキュリティ: 1 年を振り返って](https://blogs.windows.com/japan/2025/06/23/surfaceitpro-surface-security-year-in-review/)
**Source:** Windows Blog for Japan
**Published:** 2025-06-23 05:34:18 UTC
**Tags:** Surface, Surface security

**Digest:**
Microsoft Surface は、設計段階からのセキュリティを重視し、チップからクラウドまで安全なエクスペリエンスを提供。CISA の Secure by Design 誓約に準拠し、安全な開発ライフサイクルを構築。Rust を活用した UEFI、MCU、ドライバー開発でメモリ安全性を向上。Windows Hello や Microsoft Defender などの保護機能も提供。Copilot+ PC では Pluton セキュリティプロセッサを搭載し、デバイスの安全性を高めています。

---

### [【AWS】AWS Configでリソースタグのチェックをする-AWS Config有効化編-](https://blog.jbs.co.jp/entry/2025/06/23/090838)
**Source:** JBS Blog
**Published:** 2025-06-23 00:08:38 UTC
**Tags:** AWS, AWS Config

**Digest:**
AWS Config マネージドルールでリソースタグをチェックする設定手順を紹介。今回は、AWS Config のセットアップ方法に焦点を当てています。タグの重要性に着目し、リソース管理におけるタグ活用の第一歩となる、Config の導入方法を解説します。

---