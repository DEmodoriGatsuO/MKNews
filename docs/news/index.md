# AI Tech Trends Digest (2025-09-17)


## Top Tech Articles from Qiita


### [Brave APIキーをAWSのマーケットプレースでサブスクしてOpenAI互換APIとして呼ぶ](https://qiita.com/moritalous/items/36b1d32c5e208e394d3d)
**Published:** 2025-09-16 09:30:20 UTC
**Likes:** 3
**Tags:** AWS, OpenAI, マーケットプレイス, brave

**Digest:**
プライバシー重視のブラウザBraveが提供するBrave SearchのAPIについて。無料を含む13プランがあり、AWSマーケットプレイス経由でも購入可能。Data for AIのProプランは、OpenAI互換のSummarizer Search APIを利用でき、OpenAIライクなコードで検索が可能。Amazon Bedrock AgentCoreについての詳細な情報も得られるなど、活用範囲が広がります。

---

### [AIと仲良くなる方法：実践的な3つのステップ](https://qiita.com/s-age/items/5fe8b0aa457a2396c0fb)
**Published:** 2025-09-16 09:13:55 UTC
**Likes:** 1
**Tags:** AI, LLM

**Digest:**
AI活用はツールに偏りがちでLLMへの理解が不足していると指摘。まずは触り、次にCLI操作など明確なタスクをAIに任せ指示の出し方を習得、ルールやロジックの実装に挑戦しAIの思考を理解することが重要。**観察、分析、言語化**の繰り返しでLLMの特性を掴み、ツールの強み弱みを予測できる人材を目指すべきです。

---

### [RAGChecker with Azure OpenAI](https://qiita.com/suzookita/items/0ab6a8a99211a32dc605)
**Published:** 2025-09-17 05:53:02 UTC
**Likes:** 0
**Tags:** rag, LLM, AzureOpenAI, litellm, ragchecker

**Digest:**
RAGCheckerでAzure OpenAIを利用する方法の備忘録。**LiteLLM**を用いてAzure OpenAIのモデルを呼び出すため、`azure/`プレフィックスとデプロイ名を指定。`AZURE_API_KEY`、`AZURE_API_BASE`、`AZURE_API_VERSION`を環境変数かコード内で設定。RAGCheckerとLiteLLMをインストールし、Python SDKで評価を実行。JSONファイルからの読み込みも可能。

---

### [Python × LLMでPDFからデータ抽出！JSON化の罠とデバッグ方法](https://qiita.com/maskot1977/items/6c5dc0dbcda5032e78f0)
**Published:** 2025-09-17 05:30:01 UTC
**Likes:** 0
**Tags:** Python, PDF, JSON, ChatGPT, LLM

**Digest:**
LangChainとAzure OpenAIを用いたPDF解析で、`"Missing some input keys"`エラーを解決。原因はPromptTemplateの`input_variables`設定ミスで、`["context", "question"]` に修正。`safe_invoke`はシンプルに`qa_chain.invoke({"query": prompt_text})`に。修正後のコードを提示し、df.head()表示後の列名正規化に進む。

---

### [SimAI完全ガイド｜DifyやN8Nを超える次世代AIワークフローツールの全て【2025年最新】](https://qiita.com/k_nabe/items/35b492af2d9e5ca6afb0)
**Published:** 2025-09-17 01:50:15 UTC
**Likes:** 0
**Tags:** API, 技術調査, 業務自動化, プロンプトエンジニアリング, Claude

**Digest:**
AIがワークフローを自動化する新ツール「SimAI」が登場。日本語で指示するだけでAIがワークフローを構築、DifyやN8Nを超える。AIエージェント中心設計、Copilot機能で簡単操作、Apache 2.0ライセンスで商用利用もフリー。クラウド版、セルフホスティング、ローカルLLM連携も可能。無料プランから始められ、働き方を変える可能性を秘めている。

---

## Latest News from RSS Feeds


### [FabCon Vienna: Build data-rich agents on an enterprise-ready foundation](https://www.microsoft.com/en-us/microsoft-fabric/blog/2025/09/16/fabcon-vienna-build-data-rich-agents-on-an-enterprise-ready-foundation)
**Source:** Azure AI Blog
**Published:** 2025-09-16 11:23:54 UTC
**Tags:** AI + machine learning, Analytics, Azure AI, Microsoft Fabric

