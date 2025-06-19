# AI Tech Trends Digest (2025-06-19)


## Top Tech Articles from Qiita


### [マイクロソフトCEOが言った”AIでSaaSアプリの消滅する”に関して](https://qiita.com/QueryPie/items/6c20485284f22a35ef73)
**Published:** 2025-06-18 14:01:37 UTC
**Likes:** 4
**Tags:** AI, MCP, 生成AI, LLM

**Digest:**
マイクロソフトCEOのナデラ氏は、SaaSの進化を「死んだ」と表現。AIエージェント台頭により、既存アプリのUI不要化、バックエンド崩壊を予測。ビジネスロジックはAI層へ移行し、課金モデルも変化。AIネイティブSaaSが台頭し、企業はAI活用で価値創造を。SaaS企業はAI化への対応が急務です。

---

### [生成 AI は次にどの単語を選ぶ？ Gemini の logprobs 機能で確率を見てみよう！](https://qiita.com/te_yama/items/2fddfbf0a4078e7911c0)
**Published:** 2025-06-18 13:52:15 UTC
**Likes:** 3
**Tags:** Python, Gemini, GoogleCloud, VertexAI, 生成AI

**Digest:**
Gemini APIの`logprobs`機能で、LLMがテキスト生成時にトークンごとの選択肢と確率を可視化。`response_logprobs`と`logprobs`設定で、AIの選択理由を理解。例えば「日本で一番高い山は？」への回答候補を分析し、生成AIの挙動解釈やデバッグ、チューニングに役立つ。多様な選択肢から確率的に単語が選ばれる過程を理解し、AIをより効果的に活用。

---

### [OpenHands CLIでローカルLLM（Ollama・LiteLLM）を使ったAIエージェント開発入門](https://qiita.com/nokonoko_1203/items/7cbdb5d5e82b3c0a4f41)
**Published:** 2025-06-18 13:40:52 UTC
**Likes:** 3
**Tags:** Python, LLM, litellm, ollama, OpenHands

**Digest:**
OpenHands CLIをローカルLLMで動かす方法を紹介。OllamaとLiteLLM Proxyを使用し、Qwen3 32Bモデルをローカル環境で実行する。設定は`~/.openhands/settings.json`で行い、LiteLLM経由なら柔軟な設定が可能。メリットはプライバシー保護、APIコスト不要、オフライン動作。デメリットは初期設定とハードウェアスペック。

---

### [TRTCとChatGPT（OpenAI API）を連携して音声AIチャットを構築する手順](https://qiita.com/lbddk4/items/99322d5bff097ae1cec5)
**Published:** 2025-06-19 05:34:36 UTC
**Likes:** 0
**Tags:** 音声処理, RTC, OpenAI, AI会話アプリ, ChatGPT

**Digest:**
Tencent Cloud TRTC SDKとOpenAI ChatGPT APIを連携し、Flutterでリアルタイム音声AIチャットを実現。TRTCで音声を収音し、ASRでテキスト化、ChatGPT（gpt-3.5-turbo）で対話、TTSで音声合成しTRTC経由で応答。OpenAI APIキー取得、Flutterでの音声送受信、PythonサーバーでのChatGPT連携、TTS、TRTCによる音声伝送と再生の流れを説明。

---

### [ネクストステップMCPセキュリティ:【第2回】コンテキスト汚染攻撃の全貌 - AIの記憶を狙う新たな脅威](https://qiita.com/QueryPie/items/dfac5ef56314d8a0ff38)
**Published:** 2025-06-19 04:30:24 UTC
**Likes:** 0
**Tags:** Security, AI, MCP, LLM

**Digest:**
MCPの「コンテキスト汚染攻撃」は、AIの長期記憶であるコンテキストに悪意ある情報を注入し、判断を歪める高度な攻撃。プロンプトインジェクションを超え、長期的な影響と検知の難しさが特徴です。対策として、コンテキストの整合性検証、アクセス制御強化、定期的な再評価、設計段階からのセキュリティ組み込みが重要となります。

---

## Latest News from RSS Feeds


