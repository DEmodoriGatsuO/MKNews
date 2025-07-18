# AI Tech Trends Digest (2025-07-18)


## Top Tech Articles from Qiita


### [Kiroみたいな「仕様書駆動開発」をClaude Code・Opus 4でやるまでの手順を整理した！！！](https://qiita.com/nokonoko_1203/items/8bafb6033409aadccd9f)
**Published:** 2025-07-17 12:45:30 UTC
**Likes:** 10
**Tags:** Opus, LLM, Claude, ClaudeCode, Kiro

**Digest:**
AWSの**Kiro**は、設計文書作成から実装に入る「**仕様書駆動開発**」をLLMで実現するツール。2025/07時点ではClaude Sonnet 3.7 or 4.0のみ利用可能で、Claude Codeに作業させる選択肢も。著者は、Claude Codeでの開発を前提に、カスタムコマンドや設定ファイルを用いた**事前設計**の手順を紹介。要件定義、設計、タスク分割を行うカスタムコマンド例も提示。

---

### [SnowflakeにADBから自然言語で問い合わせしてみた (SELECT AIを使ったADB Sidecar)](https://qiita.com/ssfujita/items/580a0b351f63f0278289)
**Published:** 2025-07-17 23:36:29 UTC
**Likes:** 9
**Tags:** adb, oci, Snowflake, LLM

**Digest:**
OCIのAutonomous Database (ADB)で、異種DBであるSnowflakeに対して、DBLinkとSELECT AI（NL2SQL）を組み合わせた「Sidecar」を検証。ADBからSnowflakeへのDBLink接続、データのロード、自然言語での問い合わせを試行。自然言語でSnowflakeのデータにアクセスでき、異なるDB間のデータ連携を容易にします。

---

### [『つくりながら学ぶ！LLM 自作入門』を読むぞ](https://qiita.com/RyuGotoo/items/06bf782c021a54ed06d5)
**Published:** 2025-07-18 01:18:31 UTC
**Likes:** 2
**Tags:** Python, PyTorch, 生成AI, LLM, つくりながら学ぶ！LLM自作入門

**Digest:**
「つくりながら学ぶ！LLM 自作入門」がAmazonで実質半額で購入可能、2025/7/18 10:06 JST時点でも半額の模様です。本書は大規模言語モデルの理解から、GPTモデルの実装、ファインチューニングまで網羅。AttentionメカニズムやPyTorchも扱っており、本格的なLLM自作を学べます。継続を目標に、毎朝30分の学習から始める予定とのことです。

---

### [【最新情報】ChatGPT Agent 徹底解説：機能・用途を完全網羅](https://qiita.com/nolanlover0527/items/f611f3c29c1fc66383a2)
**Published:** 2025-07-18 04:32:44 UTC
**Likes:** 1
**Tags:** AI, OpenAI, ChatGPT, AIエージェント, ChatGPTagent

**Digest:**
OpenAIは2025年7月、ウェブ操作、リサーチ、コーディングなどを実行できる「ChatGPT Agent」を正式リリース。OperatorとDeep Researchを統合し、自律的な操作や複数ステップ実行が可能。Pro/Plus/Teamプランで利用でき、Web・API連携、ターミナル操作、ファイル生成も。安全対策としてユーザー承認やWatch Modeを搭載。今後はGPT-5との統合、マルチモーダル対応も検討されています。

---

### [🧪 なぜMBTIには強く、ローカル店舗情報には弱いのか？―生成AIにおける「構造知識」と「事実知識」のギャップを掘り下げる](https://qiita.com/Pinko-zeevaa/items/67e4119bd7eb23b6dc4a)
**Published:** 2025-07-18 00:33:00 UTC
**Likes:** 1
**Tags:** 自然言語処理, ChatGPT, LLM, #生成AI, #ハルシネーション

