# AI Tech Trends Digest (2025-05-29)


## Top Tech Articles from Qiita


### [BedrockナレッジベースでClaude Sonnet 4が使いたい！](https://qiita.com/har1101/items/1732a69e44dfeac0bb91)
**Published:** 2025-05-28 16:34:51 UTC
**Likes:** 9
**Tags:** AWS, bedrock, Claude, KnowledgeBaseForAmazonBedrock

**Digest:**
Claude Sonnet 4をAmazon Bedrockのナレッジベース基盤モデルに設定すると、公式未対応ながら、カスタムプロンプト必須のエラーが発生。  オーケストレーションと生成プロンプトの両方で、`$query$`、`$search_results$`、`$output_format_instructions$`、`$conversation_history$`の4変数の明示的な指定が必要。  デフォルトプロンプトに不足分を追加し、無事動作を確認した。

---

### [手を動かして学ぶ！MCPステップバイステップ実践ガイド for Beginners - Vol.9 集大成！MCP連携コマンドラインツール（一覧表示＆検索）を作る](https://qiita.com/QueryPie/items/1936e8b4facf604bf96d)
**Published:** 2025-05-29 01:37:06 UTC
**Likes:** 3
**Tags:** Python, 初心者, AI, MCP, LLM

**Digest:**
「手を動かして学ぶ！MCPステップバイステップ実践ガイド」の集大成として、APIキー認証を活用したコマンドラインツールを開発。Pythonのargparseモジュールでコマンドと引数を扱い、デバイス一覧表示やID指定での情報取得を実現。エラー処理も組み込み、lsやgitのようなツールを自作する楽しさを体験。サーバーの起動確認後、実際にツールを実行し、機能を確認しました。

---

### [PythonとOpenAI APIで実践！はじめてのMCP開発入門【第11回】プロンプトエンジニアリング実践(1) - AIの能力を引き出す「ロールプロンプティング」と「システムメッセージ」の戦略的活用法](https://qiita.com/QueryPie/items/a0f5f35fb0db7a43bac8)
**Published:** 2025-05-28 14:57:00 UTC
**Likes:** 3
**Tags:** Python, AWS, MCP, LLM, ModelContextProtocol

**Digest:**
AI開発の第11回では、AIに個性と専門性を与える「システムメッセージ」と「ロールプロンプティング」を紹介。システムメッセージでAIの役割や応答を定義し、ロールプロンプティングで特定の役割を演じさせ、Pythonで実装。これらのテクニックにより、AIの挙動を精密に制御し、AIアプリケーションの品質向上を図ります。具体的なコード例や、トークン効率、実験の重要性についても解説。

---

### [【AIが超進化？！】話題のMCPを世界一分かりやすく解説](https://qiita.com/zukizukizukizuki/items/032f4b9be717acb533f7)
**Published:** 2025-05-28 12:31:23 UTC
**Likes:** 2
**Tags:** AI, MCP, Gemini, ChatGPT, LLM

**Digest:**
MCPはAIの能力を拡張する「AIの執事」で、PC操作や情報収集を可能にします。AIと連携し、PC内ファイル操作、ウェブ情報収集、アプリ連携などを実現。ローカル実行でプライバシー保護、APIコスト削減も。Open InterpreterやAnythingLLMなど多様なツールがあり、GUIベースなら始めやすい。AI活用の幅を広げるMCPの世界へ踏み出しましょう。

---

### [Claude Opus 4でゲーム開発を革命的に効率化した話 - AIとの対話だけで3時間でゲームをリリース!?](https://qiita.com/f_uto/items/53fddf2ea7e3ba6b6988)
**Published:** 2025-05-28 06:52:13 UTC
**Likes:** 2
**Tags:** JavaScript, game, 生成AI, Claude, Claude4

