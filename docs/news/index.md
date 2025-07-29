# AI Tech Trends Digest (2025-07-29)


## Top Tech Articles from Qiita


### [ LLMで作る「個人の好み×アイテム総当たりレコメンドシステム」- Pydantic AIで実装してみた](https://qiita.com/Tadataka_Takahashi/items/982fd5a84daf71b9df02)
**Published:** 2025-07-28 11:51:02 UTC
**Likes:** 2
**Tags:** Python, レコメンド, LLM, pydantic-ai

**Digest:**
LLMとPydantic AIを用いた**レコメンドシステム**構築。ユーザーの好みと全アイテムを総当たりで分析し、**Pydantic AI**で構造化された詳細な理由とスコア、避けるべきアイテムを提示。**カレー専門店**での実装例では、ベジタリアン向けや激辛好き向けなど、多様なニーズに合わせたレコメンドを実現。LLMの**言語理解力**により、詳細な説明と柔軟なレコメンドが可能に。

---

### [GeminiのCanvasで動く！カメラを使ったジェスチャー認識HTML](https://qiita.com/takatama/items/d4da6442038c7c05070a)
**Published:** 2025-07-28 10:59:55 UTC
**Likes:** 2
**Tags:** JavaScript, Gemini, MediaPipe

**Digest:**
GeminiのCanvasで、カメラを使ったWebアプリ開発が可能に。MediaPipeで手のジェスチャー認識も実現し、ピースサインなど6種類のサインに対応。HTMLコードを使い、Geminiに改造を依頼してスムーズな開発が可能です。MediaPipeは顔認識や物体検出など多様な機能を持ち、様々なアプリに応用できます。

---

### [AI エージェント開発の技術的負債を予防する : Amazon Bedrock AgentCore をゼロからまるっと体験](https://qiita.com/icoxfog417/items/f21bb92352277d2ddc66)
**Published:** 2025-07-29 05:50:56 UTC
**Likes:** 0
**Tags:** AWS, GenerativeAI, StrandsAgents, AgentCore

**Digest:**
AIエージェント開発の技術的負債を予防する「Amazon Bedrock AgentCore」を紹介。実装非依存のランタイム環境を提供し、LangChainなどのフレームワークを問わず利用可能。Code InterpreterやBrowserといったセキュアな実行環境も提供。2028年には業務の15%がAIエージェントで自律化すると予測され、負債蓄積対策が重要。

---

### [Claude Codeで実現！バラバラPDFを統一フォーマットに自動変換してみた](https://qiita.com/k_nabe/items/f0bbcf958871eba8b4c5)
**Published:** 2025-07-29 02:31:36 UTC
**Likes:** 0
**Tags:** API, 業務自動化, Claude, 実装事例

**Digest:**
PDFフォーマットの課題を、Claude×Claude Codeで20分で解決。要件定義、@docs参照、planモード活用で、バラバラなPDFを統一化するシステムを実装し、60倍の業務効率化を実現。OpenAIのStructured OutputでJSON構造化し、UIも完備。日本語フォント対応、OCR、非同期処理による高速化も。開発時間は20分で、ROIも抜群！

---

### [〇〇コーディングを整理してみた](https://qiita.com/sm_beats_keys/items/489d4b8eb783e93416ff)
**Published:** 2025-07-29 01:04:05 UTC
**Likes:** 0
**Tags:** AI, cursor, copilot, Claude, バイブコーディング

**Digest:**
AIを活用したコーディング手法の分類。**AIコーディング**は、AIがコード提案や補完を行う開発スタイル。**エージェンティックコード**は、AIエージェントが自律的にタスクを実行し、自動化。**バイブコーディング**は、自然言語指示でコード生成し、試行錯誤するスタイル。**プロンプトエンジニアリング**は、AIへの指示を最適化する技術。

---

## Latest News from RSS Feeds


### [Build a drug discovery research assistant using Strands Agents and Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/build-a-drug-discovery-research-assistant-using-strands-agents-and-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-07-28 19:14:26 UTC
**Tags:** Advanced (300), Amazon Bedrock, Artificial Intelligence, Life Sciences, Technical How-to

**Digest:**
創薬研究を加速するため、GenentechやAstraZenecaはAIエージェントを活用。本記事では、Strands Agents SDKとAmazon Bedrockを用いて、複数のデータベースを検索しレポート生成する研究アシスタントを構築する方法を解説。AnthropicのClaudeモデルを使用し、MCPツールでarXiv、PubMedなどを連携。専門エージェントによる情報収集と報告書作成の流れを紹介。

---

