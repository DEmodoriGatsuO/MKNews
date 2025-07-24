# AI Tech Trends Digest (2025-07-24)


## Top Tech Articles from Qiita


### [AIエンジニアへの道 - 24日目：AIエンジニア必須！DockerとKubernetesで開発環境を構築](https://qiita.com/555hamano/items/a5025a9e07db2d7524f0)
**Published:** 2025-07-23 20:00:41 UTC
**Likes:** 3
**Tags:** Python, 初心者, データサイエンス, LLM, AIエンジニア

**Digest:**
AIエンジニア必須のDockerとKubernetesを解説。Dockerは**コンテナ**技術で環境の再現性を高め、Kubernetesは**コンテナオーケストレーション**でスケーリングや高可用性を実現。AIモデルのデプロイ、運用基盤を構築し、開発効率を向上させる。

---

### [「データと会話する」AIエージェントをさらに賢く！DataRobot予測AIを組み込む方法](https://qiita.com/DataRobot_PR/items/69617f4dfbf1c4345861)
**Published:** 2025-07-23 20:47:03 UTC
**Likes:** 2
**Tags:** Python, DataRobot, LLM, 予測AI, AIエージェント

**Digest:**
DataRobot Japan副社長が、TTMDAIエージェントにDataRobot予測AIを組み込む方法を紹介。`tools.py`に関数を定義し、DataRobotデプロイIDを指定、必要なライブラリを`requirements.txt`に追加することで、AIエージェントがDataRobotの予測AIを活用可能に。これにより、より高度な分析やビジネスロジックの活用が実現します。関数名、docstring、型ヒントが重要です。

---

### [AIエンジニアへの道 - 22日目：クラウドでAIを動かす！AWS、Azure、GCPのAIサービス比較](https://qiita.com/555hamano/items/be9fc0f8c6df158dedfb)
**Published:** 2025-07-23 13:58:43 UTC
**Likes:** 2
**Tags:** Python, 初心者, データサイエンス, LLM, AIエンジニア

**Digest:**
AI学習22日目は、AWS、Azure、GCPといった主要な**クラウドAIサービス**を比較。各社の特徴として、AWSは包括性、AzureはMicrosoft製品との連携、GCPはGoogleのAI技術が強み。AIモデル学習やデプロイに不可欠で、プロジェクト要件、予算、スキルセットで選択。**SageMaker**や**Vertex AI**などのサービス、**LLM**も比較検討。

---

### [AIエンジニアへの道 - 18日目：LLMを動かす！Hugging Face Transformersライブラリ入門](https://qiita.com/555hamano/items/5e69a8689cd1c2b80601)
**Published:** 2025-07-23 07:38:35 UTC
**Likes:** 2
**Tags:** Python, 初心者, データサイエンス, LLM, AIエンジニア

**Digest:**
18日目は、LLMを動かすための「Hugging Face Transformers」ライブラリ入門。BERTやGPTなどのLLMを簡単に利用できるツールで、自然言語処理のデファクトスタンダードです。`pipeline`による感情分析、`AutoTokenizer`と`AutoModel`を使った推論を解説し、ファインチューニングの概念も紹介。明日からは感情分析の実装に進みます。

---

### [AIエンジニアへの道 - 25日目：AIエージェントと自動化！MCP (Model Context Protocol) マスターへの道](https://qiita.com/555hamano/items/8deb1b2ffd460611014f)
**Published:** 2025-07-23 20:10:18 UTC
**Likes:** 1
**Tags:** Python, 初心者, データサイエンス, LLM, AIエンジニア

**Digest:**
25日目はAIエージェントと自動化がテーマ。大規模言語モデル（LLM）を自律的にタスク実行するツールとして活用するため、Anthropic社のModel Context Protocol（MCP）を解説。AIエージェントは、プランニング、記憶、ツール利用、推論で構成され、MCPはプロンプト設計、思考の可視化、記憶の効率化、出力形式制御に貢献。プロンプトエンジニアリング、ツール利用、記憶管理、評価改善が重要スキル。

---

## Latest News from RSS Feeds


### [Customize Amazon Nova in Amazon SageMaker AI using Direct Preference Optimization](https://aws.amazon.com/blogs/machine-learning/customize-amazon-nova-in-amazon-sagemaker-ai-using-direct-preference-optimization/)
**Source:** AWS ML Blog
**Published:** 2025-07-23 19:08:16 UTC
**Tags:** Amazon Nova, Amazon SageMaker AI, Artificial Intelligence, Foundation models, Intermediate (200)

**Digest:**
Amazon Novaのモデルカスタマイズ機能を発表。Amazon SageMaker AIのレシピで、Nova Microなどを事前学習、ファインチューニング、アライメントできます。DPOを用いたカスタマイズでは、人間の好みに合わせた出力が可能で、SageMakerのトレーニングジョブを使用。Function callingに最適化し、F1スコア81%向上も実現。必要な前提条件として、SageMaker AIのクォータやIAMロールの設定が挙げられています。

---

### [Multi-tenant RAG implementation with Amazon Bedrock and Amazon OpenSearch Service for SaaS using JWT](https://aws.amazon.com/blogs/machine-learning/multi-tenant-rag-implementation-with-amazon-bedrock-and-amazon-opensearch-service-for-saas-using-jwt/)
**Source:** AWS ML Blog
**Published:** 2025-07-23 16:44:31 UTC
**Tags:** Advanced (300), Amazon Bedrock, Amazon Bedrock Knowledge Bases, Amazon OpenSearch Service, Technical How-to