**Digest:**
AI「Claude Opus 4」を使い、**コーディング不要でWebゲームを3時間で開発**した事例を紹介。弾幕シューティングなど4種のゲームを**プロンプトとコピペのみ**で作成。AIがコード生成、バグ修正、ゲームバランス調整まで行い、開発時間を大幅短縮。**GitHub Actionsによる自動デプロイ**も実現。プロンプトエンジニアリングが鍵で、開発プロセスに変革をもたらす。

---

## Latest News from RSS Feeds


### [飲食店のクーポン表示など Google ビジネス プロフィールの便利な新機能のご紹介](https://blog.google/intl/ja-jp/products/explore-get-answers/business-profile-updates/)
**Source:** Google Japan Blog
**Published:** 2025-05-28 10:00:00 UTC
**Tags:** Search, Small Business

**Digest:**
Google検索やGoogleマップで表示されるお店の正確な情報は、予約や来店に不可欠です。Googleは、ビジネスオーナーがお店の情報を簡単に更新できる機能を開発中。これは、顧客がお店を探す際に、**Google検索** や **Googleマップ** で正しい **お店の詳細** を確認し、来店意欲を高めるために重要です。

---

### [Part 3: Building an AI-powered assistant for investment research with multi-agent collaboration in Amazon Bedrock and Amazon Bedrock Data Automation](https://aws.amazon.com/blogs/machine-learning/part-3-building-an-ai-powered-assistant-for-investment-research-with-multi-agent-collaboration-in-amazon-bedrock-and-amazon-bedrock-data-automation/)
**Source:** AWS ML Blog
**Published:** 2025-05-28 18:39:06 UTC
**Tags:** Advanced (300), Amazon Bedrock, Amazon Bedrock Agents, Financial Services

**Digest:**
Amazon Bedrockのマルチエージェントコラボレーション機能を用いた投資調査アシスタントを構築。複数のAIサブエージェントが連携し、金融ニュース分析、株価評価、ポートフォリオ最適化を支援。監督エージェントが複雑な質問を分解し、専門タスクを委任。Amazon Bedrock Data Automation（BDA）でマルチモーダルデータから洞察を生成。LLMにNova understanding modelsを利用。

---

### [A generative AI prototype with Amazon Bedrock transforms life sciences and the genome analysis process](https://aws.amazon.com/blogs/machine-learning/a-generative-ai-prototype-with-amazon-bedrock-transforms-life-sciences-and-the-genome-analysis-process/)
**Source:** AWS ML Blog
**Published:** 2025-05-28 18:36:14 UTC
**Tags:** Advanced (300), Amazon API Gateway, Amazon Athena, Amazon Bedrock, Amazon DynamoDB, Amazon Simple Storage Service (S3), AWS Amplify, AWS AppSync, AWS Lambda, Customer Enablement, Customer Solutions, How-To, Technical How-to, AIML, Generative AI, HCLS, life sciences, machine-learning, Natural Language Processing

**Digest:**
バイオ医薬品開発は10年以上、20億ドル超のコスト、90%以上の失敗率を伴う高リスクなプロセスです。AWSは製薬会社のM2Mプロセスを効率化するため、大規模言語モデル（LLM）とAmazon Bedrockを活用したテキストto SQLパイプラインを構築。ゲノムデータに対し、自然言語で質問しSQLを生成するAIアシスタントを開発、研究を加速し、創薬の可能性を広げます。

---

### [Gemma 3 27B model now available on Amazon Bedrock Marketplace and Amazon SageMaker JumpStart](https://aws.amazon.com/blogs/machine-learning/gemma-3-27b-model-now-available-on-amazon-bedrock-marketplace-and-amazon-sagemaker-jumpstart/)
**Source:** AWS ML Blog
**Published:** 2025-05-28 18:30:05 UTC
**Tags:** Amazon Bedrock, Amazon SageMaker, Announcements, Generative AI, Technical How-to