### [Amazon Nova Act SDK (preview): Path to production for browser automation agents](https://aws.amazon.com/blogs/machine-learning/amazon-nova-act-sdk-preview-path-to-production-for-browser-automation-agents/)
**Source:** AWS ML Blog
**Published:** 2025-07-28 17:54:35 UTC
**Tags:** Amazon Nova, Announcements

**Digest:**
Amazonは、ブラウザタスク自動化を実現するAgentic AI「Amazon Nova Act SDK」を発表、限定プレビューを開始しました。AWS IAM、S3、Bedrock AgentCore Browser Toolとの連携により、セキュアなブラウザ操作とデータ管理を実現。Pythonと自然言語でエージェントを記述し、CI/CDでデプロイ可能。金融、カスタマーサポート、QAなど幅広い業界で活用が見込まれます。

---

### [Optimizing enterprise AI assistants: How Crypto.com uses LLM reasoning and feedback for enhanced efficiency](https://aws.amazon.com/blogs/machine-learning/optimizing-enterprise-ai-assistants-how-crypto-com-uses-llm-reasoning-and-feedback-for-enhanced-efficiency/)
**Source:** AWS ML Blog
**Published:** 2025-07-28 17:53:04 UTC
**Tags:** Amazon Bedrock, Amazon Machine Learning, Artificial Intelligence, Customer Solutions

**Digest:**
Crypto.comがAWS上で生成AIアシスタントを導入。大規模言語モデル（LLM）の性能向上にはフィードバックと推論が重要で、事実確認ツールによる批判や、Amazon Bedrockを用いたモデルの最適化ワークフローを解説。顧客からの問い合わせ分類を例に、エラー分析とプロンプト改善を繰り返し、精度向上を図っています。

---

### [Build modern serverless solutions following best practices using Amazon Q Developer CLI and MCP](https://aws.amazon.com/blogs/machine-learning/build-modern-serverless-solutions-following-best-practices-using-amazon-q-developer-cli-and-mcp/)
**Source:** AWS ML Blog
**Published:** 2025-07-28 17:42:38 UTC
**Tags:** Amazon Q, AWS Serverless Application Model, AWS Serverless Application Repository, Best Practices, Technical How-to

**Digest:**
AWS Serverless MCPサーバーは、Amazon Q Developer CLIとModel Context Protocol (MCP)を活用し、AWS Lambda、API Gatewayなどのサーバーレスアプリ開発を加速します。自然言語でインフラ構成やアーキテクチャガイダンスを得られ、`get_iac_guidance`や`get_serverless_templates`などのツールで設計から開発、デプロイまでを効率化。AWSベストプラクティスに準拠し、開発サイクル全体を短縮します。

---

### [【Microsoft Defender for Identity】正常性の問題：「NTLM監査が有効になっていません」の解決方法](https://blog.jbs.co.jp/entry/2025/07/29/131453)
**Source:** JBS Blog
**Published:** 2025-07-29 04:14:53 UTC
**Tags:** Microsoft Defeder for Identity, セキュリティ, Tech

**Digest:**
Microsoft Defender for Identity (MDI) は、オンプレミスActive Directory (AD) を保護するクラウドベースのセキュリティソリューションです。クラウドIDとAD IDのシグナルを統合し、高度な脅威を特定・検出・調査します。本記事では、MDI センサーインストール時に発生する「正常性の問題」のうち、「NTLM監査が有効になっていません」の解決方法について解説しています。

---

### [Red Hat Enterprise Linux 9でrootのSSHログインを無効にできない問題の原因と解決策](https://blog.jbs.co.jp/entry/2025/07/29/114820)
**Source:** JBS Blog
**Published:** 2025-07-29 02:48:20 UTC
**Tags:** RHEL, Red Hat Enterprise Linux, Tech

**Digest:**
RHEL導入でroot SSHログインを無効化する際、構築作業で一時的に有効化後、設定変更が効かない問題が発生。原因は、`sshd_config`のIncludeディレクティブによる設定上書き。OSインストール時の設定が影響している場合も。解決策は、Includeの確認と、必要に応じた設定変更。

---

### [AI Builderの感情分析を利用してFormsのアンケート結果を評価する](https://blog.jbs.co.jp/entry/2025/07/29/094840)
**Source:** JBS Blog
**Published:** 2025-07-29 00:48:40 UTC
**Tags:** AI Builder, Power Automate, Power Platform

**Digest:**
AI BuilderはPower PlatformのノーコードAIツールで、感情分析など様々なAIモデルを簡単に構築できます。Formsアンケート結果を感情分析で評価する活用例を紹介。Power Automateフローを作成し、アンケートデータを分析することで、テキストの感情（ポジティブ、ネガティブ、ニュートラル）を把握できます。

---