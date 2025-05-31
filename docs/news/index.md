# AI Tech Trends Digest (2025-05-31)


## Top Tech Articles from Qiita


### [【unsloth + Gemma3】RAG時代終了か？高精度・高速LLMモデルをローカルPCで爆速FTする！](https://qiita.com/ryosuke_ohori/items/7b0f14d8f6e0668fd979)
**Published:** 2025-05-30 16:35:12 UTC
**Likes:** 32
**Tags:** Python, 自然言語処理, AI, Gemma, LLM

**Digest:**
株式会社ulusageの生成AIが、UnslothAIとGemma 3を組み合わせたLLMファインチューニング効率化を解説。UnslothAIは高速化、メモリ効率改善、長文対応に優れ、Gemma 3はオープンソースで多様なモデルサイズとマルチモーダル、多言語対応が特徴です。両者の相乗効果で、限られたリソースでも高品質なカスタムAI開発が可能になります。

---

### [生成AIモデルの新たな評価軸を求めて：水平思考クイズで「人間らしさ」を測ってみる](https://qiita.com/dnp-ashida/items/ed4ce81a849e6d165e2e)
**Published:** 2025-05-30 07:26:00 UTC
**Likes:** 1
**Tags:** 評価指標, 生成AI, Claude, GPT-4o, gemini-2.5-flash

**Digest:**
生成AIモデルの評価軸を探る実験として、水平思考クイズ「ウミガメのスープ」を様々なモデルで検証。Gemini 2.5 Flashが短時間で正解も、既知の可能性あり。GPT-4o miniは惜しい推論力、Claude 3.5 Haikuは曖昧ながら創造的モードで核心に迫る。人間の認知能力を測る新たな指標となりうる一方、AIが知らない問題での検証が今後の課題。

---

### [AutoGen の SocietyOfMindAgent によるネスト型マルチエージェント構成(GraphFlow)](https://qiita.com/nohanaga/items/50e973cb9ed3cc2a7436)
**Published:** 2025-05-30 07:21:43 UTC
**Likes:** 1
**Tags:** Microsoft, OpenAI, AutoGen

**Digest:**
AutoGen v0.5.6のGraphFlowで、マルチエージェント構成の複雑なワークフローを構築。小説家、批判・肯定的評価チーム、要約エージェントを組み合わせ、RoundRobinGroupChatとSocietyOfMindAgentを駆使して、異世界転生小説の執筆と評価を行う。並行ファンアウト/インや、集約結果に基づくLLM生成も実現。自律性とワークフローの融合で、多様な可能性を模索。

---

### [Geminiで人形を使う魔法少女を描いてみた。](https://qiita.com/nori-channel/items/a868f9ae648e4c25ca49)
**Published:** 2025-05-31 05:42:42 UTC
**Likes:** 0
**Tags:** Gemini

**Digest:**
Geminiで魔法少女イラストを生成する試み。プロンプト「聖なる人形を使う魔法少女を描いてください」を実行し、結果として可愛らしいイラストが得られた。Geminiによる画像生成の可能性を示唆し、何かの役に立てばという期待が込められたシンプルなまとめです。

---

### [Snowflake経由でClaudeのTool Useを試す](https://qiita.com/abe_masanori/items/62e9e0f9bb157141310d)
**Published:** 2025-05-31 03:34:07 UTC
**Likes:** 0
**Tags:** Snowflake, Claude, AIエージェント

**Digest:**
Snowflake CortexのAnthropic ClaudeでTool Use機能の動作確認を実施。日本語での質問では外部ツールが実行されず、結果に基づいた回答も得られなかった。`tool_choice`を`auto`にするとツールが選択されない、外部ツールの結果を`messages`に加えても上手くいかない。Snowflake版と本家のTool Useの違いも感じられ、まともに動いていないという結果になった。

---

## Latest News from RSS Feeds


### [Deploy Amazon SageMaker Projects with Terraform Cloud](https://aws.amazon.com/blogs/machine-learning/deploy-amazon-sagemaker-projects-with-terraform-cloud/)
**Source:** AWS ML Blog
**Published:** 2025-05-30 17:27:16 UTC
**Tags:** Amazon SageMaker, Amazon SageMaker Data & AI Governance, Amazon SageMaker Studio, Technical How-to

