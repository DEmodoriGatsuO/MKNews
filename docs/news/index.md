# AI Tech Trends Digest (2025-08-06)


## Top Tech Articles from Qiita


### [gpt-ossがAWSに来てる！](https://qiita.com/moritalous/items/09495649c2ad7151a2fc)
**Published:** 2025-08-05 21:40:56 UTC
**Likes:** 14
**Tags:** AWS, OpenAI, SageMaker, bedrock, gpt-oss

**Digest:**
SageMaker JumpStart に OpenAI のモデルが登場！gpt-oss-20bとgpt-oss-120bが利用可能に。Deployボタンからデプロイを試みるも、ml.p5.48xlargeなどの高価なP5インスタンスが必要で、クォーター制限により起動できず。Jupyter環境でのノートブック実行も、SageMakerライブラリーのバージョン問題でエラーとなり、今後の動作報告に期待。

---

### [Claude Code暴走対策 | gomiコマンドでrmの事故を防ぐ](https://qiita.com/Enokisan/items/0d498fa6943f3c463675)
**Published:** 2025-08-05 11:43:20 UTC
**Likes:** 5
**Tags:** Claude, ClaudeCode

**Digest:**
AI開発ツールClaude Code使用時、`rm`コマンド誤実行によるファイル削除リスクを軽減するため、`gomi`コマンドを紹介。`rm`の代替として機能し、ゴミ箱への移動で復元可能。Homebrewで簡単にインストールし、シェル設定で`rm`を`gomi`にエイリアス設定することで既存ワークフローを変えずに安全性を向上。TUIでファイルの閲覧・復元も容易で、安全なターミナル操作を実現します。

---

### [OpenAIのオープンモデルgpt-ossがDatabricksで利用可能に](https://qiita.com/taka_yayoi/items/f2aec363e1840e0cb743)
**Published:** 2025-08-05 21:43:41 UTC
**Likes:** 2
**Tags:** OpenAI, Databricks, gpt-oss

**Digest:**
OpenAIの新たなオープンモデル、GPT OSSモデルがDatabricksのMosaic AIモデルサービングで利用可能になりました。GPT OSS 20Bと120Bの2種類があり、トークン従量課金APIでアクセスできます。東京リージョンでも利用でき、Playgroundでの使用も可能です。Provisioned ThroughputとAI Functionsのサポートは今後段階的に提供される予定です。

---

### [🚀 AI大手2社が同日発表！Claude Opus 4.1とOpenAI GPT-OSSが切り開く新時代](https://qiita.com/Ameyanagi/items/dab8c6fdb0fc8ab83dea)
**Published:** 2025-08-05 21:43:24 UTC
**Likes:** 2
**Tags:** AI, オープンソース, OpenAI, LLM, Claude

**Digest:**
2025年8月5日、Anthropicの**Claude Opus 4.1**とOpenAIの**GPT-OSS**シリーズが発表。Claude Opus 4.1はエージェントタスクやコーディング能力が向上。GPT-OSSはApache 2.0ライセンスのオープンソースモデルで、**120B**と**20B**モデルを展開、透明性と**Mixture-of-Experts**などの技術が特徴。開発者にとって選択肢拡大、AI民主化、競争促進に繋がる。

---

### [LLM活用プロンプトエンジニアリング | ベストプラクティス集](https://qiita.com/nolanlover0527/items/f91e47bc8ad576788bc9)
**Published:** 2025-08-05 06:41:35 UTC
**Likes:** 2
**Tags:** AI, ベストプラクティス, LLM, プロンプトエンジニアリング, AI活用

**Digest:**
2025年8月時点のLLM活用では、プロンプトエンジニアリングが不可欠。明確・具体的に記述し、コンテキストや役割、出力形式を指定するのが基本。思考の連鎖や思考の木、Few-shotといった最新テクニックも有効。モデル特性に合わせ、セキュリティ対策やプロンプト評価、テンプレート管理、バイアス検証も重要。

---

## Latest News from RSS Feeds


### [OpenAI’s open‑source model: gpt‑oss on Azure AI Foundry and Windows AI Foundry](https://azure.microsoft.com/en-us/blog/openais-open%e2%80%91source-model-gpt%e2%80%91oss-on-azure-ai-foundry-and-windows-ai-foundry/)
**Source:** Azure AI Blog
**Published:** 2025-08-05 17:00:00 UTC
**Tags:** AI + machine learning, AI

**Digest:**
マイクロソフトは、AIを基盤とするプラットフォームを構築。Azure AI Foundryでgpt-ossモデル（gpt-oss-120b、gpt-oss-20b）の利用が可能になり、開発者はクラウドとエッジでAIを自在に活用できます。Windows AI FoundryやFoundry Localにより、Windows環境でのローカルAI開発も実現。オープンモデルにより、カスタマイズや柔軟な展開が可能となり、AI開発の可能性を広げます。

