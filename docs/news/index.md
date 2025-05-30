# AI Tech Trends Digest (2025-05-30)


## Top Tech Articles from Qiita


### [PythonとOpenAI APIで実践！はじめてのMCP開発入門【第12回】プロンプトエンジニアリング実践(2) - 複雑な指示もAIに理解させる「ステップバック」と「思考の連鎖（CoT）」概念の実装ヒント](https://qiita.com/QueryPie/items/3b17ea40c42c9c99b188)
**Published:** 2025-05-29 14:38:16 UTC
**Likes:** 5
**Tags:** Python, AI, MCP, LLM, ModelContextProtocol

**Digest:**
AIに「深く考えさせる」プロンプトエンジニアリングの応用として、ステップバック・プロンプティングと思考の連鎖（CoT）を紹介。前者は抽象化による推論、後者は思考過程の明示化でLLMの推論能力を高める。Python実装例も提示。高性能モデル選択やトークン消費への配慮が重要。APIキー管理など次回予告も。

---

### [MCPで研究！Notion+Jupyter+Google ScholarでAIに勝手に実験してもらおう！](https://qiita.com/kyuko/items/1c46cd596492c4416936)
**Published:** 2025-05-30 03:52:29 UTC
**Likes:** 1
**Tags:** Jupyter, MCP, Notion, 生成AI, Claude

**Digest:**
MCP（Model Context Protocol）を使ってClaude Desktopに研究をさせてみた。論文検索、Jupyterでの実験、Notionでの結果まとめをAIが自律的に実施。実験テーマはニューラルネットワークの活性化関数による学習効率の変化。研究の各段階をこなし、結果をNotionに報告。まだ課題はあるものの、MCPの汎用性やAIの可能性を感じる結果となった。

---

### [資料に命を吹き込むAI！NotebookLMが描く、もっと「伝わる」コミュニケーション](https://qiita.com/dnp_wada/items/7e7c7fc451302d4f005b)
**Published:** 2025-05-30 01:20:19 UTC
**Likes:** 1
**Tags:** LLM, NotebookLM

**Digest:**
NotebookLMは、資料をアップロードすると、内容を理解し、2人の話者によるポッドキャスト形式の音声概要を生成するAIツール。資料の文脈や意図を汲み取り、研修、プロジェクト共有、提案書作成、社内広報など、多岐にわたる業務での活用が期待できる。ポジティブなフィードバックによる学習効果向上や、組織文化の醸成にも貢献する可能性を秘めています。

---

### [ターミナルからGeminiに話しかける(curl)](https://qiita.com/tukiyo3/items/1fad9cfdc9f33dcff454)
**Published:** 2025-05-30 04:29:31 UTC
**Likes:** 0
**Tags:** curl, Gemini

**Digest:**
Google AI StudioでAPIキーを取得し、Geminiモデルを利用する`gemini.sh`スクリプトを紹介。APIキーを環境変数に設定し、curlコマンドでGemini APIにリクエストを送信。引数で質問を指定し、改行コードを処理して結果を表示。`sh gemini.sh 今日の天気`のように使用でき、数秒で応答を得られます。

---

### [PowerShellでOllamaの全モデルを一括アップデートする方法（Windows編）](https://qiita.com/kotai2003/items/90a0f6d0d1567ca660fc)
**Published:** 2025-05-30 04:02:34 UTC
**Likes:** 0
**Tags:** PowerShell, LLM, ollama, LocalLLM

**Digest:**
WindowsのOllamaでダウンロード済みのモデルを一括更新するには、PowerShellで`ollama list`と`ollama pull`を組み合わせたコマンドを実行します。これにより、公開モデルを一度に最新バージョンへアップデートできます。ただし、Modelfileで作成したカスタムモデルは手動での更新が必要、Ollama起動確認も忘れずに。

---

## Latest News from RSS Feeds


### [Revolutionizing earth observation with geospatial foundation models on AWS](https://aws.amazon.com/blogs/machine-learning/revolutionizing-earth-observation-with-geospatial-foundation-models-on-aws/)
**Source:** AWS ML Blog
**Published:** 2025-05-29 21:16:44 UTC
**Tags:** Advanced (300), Amazon OpenSearch Service, Amazon SageMaker, Amazon SageMaker AI, Foundation models, Geospatial ML with Amazon SageMaker, Technical How-to

**Digest:**
地理空間データ向けTransformerモデル（**GeoFM**）は、大陸規模の地球表面マッピングを実現する新技術。Amazon SageMakerで、Clay Foundationのモデルを用いて、森林破壊の検出など、様々な用途に活用可能。衛星画像の前処理、エンベディング生成、類似検索、変化検出、カスタムMLモデルのファインチューニングといった手順で、地理空間データの分析に役立ちます。Amazon OpenSearch ServerlessやLanceDBなどのベクトルデータベースも利用できます。

---

### [Create an agentic RAG application for advanced knowledge discovery with LlamaIndex, and Mistral in Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/create-an-agentic-rag-application-for-advanced-knowledge-discovery-with-llamaindex-and-mistral-in-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-05-29 20:10:51 UTC
**Tags:** Advanced (300), Amazon Bedrock, Amazon Bedrock Knowledge Bases, Technical How-to

