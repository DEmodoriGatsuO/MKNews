# AI Tech Trends Digest (2025-06-17)


## Top Tech Articles from Qiita


### [Streamlit × LangGraphでHuman-in-the-loopを実現する](https://qiita.com/so-engineer/items/60c10b44cea3aebae0a1)
**Published:** 2025-06-16 23:12:06 UTC
**Likes:** 4
**Tags:** Streamlit, 生成AI, LLM, LangGraph

**Digest:**
StreamlitとLangGraphでHuman-in-the-loopを実現するWebアプリを開発。AIエージェントが判断に迷う場合にユーザーに判断を委ねる機能を実現。`interrupt`と`Command`を使い、Streamlitの`st.session_state`で状態管理。AIエージェントはWeb検索と人間のレビューを使い、追加情報が必要な場合にアラートを表示。リポジトリを公開。

---

### [AWSワードウルフやってみた！！](https://qiita.com/ts_pepeti/items/67d4f7a1e2cf9625b774)
**Published:** 2025-06-17 03:55:51 UTC
**Likes:** 2
**Tags:** AWS, bedrock, Claude, AmazonQ, cline

**Digest:**
AWS単語でワードウルフゲームを作成！ClineとBedrock with Claude 4を使い、AWSの用語で遊ぶアプリを開発。認証機能、ルーム一覧、ゲーム画面などを実装。開発期間1週間、費用は約$20。プロンプトは自然言語ベースで、AWS SAMやCognitoも活用。先祖返りや苦手な部分もあったが、Amazon Qとの併用でコスト削減も。EC2 vs Lambdaなどのお題例も紹介。

---

### [Claudeの契約の仕方次第で切り替えるのに時間がかかる話](https://qiita.com/iwata-n/items/1e41dcb7c35e598a449e)
**Published:** 2025-06-16 15:28:44 UTC
**Likes:** 2
**Tags:** Claude

**Digest:**
Claude ProをAndroid定期購入すると割高で、Web版と価格差がある。MAXプランへの変更もWeb版が有利だが、Android版の契約が残っているとWeb版からのアップグレードができないという落とし穴が存在。Android版の期間が終了するまでWeb版への変更は待つ必要がある。

---

### [音声入力でAIエージェントを動かすデスクトップアプリを作ったんだなも](https://qiita.com/hmkc1220/items/3dea024f489b9d9a24af)
**Published:** 2025-06-16 16:45:53 UTC
**Likes:** 1
**Tags:** whisper, OpenAI, Gemini, Claude, AIエージェント

**Digest:**
音声入力ツールは進化し、Super WhisperやAqua Voiceは音声からテキスト、LLMによる加工を自動化。Open Super Whisper V2は、OpenAI Agents SDKとMCPを採用し、音声でツールを操る体験を提供。会議録音、メール作成、Web操作など、多様なAIエージェントが利用可能。OpenAI APIやLLMを活用し、音声入力から行動への変革を提案。

---

### [watsonx Orchestrate上のAgentで複数Geminiモデルでロードバランシングしてみる](https://qiita.com/haseshin/items/e31f3da8ea1c6413fc5c)
**Published:** 2025-06-16 14:52:42 UTC
**Likes:** 1
**Tags:** ADK, Gemini, watsonxOrchestrate, AIAgent

**Digest:**
watsonx Orchestrateでカスタムモデルがサポートされ、OpenAIやGoogleなどの外部LLMを利用可能に。ADK1.5.0からはModel Policy機能でロードバランシングやフォールバックも実現。Geminiモデルを例に、ポリシー設定でモデルの動的切り替えを検証。エラー時の代替モデル指定も可能となり、LLMの可用性を向上させることが可能です。

---

## Latest News from RSS Feeds


### [How Apollo Tyres is unlocking machine insights using agentic AI-powered Manufacturing Reasoner](https://aws.amazon.com/blogs/machine-learning/how-apollo-tyres-is-unlocking-machine-insights-using-agentic-ai-powered-manufacturing-reasoner/)
**Source:** AWS ML Blog
**Published:** 2025-06-16 17:22:05 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Agents, Amazon Machine Learning, Customer Solutions, Generative AI, Manufacturing