**Digest:**
Amazon Bedrock MarketplaceとSageMaker JumpStartで、Googleの高性能LLM「Gemma 3 27B Instruct」モデルが利用可能に。270億パラメータのモデルで、テキストと画像入力に対応し、長文処理や多言語サポートが特徴です。AWS上で生成AIソリューション構築を加速できます。BedrockまたはSageMaker UI、Python SDKでデプロイし、チャットボット等に応用できます。

---

### [Building a multimodal RAG based application using Amazon Bedrock Data Automation and Amazon Bedrock Knowledge Bases](https://aws.amazon.com/blogs/machine-learning/building-a-multimodal-rag-based-application-using-amazon-bedrock-data-automation-and-amazon-bedrock-knowledge-bases/)
**Source:** AWS ML Blog
**Published:** 2025-05-28 16:53:27 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Knowledge Bases, Generative AI, Intermediate (200)

**Digest:**
Amazon Bedrock Data AutomationとKnowledge Basesを活用した、マルチモーダルコンテンツ処理アプリケーションを紹介。様々なファイル形式を自動処理し、自然言語での質問応答を実現。医療、金融、法律、メディアなど多業種でのユースケースを紹介し、RAGベースのQ&A機能で情報検索を効率化。AWS CDKによるデプロイ手順、前提条件、GitHubリポジトリも公開。

---

### [Tailoring foundation models for your business needs: A comprehensive guide to RAG, fine-tuning, and hybrid approaches](https://aws.amazon.com/blogs/machine-learning/tailoring-foundation-models-for-your-business-needs-a-comprehensive-guide-to-rag-fine-tuning-and-hybrid-approaches/)
**Source:** AWS ML Blog
**Published:** 2025-05-28 16:50:20 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Knowledge Bases, Amazon SageMaker AI, Amazon SageMaker JumpStart, Artificial Intelligence, Foundation models, Intermediate (200), Technical How-to

**Digest:**
AWSのFoundation Model（FM）活用戦略として、**RAG、ファインチューニング、ハイブリッド**の3手法を紹介。Amazon BedrockでRAGを容易化し、SageMakerでファインチューニングとハイブリッドを実装。評価指標にはBERTScore、LLM評価スコア、推論時間、コスト分析を用い、RAGが低コストながらハイブリッドと同等の性能を示した。GitHubリポジトリでコード公開。

---

### [Highlights from the Dialogues stage at I/O 2025](https://blog.google/technology/developers/google-io-2025-dialogues-ai-quantum-storytelling/)
**Source:** Google DeepMind
**Published:** 2025-05-28 16:14:00 UTC
**Tags:** Gemini App, Google DeepMind, Developers, AI

**Digest:**
Google I/O 2025のDialoguesステージでは、Googleのリーダーとビジョナリーが集結しました。今後の展望や技術革新について活発な議論が交わされ、AIや次世代技術に関する発表に大きな注目が集まりました。

---

### [AvePoint Cloud Governanceでメタデータを利用した台帳管理を行う方法](https://blog.jbs.co.jp/entry/2025/05/29/145836)
**Source:** JBS Blog
**Published:** 2025-05-29 05:58:36 UTC
**Tags:** Microsoft 365, AvePoint, ACG

**Digest:**
AvePoint Cloud Governance（ACG）管理者を対象とした記事のダイジェストです。ACGでチームやサイトの棚卸を行う際、例外的な管理が発生しがちですが、データ一貫性維持のためにはメタデータ活用が重要です。本記事では、ACGのメタデータ機能を使い、台帳管理を一元化する方法を紹介します。

---

### [SharePoint リストに添付されたファイルをPythonで取得する方法](https://blog.jbs.co.jp/entry/2025/05/29/140554)
**Source:** JBS Blog
**Published:** 2025-05-29 05:05:54 UTC
**Tags:** SharePoint, API, Python, Azure Key Vault

**Digest:**
SharePoint REST APIを利用し、PythonでSharePointリストに格納された添付ファイルの情報を取得する方法を紹介しています。具体的には、REST APIを用いて、添付ファイル名やURLなどの詳細を効率的に取得する方法を解説しているようです。

---