**Digest:**
Microsoft Fabric Community Conferenceがオーストリア・ウィーンで開催。Fabricは急速に成長し、Fortune 500社の約8割が利用。OneLakeの機能強化、GraphデータベースとMapsのプレビュー、開発者ツールの拡充、セキュリティ向上を発表。Synapseからの移行も容易に。Snowflakeとの連携も強化。2026年のFabConはアトランタで開催予定。

---

### [Streamline access to ISO-rating content changes with Verisk rating insights and Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/streamline-access-to-iso-rating-content-changes-with-verisk-rating-insights-and-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-09-16 16:43:42 UTC
**Tags:** Amazon Bedrock, Amazon ElastiCache, Amazon OpenSearch Service, Artificial Intelligence, Customer Solutions, Generative AI

**Digest:**
Veriskは、ISO Ratingの変更概要を提供する「Rating Insights」を、生成AIとAWSで刷新。AnthropicのClaudeやRAGを活用し、ユーザーは自然言語で質問し、関連情報を即座に取得可能に。手作業でのデータ検索や分析を削減し、顧客サポートの効率も向上。今後は、より高度な検索とプラットフォームの拡張を目指す。

---

### [Unified multimodal access layer for Quora’s Poe using Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/unified-multimodal-access-layer-for-quoras-poe-using-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-09-16 16:40:11 UTC
**Tags:** Amazon Bedrock, Customer Solutions, Foundation models, Generative AI

**Digest:**
AWS Generative AI Innovation CenterとQuoraは、Amazon BedrockのモデルをQuoraのPoeシステムに迅速統合するため、統一APIフレームワークを開発。ServerSentEventsとREST APIのブリッジング、テンプレートベース設定でデプロイを15分に短縮。30以上のモデルを統合し、コード変更を最大95%削減。

---

### [GitHub Copilot Custom Chat Modesで独自エージェントを作成](https://blog.jbs.co.jp/entry/2025/09/17/145028)
**Source:** JBS Blog
**Published:** 2025-09-17 05:50:28 UTC
**Tags:** VS Code, Copilot, GitHub, GitHub Copilot

**Digest:**
GitHub CopilotのVS Code向け新機能「Custom Chat Modes」が登場。2025年5月リリース版から、独自のAIチャットモード作成が可能に。Ask、Edit、Agentに加え、目的に特化したAI体験を実現。例えば、コード解説専門AIモードを構築し、開発効率を格段に向上させる活用方法も紹介します。

---

### [Power Apps：「SortByColumns」関数を使ってSharePointリストの内容を並び替えて表示させる](https://blog.jbs.co.jp/entry/2025/09/17/130733)
**Source:** JBS Blog
**Published:** 2025-09-17 04:07:33 UTC
**Tags:** PowerPlatfirm, Power Apps, 初心者向け

**Digest:**
Power AppsでSharePointリストを昇順・降順に並び替える方法を紹介。**SortByColumns関数**を使用し、リスト内の特定の列を基準に並べ替えられます。これにより、SharePointリストの表示を**昇順**または**降順**に簡単に設定し、データの見やすさを向上させることが可能です。

---

### [iDRACを使ったRAID構築方法と注意点](https://blog.jbs.co.jp/entry/2025/09/17/110740)
**Source:** JBS Blog
**Published:** 2025-09-17 02:07:40 UTC
**Tags:** iDRAC, Windows Server, Tech

**Digest:**
iDRACでRAIDを構築する方法を解説。RAID設定はiDRAC Web UIから行い、仮想ディスク作成でRAIDレベル、ディスク選択、名前などを指定します。構築には時間が必要で、再起動も伴います。構築後の確認も忘れずに。手順と注意点をまとめた情報です。

---

### [【Microsoft×生成AI連載】【Power Platform】Microsoft Power AutomateでMicrosoft Copilotを使ってみた 3](https://blog.jbs.co.jp/entry/2025/09/17/090047)
**Source:** JBS Blog
**Published:** 2025-09-17 00:00:47 UTC
**Tags:** Copilot, Microsoft Copilot, Microsoft 365 Copilot, 生成AI, Microsoft×生成AI連載, Power Automate

**Digest:**
Power AutomateのCopilot機能を使ったフロー作成を試します。前回紹介した多様なCopilot機能を活用し、フローを構築します。Power AutomateとCopilotの連携により、より効率的な自動化フローの作成が期待できます。

---