**Digest:**
インドのタイヤメーカー、Apollo Tyresは、Amazon Bedrockと生成AIを活用し、製造工程のデータ分析を革新。熟練の技術者向けに、自然言語で機械データからインサイトを得る「Manufacturing Reasoner」を開発しました。これにより、RCA（根本原因分析）の時間を最大7時間から10分に短縮、年間1500万円のコスト削減を見込んでいます。

---

### [Extend your Amazon Q Business with PagerDuty Advance data accessor](https://aws.amazon.com/blogs/machine-learning/extend-your-amazon-q-business-with-pagerduty-advance-data-accessor/)
**Source:** AWS ML Blog
**Published:** 2025-06-16 17:15:54 UTC
**Tags:** Amazon Q, Amazon Q Business, Customer Solutions, Partner solutions, AI/ML, AIML, Generative AI

**Digest:**
PagerDuty AdvanceとAmazon Q Businessの連携を紹介。PagerDuty Advanceはインシデント管理を強化し、Amazon Qのデータアクセスで複数システム横断検索を実現。これにより、迅速な問題解決、MTTR短縮、コスト最適化、セキュリティ向上を実現。企業は、ランブックや関連情報を効率的に取得し、運用効率を向上。

---

### [Innovate business logic by implementing return of control in Amazon Bedrock Agents](https://aws.amazon.com/blogs/machine-learning/innovate-business-logic-by-implementing-return-of-control-in-amazon-bedrock-agents/)
**Source:** AWS ML Blog
**Published:** 2025-06-16 17:11:19 UTC
**Tags:** Advanced (300), Amazon SageMaker, Artificial Intelligence, Learning Levels

**Digest:**
Amazon Bedrock Agents は、分散システムにおけるエージェント作成を簡素化し、"return of control"機能で複雑な相互作用を容易にします。本記事では、パーソナライズされた投資ポートフォリオの例として、AWS Lambda、AWS Step Functions、外部API、Streamlitアプリとの連携を解説。API呼び出しや長時間のタスクに有効で、セキュリティ、モニタリングなどの考慮事項も提示。

---

### [【OpManager使ってみた】第1回 OpManagerのインストール](https://blog.jbs.co.jp/entry/2025/06/17/130646)
**Source:** JBS Blog
**Published:** 2025-06-17 04:06:46 UTC
**Tags:** Tech, OpManager, 監視, Windows

**Digest:**
ゾーホージャパンの監視ソフトウェア「OpManager」を紹介。第1回はインストール方法を解説します。OpManagerは、幅広い機器対応、豊富な監視項目、使いやすさが魅力。評価版をWindows Server 2022へ導入し、設定や監視機能について全5回で説明予定です。

---

### [【PowerShell】Active Directoryモジュールがない環境でActive Directoryのユーザー情報を取得する](https://blog.jbs.co.jp/entry/2025/06/17/091429)
**Source:** JBS Blog
**Published:** 2025-06-17 00:14:29 UTC
**Tags:** PoweShell, Active Directory

**Digest:**
顧客環境でのモジュールインストールが困難なため、PowerShellモジュールを使わずにActive Directory（AD）のユーザー情報を取得する方法を検討しました。

---

### [【Windows 365】クラウドPCへのRDP接続許可設定について -IntuneからのPower Shellスクリプト配布による対応編-](https://blog.jbs.co.jp/entry/2025/06/16/162226)
**Source:** JBS Blog
**Published:** 2025-06-16 07:22:26 UTC
**Tags:** Windows 365, Microsoft Intune

**Digest:**
Windows 365は、Azure上のWindows Desktopに接続するMicrosoftのVDIソリューションです。クラウドPCと呼ばれる仮想マシンが各ユーザーに割り当てられ、Windowsデバイスとして利用可能。セキュリティのため、すべてのクラウドPCでRDP接続に利用されるポート3389が既定でブロックされ、Intuneによる設定が必要となる仕様です。

---