### [Meeting summarization and action item extraction with Amazon Nova](https://aws.amazon.com/blogs/machine-learning/meeting-summarization-and-action-item-extraction-with-amazon-nova/)
**Source:** AWS ML Blog
**Published:** 2025-06-18 16:13:36 UTC
**Tags:** Amazon Bedrock, Amazon Nova, Generative AI, Intermediate (200), Technical How-to, AI/ML

**Digest:**
Amazon Bedrockで利用可能なAmazon Novaモデルを活用し、会議の議事録から要約とアクションアイテムを生成する手法を解説。Prompt engineeringを用い、モデルの選定基準や性能を評価。Nova Premierは高い精度を示し、Nova Microは高速処理を実現。企業向けに、速度とコストを最適化するAmazon Novaの利点を紹介しています。

---

### [Building a custom text-to-SQL agent using Amazon Bedrock and Converse API](https://aws.amazon.com/blogs/machine-learning/building-a-custom-text-to-sql-agent-using-amazon-bedrock-and-converse-api/)
**Source:** AWS ML Blog
**Published:** 2025-06-18 16:10:16 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Agents, Amazon Bedrock Knowledge Bases, Amazon DynamoDB, Amazon Machine Learning, AWS Lambda, Technical How-to

**Digest:**
自然言語からSQLを生成するText-to-SQLの課題に対し、Amazon BedrockとConverse APIを活用したカスタムエージェント「ConverseSQLAgent」を紹介。複雑なクエリやデータベース構造に対応するため、計画、自己修正、長期学習機能を実装。SQLAlchemyによる自己修正やDynamoDBを活用した長期記憶で精度向上を図り、AnthropicのClaude 3.5 Sonnetを利用。コードはGitHubで公開されており、デプロイとクリーンアップの手順も解説。

---

### [Accelerate threat modeling with generative AI](https://aws.amazon.com/blogs/machine-learning/accelerate-threat-modeling-with-generative-ai/)
**Source:** AWS ML Blog
**Published:** 2025-06-18 16:05:53 UTC
**Tags:** Amazon Bedrock, Artificial Intelligence, Generative AI, Security, Technical How-to

**Digest:**
ジェネレーティブAIは、**脅威モデリング**を革新し、脆弱性の特定、攻撃シナリオ生成、緩和策の提供を自動化。**Threat Designer** は、アーキテクチャ図を分析し、大規模言語モデル(LLM)を活用して脅威を特定。時間や専門知識の壁を越え、**AI**による包括的なセキュリティ分析を実現し、開発の速度を落とさずに、より強固なシステム構築を可能にする。

---

### [Azure Red Hat Enterprise Linux 仮想マシン導入ポイント～その2～](https://blog.jbs.co.jp/entry/2025/06/19/130612)
**Source:** JBS Blog
**Published:** 2025-06-19 04:06:12 UTC
**Tags:** Azure, Linux, RHEL

**Digest:**
Azure上のRHEL VM設定について解説。SELinux、Firewalld、IPv6を無効化し、日本語環境を構築、パッケージをアップデートします。Azure環境でRHEL VMを最適化するための手順を簡潔にまとめました。

---

### [Microsoft Entra Connect Health 管理者への通知について](https://blog.jbs.co.jp/entry/2025/06/19/090248)
**Source:** JBS Blog
**Published:** 2025-06-19 00:02:48 UTC
**Tags:** Azure AD Connect, Azure AD, Microsoft Entra Connect, Microsoft Entra ID

**Digest:**
Microsoft Entra Connect Health（MECH）は、オンプレAD DSとEntra IDの同期を監視する重要ツール。プロキシ環境では設定が必要で、本記事では管理者へのエラー通知設定を解説。MECHの設定方法を説明し、実際の通知例を提示。

---

### [【AWS】AWS BudgetsレポートでAWSの利用状況を把握する](https://blog.jbs.co.jp/entry/2025/06/18/164606)
**Source:** JBS Blog
**Published:** 2025-06-18 07:46:06 UTC
**Tags:** AWS, AWS Budgets

**Digest:**
AWS Budgetsは、AWS利用料金を管理するコスト管理ツールです。予算を設定し、利用状況とコストを追跡、予算超過のアラート設定やレポート作成が可能です。AWS Budgetsレポートを活用することで、AWS利用料金の現状把握に役立ちます。

---