**Digest:**
生成AIはMBTIなど構造的知識は得意だが、実在しないカフェ情報を生成する「ハルシネーション」を起こす原因を解説。これは、AIが持つ知識の構造と記憶の在り方の違いによるもの。構造知識は再構成しやすい一方、事実知識は可変性や情報源の不確かさから、正確な記憶が難しいため。RAGやファインチューニングで精度を補い、一次情報での検証が重要。

---

## Latest News from RSS Feeds


### [Microsoft Azure AI Foundry Models and Microsoft Security Copilot achieve ISO/IEC 42001:2023 certification](https://azure.microsoft.com/en-us/blog/microsoft-azure-ai-foundry-models-and-microsoft-security-copilot-achieve-iso-iec-420012023-certification/)
**Source:** Azure AI Blog
**Published:** 2025-07-17 15:00:00 UTC
**Tags:** AI + machine learning, AI, Copilot

**Digest:**
マイクロソフトは、Azure AI Foundry ModelsとSecurity CopilotがAI管理システム（AIMS）の国際規格ISO/IEC 42001:2023認証を取得。責任あるAI開発へのコミットメントを示し、リスク管理や透明性を重視。顧客は、認証されたAIサービスを活用し、コンプライアンスを加速、信頼を構築できます。マイクロソフトは、プラットフォームと専門知識を提供し、AIの倫理的な利用を支援します。

---

### [Evaluating generative AI models with Amazon Nova LLM-as-a-Judge on Amazon SageMaker AI](https://aws.amazon.com/blogs/machine-learning/evaluating-generative-ai-models-with-amazon-nova-llm-as-a-judge-on-amazon-sagemaker-ai/)
**Source:** AWS ML Blog
**Published:** 2025-07-17 22:12:26 UTC
**Tags:** Amazon Nova, Amazon SageMaker, Amazon SageMaker AI, Announcements, Artificial Intelligence, Foundation models

**Digest:**
Amazon SageMaker AI で提供開始された「Nova LLM-as-a-Judge」は、大規模言語モデル (LLM) の出力を評価する新機能です。バイアスを抑え、人間の好みを反映するよう訓練されており、モデルの優劣を客観的に評価できます。ペア比較を行い、勝率や信頼区間などのメトリクスを提供。評価ワークフローはSQuADデータセットとQwen2.5、Claude 3.7などのモデルを使用し、Amazon S3に結果を保存、可視化します。

---

### [Building cost-effective RAG applications with Amazon Bedrock Knowledge Bases and Amazon S3 Vectors](https://aws.amazon.com/blogs/machine-learning/building-cost-effective-rag-applications-with-amazon-bedrock-knowledge-bases-and-amazon-s3-vectors/)
**Source:** AWS ML Blog
**Published:** 2025-07-17 22:09:04 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Knowledge Bases, Amazon Machine Learning, Artificial Intelligence

**Digest:**
Amazon Bedrock Knowledge Basesで、低コストのクラウドオブジェクトストレージ、Amazon S3 Vectors（プレビュー）が利用可能に。これにより、RAGアプリケーションのベクトルアップロード、ストレージ、クエリコストを最大90%削減。大量のデータに対応し、サブ秒のクエリ性能を実現。S3 VectorsとBedrockの連携で、大規模知識ベースの構築がより経済的に。

---

### [Implementing on-demand deployment with customized Amazon Nova models on Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/implementing-on-demand-deployment-with-customized-amazon-nova-models-on-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-07-17 19:36:59 UTC
**Tags:** Amazon Bedrock, Artificial Intelligence, Foundation models

**Digest:**
Amazon Bedrockで、カスタムモデルのオンデマンドデプロイが開始。モデルの**ファインチューニング**や**蒸留**でカスタマイズしたモデルを、必要な時に呼び出して利用可能に。**トークンベース**の従量課金で、**Novaモデル**に対応。AWSコンソールまたはAPI/SDKでデプロイ、運用でき、**コールドスタート**や**リージョン**などの考慮事項も。