**Digest:**
Amazon SageMaker ProjectsをTerraform Cloudで利用する方法を紹介。CloudFormationへの依存を排除し、AWS Service Catalog Engine for Terraform Cloudを活用します。必要なAWSアカウント設定やTerraform Cloudの準備、GitHubリポジトリからのテンプレート利用手順を解説。Terraformのみでカスタムプロジェクトテンプレートをデプロイし、SageMaker Studioからプロジェクト作成可能になります。

---

### [How ZURU improved the accuracy of floor plan generation by 109% using Amazon Bedrock and Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/how-zuru-improved-the-accuracy-of-floor-plan-generation-by-109-using-amazon-bedrock-and-amazon-sagemaker/)
**Source:** AWS ML Blog
**Published:** 2025-05-30 17:18:24 UTC
**Tags:** Amazon Bedrock, Amazon SageMaker, Customer Solutions

**Digest:**
ZURU Techは、建築設計プラットフォームDreamcatcherで、LLMを活用したテキストからの間取り図生成を開発。AWSとの協業で、自然言語からの間取り図生成を実現、Prompt EngineeringやLlama 3BでのFine-tuningを試行。評価フレームワークで精度を検証し、Claude 3.5 SonnetによるPrompt Engineering、Llama 3.1 8BのFull Fine-tuningで精度向上を確認。

---

### [Going beyond AI assistants: Examples from Amazon.com reinventing industries with generative AI](https://aws.amazon.com/blogs/machine-learning/going-beyond-ai-assistants-examples-from-amazon-com-reinventing-industries-with-generative-ai/)
**Source:** AWS ML Blog
**Published:** 2025-05-30 17:10:35 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Agents, Amazon Machine Learning, Artificial Intelligence, Generative AI, Retail

**Digest:**
Amazonは、Amazon RufusやAmazon Seller Assistantのような会話型アシスタントに加え、大規模な業務効率化を実現する非会話型生成AIを活用。**商品リスト作成やAmazon Pharmacyでの処方箋処理、レビューの要約、広告クリエイティブ**など、様々な分野でLLM（大規模言語モデル）を活用し、顧客体験を向上させています。AWSのサービスを活用し、高品質な結果とコスト効率を両立しています。

---

### [Architect a mature generative AI foundation on AWS](https://aws.amazon.com/blogs/machine-learning/architect-a-mature-generative-ai-foundation-on-aws/)
**Source:** AWS ML Blog
**Published:** 2025-05-30 17:02:37 UTC
**Tags:** Best Practices, Generative AI, Intermediate (200), Thought Leadership

**Digest:**
生成AIアプリケーション構築には複雑なワークフロー、安全対策、運用基盤が不可欠。 企業は、開発の効率化、リスク軽減、コスト最適化のため、基盤をサービスとして提供する「ジェネレーティブAIプラットフォーム」を導入。Hub、Gateway、Orchestrationなどの主要コンポーネントで構成され、Centralized、Decentralized、Federatedの運用モデルに対応し、GenAIOpsによる運用も重要です。

---

### [Using Amazon OpenSearch ML connector APIs](https://aws.amazon.com/blogs/machine-learning/using-amazon-opensearch-ml-connector-apis/)
**Source:** AWS ML Blog
**Published:** 2025-05-30 15:57:21 UTC
**Tags:** Amazon Comprehend, Amazon OpenSearch Service, Amazon Titan, Intermediate (200), Technical How-to

**Digest:**
Amazon OpenSearch でのデータ拡張のため、Amazon Comprehend を使った言語検出や、Amazon Bedrock の Titan Text Embeddings v2 を使った埋め込み作成とセマンティック検索を実装する方法を紹介。必要な IAM ロール設定や、OpenSearch ML コネクタの設定、Ingest Pipeline を用いたデータ処理の詳細を解説。SageMaker ノートブックでデモ実行可能。

---

### [Microsoft 365 Copilot の新機能 | 2025 年 5 月](https://blogs.windows.com/japan/2025/05/30/whats-new-in-microsoft-365-copilot-may-2025/)
**Source:** Windows Blog for Japan
**Published:** 2025-05-30 07:58:41 UTC
**Tags:** Copilot, What's new in Copilot

**Digest:**
5月版Microsoft 365 Copilot最新情報：**Copilotアプリ**更新、**Create**エクスペリエンス、**Copilot Notebooks**が一般提供開始。**Microsoft Purview DLP**機能拡張、**Copilot Analytics**統合、**Copilot Chat**安全強化。**OneNote**や**Word**、**Outlook**での新機能も。管理者は**エージェント管理**や**メッセージ消費レポート**で利用状況を把握可能。

---