**Digest:**
大規模言語モデル(LLM)の活用を促進するため、RAGが注目されています。本記事では、マルチテナント環境における、JWTとFGACを活用したOpenSearch Serviceでのセキュアなデータ分離方法を紹介。Amazon Cognito、DynamoDB、Lambdaを連携し、テナントIDをJWTに付与、FGACでロールマッピングを実現。OpenSearch Serviceの3つの分離パターンに対応し、安全なRAG環境を構築します。

---

### [Enhance generative AI solutions using Amazon Q index with Model Context Protocol – Part 1](https://aws.amazon.com/blogs/machine-learning/enhance-generative-ai-solutions-using-amazon-q-index-with-model-context-protocol-part-1/)
**Source:** AWS ML Blog
**Published:** 2025-07-23 16:40:40 UTC
**Tags:** Amazon Q, Amazon Q Business, Artificial Intelligence, Best Practices

**Digest:**
AI活用で意思決定を強化するため、MCPとAmazon Q indexを連携。MCPはLLMを外部ツールに接続、Amazon Q indexはセマンティック検索でデータ検索を高速化します。ISVは顧客データに安全にアクセス可能。2つの連携パターンがあり、迅速な展開には直接検索、MCPで統合なら統一インターフェースが利点。AWSは相互運用性を強化中です。

---

### [Listen to a conversation about the newest AI capabilities in Search.](https://blog.google/products/search/release-notes-podcast-search/)
**Source:** Google DeepMind
**Published:** 2025-07-23 19:00:00 UTC
**Tags:** Search, Google DeepMind, AI

**Digest:**
Google AI: Release Notesの最新エピソードでは、Logan Kilpatrickが、検索で何十億もの人々が本当に何でも質問できるようにするための取り組みについて議論しています。AI技術を活用し、検索体験を革新することを目指しており、より高度な質問応答能力を実現するために研究開発が進められています。

---

### [Surface Laptop with 5Gの登場: ビジネスのためのシームレスな接続性](https://blogs.windows.com/japan/2025/07/24/introducing-surface-laptop-5g-seamless-connectivity-built-for-business/)
**Source:** Windows Blog for Japan
**Published:** 2025-07-24 04:06:13 UTC
**Tags:** Surface, Surface Laptop 5G

**Digest:**
マイクロソフトは法人向け Surface Copilot+ PC ポートフォリオを拡充、5G対応のSurface Laptopを発表。Intel Core Ultra搭載、8月26日出荷開始。ダイナミックアンテナシステムによる安定した5G接続、NanoSIM/eSIM対応でグローバル利用も。セキュリティと管理機能を強化、Windows 10サポート終了に向けた移行を促進。日本国内では2025年9月2日出荷開始予定。

---

### [Microsoft Sentinel をご利用のお客様向け Microsoft Defender ポータルへの移行計画](https://blogs.windows.com/japan/2025/07/23/planning-your-move-to-microsoft-defender-portal-for-all-microsoft-sentinel-custo/)
**Source:** Windows Blog for Japan
**Published:** 2025-07-23 09:09:58 UTC
**Tags:** Security, Defender, Sentinel

**Digest:**
Microsoftは、Microsoft SentinelをMicrosoft Defenderポータルに統合し、2026年7月1日までにAzureポータルでのSentinelを廃止します。これにより、SIEMとXDRの統合によるセキュリティオペレーションの効率化を目指します。単一UIでのインシデント管理やAI活用、SOCの最適化により、アナリストの効率性向上、迅速な対応を実現します。早期の移行計画と準備を推奨し、Microsoftの支援を活用できます。

---

### [Terraformのcheckブロックを試してみた](https://blog.jbs.co.jp/entry/2025/07/24/114858)
**Source:** JBS Blog
**Published:** 2025-07-24 02:48:58 UTC
**Tags:** Azure, Terraform

**Digest:**
Terraform v1.5から導入された`check`ブロック機能を試します。これはTerraformモジュールやリソースのテストを可能にするもので、以前の`terraform test`に加えて選択肢が増えました。今回は、Azure App Serviceへの接続をテストするterraform定義ファイルを作成し、接続可否で挙動を確認します。

---

### [NIST SP800-171を徹底解説!! ー SP800-53との比較 ー](https://blog.jbs.co.jp/entry/2025/07/24/095904)
**Source:** JBS Blog
**Published:** 2025-07-24 00:59:04 UTC
**Tags:** セキュリティ, サイバー攻撃

**Digest:**
近年注目されるSP800は、NIST（米国国立標準技術研究所）が発行するセキュリティガイドライン群。製品選定で加点要素となることも。SP800-171やSP800-53が有名で、米連邦政府やパートナー企業のセキュリティ体制構築に活用されています。NISTはCSFやAI RMFも発行し、包括的なセキュリティ対策を支援しています。

---

### [AIエージェント実現にむけての一手　― Computer Useによる自動操作の検証](https://blog.jbs.co.jp/entry/2025/07/24/090336)
**Source:** JBS Blog
**Published:** 2025-07-24 00:03:36 UTC
**Tags:** Azure AI Foundry, LLM, AIエージェント, Computer Use, Responses API, Playwright, MCP

**Digest:**
Azure OpenAIの**Computer Use Preview**モデルと**Playwright**を連携させ、AIエージェントを構築する方法を紹介。ブラウザ操作を自動化し、Azure OpenAIで**プロンプト**を生成、Playwrightで**Webサイト**を操作することで、様々なタスクを効率化します。

---