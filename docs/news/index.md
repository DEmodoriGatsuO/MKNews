# AI Tech Trends Digest (2025-07-02)


## Top Tech Articles from Qiita


### [BedrockのPDFサポートについて検証しましたが、、](https://qiita.com/moritalous/items/54a3eb9a410a41d04b6c)
**Published:** 2025-07-01 11:39:08 UTC
**Likes:** 12
**Tags:** AWS, PDF, bedrock, Claude

**Digest:**
Amazon BedrockがClaudeモデルのアップデートを発表。**引用API**と**PDFサポート**が追加され、ClaudeがPDFからテキストだけでなく画像も認識可能に。Converse APIのPDFサポートとの違いは、後者はテキスト抽出のみなのに対し、新機能は画像化して処理するため、より高度な分析が可能。**InvokeModel API**または引用を有効にしたConverse APIで利用でき、検証結果も良好。

---

### [LLMで気分の浮き沈みを可視化してみたら有用なデータが得られた！](https://qiita.com/gretchi/items/1cc791e8e5145c0250b9)
**Published:** 2025-07-01 22:13:16 UTC
**Likes:** 2
**Tags:** フーリエ変換, 感情分析, OpenAI, ChatGPT, LLM

**Digest:**
約400日分のX投稿をLLMで分析し、情動、活動性など8項目の精神状態をスコアリング。過去の試行錯誤を経て、GPT-4o-miniのAPIを利用し、日ごとのツイートをCSV形式で入力、簡潔な指示で精度を向上させた。結果はCSV形式で出力され、評価の根拠も付記。

---

### [LangGraph体験(その2) : Geminiとしりとりで対戦するプログラムをLangGraphを使って書いてみた](https://qiita.com/steelpipe75/items/0b5948779c3c3485ba1d)
**Published:** 2025-07-01 15:09:26 UTC
**Likes:** 2
**Tags:** Gemini, LangGraph

**Digest:**
LangGraphを用いてLLMと対戦するしりとりゲームを開発。ユーザー入力とAI（Gemini）の応答をLangGraphで状態遷移グラフとして実装。LLMを活用し、単語の「読み」を考慮したルールチェックを実現。AIの応答、ルール違反判定、ターン管理をノードで表現。最終的に、LangGraphの柔軟性を活かした、より自然な対戦を目指す。

---

### [[Mac]ClaudeCodeのStop Hooksを使ってユーザー応答待ちのとき「だけ」デスクトップ通知する](https://qiita.com/yheihei/items/4415759278d3686b6f2b)
**Published:** 2025-07-02 02:43:26 UTC
**Likes:** 1
**Tags:** Anthropic, Claude, ClaudeCode

**Digest:**
Claude CodeのHooksで、ユーザー応答待ちの通知をMacで実装。`Stop`フックでツール完了時にも通知される問題を、JSON処理ツール`jq`を用いて解決。アシスタントのメッセージタイプを判別し、テキスト応答時のみ通知するように。5秒待機して再確認する二段階検出で誤検出も防止。`settings.json`とシェルスクリプトで設定、Homebrewで`jq`インストールが必要。

---

### [AI時代にソフトウェアエンジニアが生き残る方法](https://qiita.com/ronitsachdev/items/a15eaaba1f02befeb54e)
**Published:** 2025-07-02 05:59:00 UTC
**Likes:** 0
**Tags:** 初心者, AI, cursor, ChatGPT, Claude

**Digest:**
AI時代、AIエンジニアの需要は増加。AnthropicのClaude CodeとCursorを駆使し、設計レビュー、リファクタ、バグ調査を効率化。バックエンド、AWS、CI/CD等の基盤スキル習得が重要。ClaudeとCursorで学びながらアプリを開発、GitHubやQiitaで公開し経験を積むことが、AIを活かせる強いエンジニアへの道です。

---

## Latest News from RSS Feeds


### [Building secure, scalable AI in the cloud with Microsoft Azure](https://azure.microsoft.com/en-us/blog/building-secure-scalable-ai-in-the-cloud-with-microsoft-azure/)
**Source:** Azure AI Blog
**Published:** 2025-07-01 15:00:00 UTC
**Tags:** AI + machine learning, Analytics, Compute, Containers, Hybrid + multicloud, Management and governance, Security, Generative AI

**Digest:**
生成AIの導入は企業変革を促すが、Azureのようなクラウド基盤が不可欠。オンプレミス環境は制約が多く、72%がクラウド移行でAI導入の障壁が減少。Azureはセキュリティとスケーラビリティを提供し、データプライバシーや人材不足等の課題を解決。包括的なフレームワークでAIワークロードを保護し、イノベーションを加速、企業価値向上に貢献します。

---

### [Google Pixel 9a、楽天モバイルで取扱開始](https://blog.google/intl/ja-jp/feed/pixel-9a-rakutenmobile/)
**Source:** Google Japan Blog
**Published:** 2025-07-01 18:00:00 UTC
**Tags:** Pixel

**Digest:**
本日より、楽天モバイルでGoogle Pixel 9aの取り扱いが開始されました。洗練されたフラットデザインに、Aシリーズ史上最も明るいディスプレイを搭載。エントリーモデルながら、48MPメインカメラで美しい写真が撮れ、AI機能も充実しています。