**Digest:**
Agentic RAGアプリケーションは、外部知識取得と自律エージェント機能を統合したAIの高度なアプローチです。LlamaIndexフレームワークを用い、Mistral Large 2 FM on Amazon Bedrockを活用。GitHub、Arxiv、TechCrunch、DuckDuckGo等のAPIとRAGフレームワークを連携し、Amazon OpenSearch ServerlessやBedrock Knowledge Basesと連携したドキュメント統合も可能です。エージェントフローはAgentRunnerとAgentWorkerで構成され、複雑なタスクの実行、API連携、コンテキストに応じた応答を実現します。

---

### [Text-to-image basics with Amazon Nova Canvas](https://aws.amazon.com/blogs/machine-learning/text-to-image-basics-with-amazon-nova-canvas/)
**Source:** AWS ML Blog
**Published:** 2025-05-29 19:29:49 UTC
**Tags:** Amazon Nova, Best Practices, Foundational (100), Generative AI, Python, Technical How-to

**Digest:**
Amazon BedrockのAmazon Nova Canvasは、テキストから高品質な画像を生成するAIモデルです。本記事は、初心者向けにNova Canvasの使い方を解説し、Amazon Bedrockでのセットアップ、画像生成プロセス、プロンプトの基本、CFGスケール、シード値などを説明。Pythonスクリプトによるコード例も紹介し、AWS料金についても触れています。

---

### [Real-world applications of Amazon Nova Canvas for interior design and product photography](https://aws.amazon.com/blogs/machine-learning/real-world-applications-of-amazon-nova-canvas-for-interior-design-and-product-photography/)
**Source:** AWS ML Blog
**Published:** 2025-05-29 19:26:14 UTC
**Tags:** Amazon Bedrock, Amazon Nova, Amazon SageMaker AI, Customer Solutions, Generative AI, Intermediate (200), Technical How-to

**Digest:**
Amazon Nova Canvasを活用し、ビジネス課題を解決する方法を解説。インテリアデザインではセグメンテーションによる画像加工で、製品写真ではアウトペインティングで背景を変え、制作コストを削減。Pythonコード例も紹介し、AWSアカウントとBedrockアクセスが前提。Nova Canvasは、時間とコストを削減し、多様なビジュアルコンテンツ作成を可能にします。

---

### [PowerShellによるTeamsアプリ設定の一括変更手順](https://blog.jbs.co.jp/entry/2025/05/30/131003)
**Source:** JBS Blog
**Published:** 2025-05-30 04:10:03 UTC
**Tags:** Microsoft 365, Microsoft Team, PowerShell

**Digest:**
Teamsアプリ管理を効率化！PowerShellスクリプトでアプリ中心の管理をスムーズに行う方法を解説。Teamsアプリごとの可用性設定が面倒な方に、PowerShellを活用した一括設定手順を紹介し、手間を省きます。

---

### [Azureのリージョン一覧をExcelで利用できるようにする方法](https://blog.jbs.co.jp/entry/2025/05/30/114759)
**Source:** JBS Blog
**Published:** 2025-05-30 02:47:59 UTC
**Tags:** Azure, Power Query

**Digest:**
PowerShellのGet-AzLocationコマンドレットとPower Queryを活用し、Azureリージョンの情報をExcelで利用可能にする方法を解説。PowerShellでリージョン情報を取得し、Power Queryでデータ整形することで、リージョン名、対応サービス、可用性ゾーンなどをExcelで可視化・分析できます。

---

### [【Microsoft×生成AI連載】【Agents】Researcher Agentを使ってみた](https://blog.jbs.co.jp/entry/2025/05/30/090501)
**Source:** JBS Blog
**Published:** 2025-05-30 00:05:01 UTC
**Tags:** Copilot, Microsoft Copilot, Microsoft 365 Copilot, Microsoft×生成AI連載, 生成AI

**Digest:**
マイクロソフトの生成AI連載、今回はMicrosoft 365 Copilotの**宣言型エージェント**と**カスタムエンジンエージェント**について解説。2025年5月21日時点の情報で、**Researcher Agent**はFrontierプログラムのものです。機能、ライセンス、料金は変更の可能性あり。前回までの連載では**Researcher Agent**の紹介や利用、追加、実行、最新情報の調査などを行いました。

---

### [ショートカットでのAzure Virtual Desktopへの接続を試してみた](https://blog.jbs.co.jp/entry/2025/05/29/160027)
**Source:** JBS Blog
**Published:** 2025-05-29 07:00:27 UTC
**Tags:** AVD, Tech, 仮想デスクトップ, VDI, Azure, URI, Uniform Resource Identifier スキーム

**Digest:**
2023年にMicrosoftが公開したAzure Virtual Desktop (AVD) 用URIスキームを使うと、ショートカットからAVDに直接接続可能に！ クライアントアプリを使わず、URI（URL）形式で接続できます。 今回は、そのURIの作成方法とショートカット設定について解説します。 ID取得やURI作成の手順、ショートカットの作成・配置方法についても触れます。

---