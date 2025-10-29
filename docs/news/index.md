# AI Tech Trends Digest (2025-10-29)


## Top Tech Articles from Qiita


### [NPU搭載PCでLLMを動かすまでの話 〜第一弾 Docker Model Runnerとの出会い〜](https://qiita.com/gnt0608/items/22964b5fbc028074ccf3)
**Published:** 2025-10-28 09:25:09 UTC
**Likes:** 1
**Tags:** LLM, NPU, DockerModelRunner

**Digest:**
Intel NPU搭載AI PCでローカルLLMを試すため、Docker Model Runner を利用。SmolLM3 を起動し、挨拶応答まで約5秒。API実行では35秒かかる。GPT-OSSも試したが、応答に21秒かかり、モデルサイズの差が影響か。NPUやGPUは未利用のため、今後の課題。

---

### [DatabricksにGeminiがやってきました！](https://qiita.com/taka_yayoi/items/6fb444f637a4eec3fe34)
**Published:** 2025-10-29 05:34:10 UTC
**Likes:** 0
**Tags:** Google, Databricks, Gemini

**Digest:**
DatabricksがGemini 2.5 ProとFlashモデルのサポートを開始。Foundation Model APIsのpay-per-tokenで利用可能となり、Function callingやStructured outputにも対応。AWS東京リージョンで動作確認済み。推論モデルのクエリも試せる。

---

### [AI Shell 入門 — PowerShell とスタンドアローンで始める AI シェル運用ガイド](https://qiita.com/ochtum/items/a511a0a2de74bdf46663)
**Published:** 2025-10-29 03:52:03 UTC
**Likes:** 0
**Tags:** Azure, PowerShell, AI, OpenAI, AIShell

**Digest:**
AI Shellは、PowerShell上でAIエージェントと対話できるツールです。Windows環境でのインストールはPSGalleryから可能で、`/code`コマンドでコード生成、`Start-AIShell`でPowerShell連携。スタンドアローン版も存在し、トラブルシューティングとベストプラクティスも解説。簡単なプロンプト設計テンプレートと導入チェックリストも提供、開発効率化に貢献します。

---

### [Claude Code v2.0.27 - v2.0.28 リリースノート](https://qiita.com/NaokiIshimura/items/3e86e53c8ce4a5294e7a)
**Published:** 2025-10-28 23:23:09 UTC
**Likes:** 0
**Tags:** Claude

**Digest:**
Claude Codeがv2.0.28とv2.0.27にアップデート。v2.0.28ではPlanモードのPlanサブエージェント導入、サブエージェント再開、動的モデル選択、`--max-budget-usd`フラグ追加、スラッシュコマンド検出改善、Gitベースプラグインでのフラグメント構文対応など。v2.0.27ではUI刷新、セッション再開画面改善、VSCode拡張機能の改善、バグ修正が行われました。インストールは`npm`で。

---

### [Geminiでサツマイモと遊ぶ魔法少女を描いてみた。](https://qiita.com/nori-channel/items/d4ed8af53c1e7d129bd2)
**Published:** 2025-10-28 21:50:28 UTC
**Likes:** 0
**Tags:** Gemini

**Digest:**
Geminiを用いて、サツマイモと遊ぶ魔法少女のイラストを生成しました。シンプルなプロンプト「サツマイモと遊ぶ魔法少女を描いてください」を実行した結果、画像が生成されました。可愛らしい出来栄えで、何かの役に立てば嬉しいという思いが込められています。

---

## Latest News from RSS Feeds


### [Hosting NVIDIA speech NIM models on Amazon SageMaker AI: Parakeet ASR](https://aws.amazon.com/blogs/machine-learning/hosting-nvidia-speech-nim-models-on-amazon-sagemaker-ai-parakeet-asr/)
**Source:** AWS ML Blog
**Published:** 2025-10-28 18:09:48 UTC
**Tags:** Amazon SageMaker AI, Generative AI, Technical How-to

**Digest:**
NVIDIAとAmazon SageMaker AIを活用した音声処理の拡張性を解説。NVIDIA Parakeet ASRモデルを非同期エンドポイントにデプロイし、大規模な音声データ（顧客コール、会議録音など）を効率的にテキスト化。NVIDIA NIM、LMIコンテナ、PyTorchコンテナでの実装例を紹介し、SageMaker、S3、Bedrock LLM、DynamoDBを組み合わせたパイプラインを構築します。

---

### [Amazon Nova Multimodal Embeddings: State-of-the-art embedding model for agentic RAG and semantic search](https://aws.amazon.com/blogs/aws/amazon-nova-multimodal-embeddings-now-available-in-amazon-bedrock/)
**Source:** AWS News Blog
**Published:** 2025-10-28 15:12:38 UTC
**Tags:** *Post Types, Amazon Bedrock, Amazon Machine Learning, Announcements, Artificial Intelligence, Generative AI, Launch, News

**Digest:**
Amazon Bedrockで利用可能な、Nova Multimodal Embeddingsを発表。テキスト、画像、動画、音声に対応し、単一モデルで高精度な検索を実現します。最大8Kトークンのコンテキスト長、200言語以上のテキストをサポート。非構造化データから価値を引き出し、クロスモーダル検索、RAG、類似性比較などに活用できます。

---

### [【Microsoft×生成AI連載】Skillsエージェントにより組織のスキル検索が便利に](https://blog.jbs.co.jp/entry/2025/10/29/100233)
**Source:** JBS Blog
**Published:** 2025-10-29 01:02:33 UTC
**Tags:** Copilot, Microsoft Copilot, Microsoft 365 Copilot, 生成AI, Microsoft×生成AI連載

**Digest:**
Microsoftの生成AI連載シーズン4では、SkillsエージェントとPeople Skillsが焦点です。組織内の**スキル管理**を効率化し、**エキスパート探索**を支援するAI機能が詳しく解説されています。これらの新機能は、Microsoftが提供する**AI**技術を活用し、組織の**人材活用**を促進するものです。

---