---

### [Build an AI assistant using Amazon Q Business with Amazon S3 clickable URLs](https://aws.amazon.com/blogs/machine-learning/build-an-ai-assistant-using-amazon-q-business-with-amazon-s3-clickable-urls/)
**Source:** AWS ML Blog
**Published:** 2025-08-06 01:16:43 UTC
**Tags:** Amazon Q Business, Amazon Simple Storage Service (S3)

**Digest:**
Amazon Q Businessで、S3に保存された企業ドキュメントを参照できるAIアシスタントを構築する方法を紹介。AIが生成した回答の出典URLをクリックすることで、安全にドキュメントにアクセスし、検証できます。S3のドキュメントは、Amazon Q Businessが認証されたユーザーにのみアクセスを許可。この機能を利用するには、IAM Identity CenterまたはIAMフェデレーションでのユーザーアクセス管理が必要です。

---

### [GPT OSS models from OpenAI are now available on SageMaker JumpStart](https://aws.amazon.com/blogs/machine-learning/gpt-oss-models-from-openai-are-now-available-on-sagemaker-jumpstart/)
**Source:** AWS ML Blog
**Published:** 2025-08-05 23:16:48 UTC
**Tags:** Amazon SageMaker, Amazon SageMaker JumpStart, Announcements, Artificial Intelligence

**Digest:**
Amazon SageMaker JumpStartでOpenAIのGPT OSSモデル`gpt-oss-120b`と`gpt-oss-20b`が利用可能に。コーディング、科学分析、数学的推論に優れ、最大128Kのコンテキストウィンドウと調整可能な推論レベルが特徴。EXAによるウェブ検索、SageMaker Python SDK、SageMaker Studio UIからのデプロイが可能で、エンタープライズグレードのセキュリティとスケーラビリティを提供します。

---

### [Discover insights from Microsoft Exchange with the Microsoft Exchange connector for Amazon Q Business](https://aws.amazon.com/blogs/machine-learning/discover-insights-from-microsoft-exchange-with-the-microsoft-exchange-connector-for-amazon-q-business/)
**Source:** AWS ML Blog
**Published:** 2025-08-05 17:01:57 UTC
**Tags:** Amazon Q Business, Generative AI, Intermediate (200), Technical How-to

**Digest:**
Amazon Q Businessは、企業がデータや知識を活用できるよう支援するAIアシスタントです。Microsoft Exchangeコネクタを使用し、メールやカレンダー情報を統合。**Microsoft** **Exchange**データを一元的に検索・アクセス可能にし、自然言語での検索や要約生成を実現。**Amazon Q** Business内で、業務効率化と意思決定を支援します。

---

### [OpenAI open weight models now available on AWS](https://aws.amazon.com/blogs/aws/openai-open-weight-models-now-available-on-aws/)
**Source:** AWS News Blog
**Published:** 2025-08-06 05:56:44 UTC
**Tags:** Amazon Bedrock, Amazon Machine Learning, Amazon SageMaker, Amazon SageMaker JumpStart, Announcements, Artificial Intelligence, Launch, News, Open Source

**Digest:**
AWSがOpenAIのオープンウェイトモデル**gpt-oss-120b**と**gpt-oss-20b**を**Amazon Bedrock**と**SageMaker JumpStart**で提供開始。テキスト生成や推論に特化し、128Kコンテキストウィンドウ、調整可能な推論レベルをサポート。**Bedrock**ではOpenAI互換エンドポイントで利用でき、**SageMaker JumpStart**ではモデルの評価、カスタマイズ、本番環境へのデプロイが可能。コード、分析、数理能力に優れ、AWSでAI開発の自由度を向上させます。

---

### [Teams Phoneで代理人を設定する](https://blog.jbs.co.jp/entry/2025/08/06/110206)
**Source:** JBS Blog
**Published:** 2025-08-06 02:02:06 UTC
**Tags:** Teams Phone

**Digest:**
Teams Phoneの代理人機能は、他のユーザーに通話の受発信を代行させることが可能です。Teams内で代理人を設定すると、指定されたユーザーは自分の代わりに電話に出たり、発信したりできるようになります。設定方法について解説します。

---

### [【Microsoft×生成AI連載】【PowerPoint】Copilot in PowerPointの新機能を紹介](https://blog.jbs.co.jp/entry/2025/08/06/085241)
**Source:** JBS Blog
**Published:** 2025-08-05 23:52:41 UTC
**Tags:** Copilot, Microsoft Copilot, 生成AI, Microsoft×生成AI連載, PowerPoint

**Digest:**
Microsoft PowerPointのCopilotに、新たな機能が追加されました。本記事では、その新機能の中からいくつかを紹介します。PowerPointのCopilotは、プレゼンテーション作成を効率化するAIアシスタントとして、今後も様々な機能追加が期待されます。

---