---

### [Building enterprise-scale RAG applications with Amazon S3 Vectors and DeepSeek R1 on Amazon SageMaker AI](https://aws.amazon.com/blogs/machine-learning/building-enterprise-scale-rag-applications-with-amazon-s3-vectors-and-deepseek-r1-on-amazon-sagemaker-ai/)
**Source:** AWS ML Blog
**Published:** 2025-07-17 12:30:48 UTC
**Tags:** Amazon SageMaker AI, Generative AI, Launch, Amazon SageMaker

**Digest:**
LLM活用で業務変革を目指す企業向けに、Amazon S3 Vectorsが発表されました。RAGシステムの課題であるコスト増、運用複雑化をS3の低コスト・高耐久性で解決。SageMaker AIと連携し、ベクターデータの効率的な管理と分析を実現します。S3 Vectorsは、埋め込みモデル、文章生成モデル、MLflowによる実験追跡といったRAGシステム構築を容易にします。

---

### [ユニファイドコミュニケーション採用時のボイスゲートウェイによる回線収容](https://blog.jbs.co.jp/entry/2025/07/18/141957)
**Source:** JBS Blog
**Published:** 2025-07-18 05:19:57 UTC
**Tags:** 電話回線, 既存回線, レガシー回線, セッションボーダーコントローラー, 選び方, 収容可能回線, ユニファイドコミュニケーション

**Digest:**
ユニファイドコミュニケーション（UC）は、ビジネスで不可欠な多機能通信統合技術です。複数の通信手段を連携し、スムーズなコミュニケーションと生産性向上を実現します。従業員のコラボレーションを促進し、業務効率を大幅に向上。近年、電話交換機入れ替え時にUCが検討され、電話番号の付加や既存番号のクラウド収容も可能です。

---

### [Intuneライセンスがない環境でデバイスを条件にした条件付きアクセス許可ポリシーの作成方法と有用性](https://blog.jbs.co.jp/entry/2025/07/18/124155)
**Source:** JBS Blog
**Published:** 2025-07-18 03:41:55 UTC
**Tags:** Azure AD, Microsoft Entra ID

**Digest:**
企業でBYODを抑止する際、Microsoft Intuneのデバイスベース条件付きアクセスが有効です。Intuneライセンスが必要ですが、Microsoft Entra ID P1ライセンス（旧Azure AD Premium P1）があれば、Entra上のデバイス登録機能を利用可能です。Intuneライセンスがない環境でも、BYOD対策の一部としてEntraの活用を検討できます。

---

### [【Microsoft×生成AI連載】【Power Platform】Microsoft Power AutomateでMicrosoft Copilotを使ってみた](https://blog.jbs.co.jp/entry/2025/07/18/090613)
**Source:** JBS Blog
**Published:** 2025-07-18 00:06:13 UTC
**Tags:** Copilot, Microsoft Copilot, Microsoft 365 Copilot, 生成AI, Microsoft×生成AI連載, Power Automate

**Digest:**
1年前にPower AutomateでCopilotのフロー作成を検証。今回は、1年間の改善点を探るため、同じプロンプトで再検証。さらに、様々なプロンプトを試して、Copilotの進化を検証します。

---

### [PIM対応もばっちり！Microsoft Graph PowerShellで構築するEntra IDロール棚卸術](https://blog.jbs.co.jp/entry/2025/07/17/150751)
**Source:** JBS Blog
**Published:** 2025-07-17 06:07:51 UTC
**Tags:** Microsoft Entra ID, Microsoft Graph, PowerShell

**Digest:**
Entra ID（旧Azure AD）の管理者ロール管理を効率化する方法を紹介。PowerShellスクリプトを用いて、ロール情報を可視化し、CSV形式で出力することで、管理者の負担を軽減します。混在しがちな管理者ロールの一元管理に役立つ、必見の情報です。

---