---

### [新しい Chromebook Plus が登場： AI 機能でさらに便利に](https://blog.google/intl/ja-jp/products/android-chrome-play/chromebook-plus-lenovo-plusgen10/)
**Source:** Google Japan Blog
**Published:** 2025-07-01 12:06:00 UTC
**Tags:** Chrome

**Digest:**
レノボから高性能Chromebook「Chromebook Plus Gen 10」が登場。AI機能搭載で作業効率を向上させます。処理性能が高く、ビジネスやクリエイティブな作業を快適にサポート。

---

### [Use Amazon SageMaker Unified Studio to build complex AI workflows using Amazon Bedrock Flows](https://aws.amazon.com/blogs/machine-learning/use-amazon-sagemaker-unified-studio-to-build-complex-ai-workflows-using-amazon-bedrock-flows/)
**Source:** AWS ML Blog
**Published:** 2025-07-01 20:42:28 UTC
**Tags:** Amazon Bedrock, Amazon SageMaker Unified Studio, Intermediate (200), Technical How-to

**Digest:**
Amazon SageMaker Unified Studioを活用し、データ管理、AI/MLツール、ワークフローを統合するAIソリューション開発を紹介。金融機関の苦情参照システム構築例では、Amazon Bedrock Flow、知識ベース、エージェントを連携。SageMakerでプロンプト作成、チャットエージェント設定後、フローを作成しテスト。複雑なAIワークフローを迅速に開発・デプロイする方法を解説。

---

### [Accelerating AI innovation: Scale MCP servers for enterprise workloads with Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/accelerating-ai-innovation-scale-mcp-servers-for-enterprise-workloads-with-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-07-01 18:16:51 UTC
**Tags:** Amazon Bedrock, Amazon DynamoDB, Amazon Elastic Container Service, Artificial Intelligence, AWS Fargate, AWS PrivateLink, Elastic Load Balancing, Financial Services, Generative AI, Technical How-to

**Digest:**
AnthropicのMCP（Model Context Protocol）は、様々なツール連携を可能にするオープンソースプロトコル。AWSのAmazon Bedrockを活用し、MCPサーバーを集中管理することで、企業内でのジェネレーティブAI活用の加速を目指す。金融サービスでのユースケースとして、注文執行を例に、効率的なAIエージェント開発とガバナンス強化を実現する。

---

### [Choosing the right approach for generative AI-powered structured data retrieval](https://aws.amazon.com/blogs/machine-learning/choosing-the-right-approach-for-generative-ai-powered-structured-data-retrieval/)
**Source:** AWS ML Blog
**Published:** 2025-07-01 18:11:19 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Knowledge Bases, Amazon Q Business, Amazon QuickSight, Amazon Redshift, Amazon SageMaker AI, Generative AI, Generative BI, AI/ML, Amazon Machine Learning, Amazon Quicksight, Amazon SageMaker, Natural Language Processing

**Digest:**
Amazon Web Services (AWS) は、LLMを活用した構造化データ検索の5つのパターンを紹介。Amazon Q Business を使った対話型インターフェース、QuickSightへの自然言語クエリ機能追加、BIと対話型AIの統合など、目的に応じた方法を提供。Amazon Bedrock Knowledge Bases を用いたtext-to-SQLやカスタム実装も可能。企業はSQL不要でデータにアクセスでき、意思決定を迅速化できます。

---

### [Revolutionizing drug data analysis using Amazon Bedrock multimodal RAG capabilities](https://aws.amazon.com/blogs/machine-learning/revolutionizing-drug-data-analysis-using-amazon-bedrock-multimodal-rag-capabilities/)
**Source:** AWS ML Blog
**Published:** 2025-07-01 18:05:10 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Knowledge Bases, Intermediate (200)

**Digest:**
Amazon Bedrock を活用した、製薬・ヘルスケア企業向けの高度なドキュメント分析ソリューションを紹介。多種多様なデータを効率的に処理するため、マルチモーダル検索、高度なチャンク化、引用機能を使用。複雑な研究文書からデータ駆動のインサイトを抽出、臨床試験データや分子図などの分析が可能。Amazon Bedrock Knowledge Bases を利用し、精度と効率を向上。

---

### [【Microsoft×生成AI連載】【Agents】Microsoft 365 Copilotのアナリスト エージェントを使ってみた](https://blog.jbs.co.jp/entry/2025/07/02/085130)
**Source:** JBS Blog
**Published:** 2025-07-01 23:51:30 UTC
**Tags:** Copilot, Microsoft Copilot, Microsoft 365 Copilot, Microsoft×生成AI連載, 生成AI

**Digest:**
Microsoft 365 Copilotの「アナリスト エージェント」について、寺澤氏が解説。2025/6/25時点の情報で、機能や料金変更の可能性に言及。Researcher Agentの使用方法、エージェントの場所、実行、利用シーン、メリット、注意点、まとめを紹介。BizChatによる記事要約もおまけで提供。過去の連載記事へのリンクも掲載しています。

---