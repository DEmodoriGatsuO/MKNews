# AI Tech Trends Digest (2025-11-22)


## Top Tech Articles from Qiita


### [Antigravity（Google Gemini Code Assist）を日本語化する方法](https://qiita.com/take_naka/items/e2ac7f9cd4fd698bbc12)
**Published:** 2025-11-21 07:09:06 UTC
**Likes:** 6
**Tags:** Gemini, Antigravity

**Digest:**
Google Gemini Code Assist（Antigravity）でタスク名やアーティファクトが英語表示される問題の解決策。`.gemini/GEMINI.md` に`<user_rules>`を追加し、言語設定、アーティファクト、コードコメントを日本語化。これにより、タスクUIや生成されるドキュメントが日本語になり、快適な開発が可能に。一度設定すれば永続的に適用される。

---

### [Codex CLIにWebスクレイピングの翼を授ける話（Bright Data MCP 連携メモ）](https://qiita.com/AI_Beginner_Note/items/939cc4c80a22188747cd)
**Published:** 2025-11-21 16:16:42 UTC
**Likes:** 2
**Tags:** スクレイピング, 自動化, MCP, OpenAI, AIエージェント

**Digest:**
ChatGPT Plus契約を機に、OpenAI CodexでWebスクレイピングに挑戦。Bright Dataの`Web MCP`とCodex CLIを統合し、動的サイトからのデータ取得を試みる。Codex CLIのインストールとBright Data APIキー設定を行い、InstagramやGoogle Mapの情報を取得。結果、CodexとBright Dataの組み合わせで、より柔軟なデータ収集が可能になった。

---

### [Hugging Face形式をgguf形式にしてElixirでOllamaを使う](https://qiita.com/t-yamanashi/items/ceaccc72bf4833ac1d15)
**Published:** 2025-11-21 10:41:56 UTC
**Likes:** 2
**Tags:** Ubuntu, Elixir, AI, LLM, ollama

**Digest:**
ElixirでHugging Face形式のLLMを動かすため、Ollamaを介してgguf形式に変換する手順を解説。CUDA環境構築の難しさから、UbuntuでGPUを利用する代わりに、Macのように手軽にLLMを実行するため。llama.cppで変換し、Ollamaに登録後、Elixirから呼び出す方法を紹介。H2O LLM Studioでファインチューニングしたモデルの例も示しています。

---

### [Antigravity使うのやめてCopilotに戻った話](https://qiita.com/tubasa854/items/bf96feb1a0d26fe3a4c7)
**Published:** 2025-11-21 21:38:41 UTC
**Likes:** 1
**Tags:** Next.js, copilot, LLM, gemini3.0, Antigravity

**Digest:**
Google DeepMindのAI開発プラットフォーム「Antigravity」を試用。Gemini 3搭載、エージェント駆動IDEだが、ブラウザ統合の重さやGitの頻繁な確認で実用性に欠ける。Nano Bananaの画像生成は魅力。Gemini 3の日本語対応も課題。Copilotの軽快さ、Git連携、日本語理解の方が優勢。v0のようなスクラッチ開発には向く。

---

### [非Web系プログラマが、1万円WordPressサイトをAIでリニューアルし始めた記録（進行中）](https://qiita.com/seika-chi/items/15a2ef30dd44f9c42e2d)
**Published:** 2025-11-21 08:27:47 UTC
**Likes:** 1
**Tags:** フリーランス, Gemini, Webサイト制作, Claude, AI活用

**Digest:**
ITエンジニアが、**AI活用** で個人サイトをリニューアル中。4年間運用したWordPressサイトはElementorで構築、予約導線やUI/UXに課題が。**Gemini/Claude** を使い、HTML/CSS での再構築とブランド再設計に着手。Gemini Pro 3のデザイン性能に期待しつつ、ローコードでのサイト整備を目指す。

---

## Latest News from RSS Feeds


### [Android と iPhone 間でファイル共有ができるようになりました。 Google Pixel 10 シリーズより提供開始](https://blog.google/intl/ja-jp/feed/quick-share-airdrop/)
**Source:** Google Japan Blog
**Published:** 2025-11-21 16:19:00 UTC
**Tags:** Android

**Digest:**
家族や友人と写真やファイルを共有する際、デバイスの違いを気にせず簡単に共有したい、という要望に応え、Googleの**Quick Share**が**AirDrop**と連携可能になりました。これにより、**Android**と**iOS**間のファイル共有がよりスムーズになり、誰とでも瞬時にコンテンツを共有できるようになりました。

---

### [Nano Banana 1 が Google 検索、NotebookLM に登場](https://blog.google/intl/ja-jp/products/connect-communicate/nano-banana-on-search/)
**Source:** Google Japan Blog
**Published:** 2025-11-21 14:09:00 UTC
**Tags:** Search, AI

**Digest:**
Google検索に画像編集モデルが追加され、GoogleレンズとAIモードで写真編集が可能に。検索から直接アクセスし、AIを活用した高度な編集機能で、写真の加工が手軽に行えるようになりました。

---

### [Streamline AI operations with the Multi-Provider Generative AI Gateway reference architecture](https://aws.amazon.com/blogs/machine-learning/streamline-ai-operations-with-the-multi-provider-generative-ai-gateway-reference-architecture/)
**Source:** AWS ML Blog
**Published:** 2025-11-21 20:34:56 UTC
**Tags:** Amazon Bedrock, Amazon SageMaker, Intermediate (200), Open Source, Technical How-to

**Digest:**
AWSの「Generative AI Gateway」は、AIモデルへのアクセスを統合管理するリファレンスアーキテクチャ。Amazon Bedrock、SageMaker AI、LiteLLMなどを組み合わせ、複数のAIプロバイダーを単一インターフェースで管理。コスト管理、セキュリティ強化、負荷分散、プロンプトキャッシングなどの機能を持ち、ECSやEKSで利用可能。オープンソースのLiteLLMを活用し、ガバナンスと監視も実現します。

---

### [Deploy geospatial agents with Foursquare Spatial H3 Hub and Amazon SageMaker AI](https://aws.amazon.com/blogs/machine-learning/deploy-geospatial-agents-with-foursquare-spatial-h3-hub-and-amazon-sagemaker-ai/)
**Source:** AWS ML Blog
**Published:** 2025-11-21 17:15:31 UTC
**Tags:** Amazon SageMaker, Amazon SageMaker AI, Artificial Intelligence, Geospatial ML with Amazon SageMaker, Intermediate (200)

**Digest:**
地理空間AIエージェント構築について、Foursquare Spatial H3 Hubの分析用データとAmazon SageMaker AI上の推論モデルを組み合わせ、非技術者でも自然言語で複雑な空間分析を可能に。H3グリッドでデータ形式の課題を解決、推論モデルで複雑なワークフローを自動化、SageMaker AIでインフラ管理を簡素化し、迅速な分析とコスト効率を実現します。

---

### [How Wipro PARI accelerates PLC code generation using Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/how-wipro-pari-accelerates-plc-code-generation-using-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-11-21 16:10:26 UTC
**Tags:** Amazon Bedrock, Customer Solutions, AI/ML, AWS Customer, Generative AI

**Digest:**
Wipro PARIは、Amazon BedrockとAnthropicのClaudeを活用し、PLCラダーコード生成を革新。従来の3～4日を10分に短縮、精度85%向上を実現。IEC 61131-3準拠、自動検証、状態管理、変数宣言、監査証跡も提供。Wiproは、AIによる自動化で、製造現場におけるコード生成の課題を解決し、運用効率化に貢献しています。

---

### [Ignite 2025: フロンティア組織でのWindows](https://blogs.windows.com/japan/2025/11/21/ignite-2025-windows-at-the-frontier-of-work/)
**Source:** Windows Blog for Japan
**Published:** 2025-11-21 12:52:20 UTC
**Tags:** Windows 11, Windows 365, AI, Copilot, Windows, Windows 365 Cloud Apps, Windows 365 Link, Windows Hello

**Digest:**
Microsoft Ignite 2025では、WindowsがAI時代に対応し、**AIエージェント** を統合したプラットフォームへと進化。タスクバーからの Copilot アクセス、**Agent workspace** (プレビュー)や **Windows 365 for Agents** (プレビュー)によるエージェント管理を実現。セキュリティ強化として、ポスト量子暗号（一般提供）、**Windows Cloud I/O Protection** (プレビュー)などを発表。柔軟な働き方を支援し、Windows 365 Link 拡充も。

---

### [Microsoft 365 Copilot の新機能 | 2025 年 10 月](https://blogs.windows.com/japan/2025/11/21/whats-new-in-microsoft-365-copilot-october-2025/)
**Source:** Windows Blog for Japan
**Published:** 2025-11-21 09:30:10 UTC
**Tags:** Copilot, What's new in Copilot

**Digest:**
2025年10月のMicrosoft 365 Copilot新機能を紹介。Copilot ChatでGPT-5モデルや、カレンダー検索、Bing Webカード連携が強化。Teamsの音声要約や、Word、Excelのエージェントモードも登場。管理者はCopilot制御システムで、レポート機能やタスクバーへのアプリピン留めが可能に。チームリーダー向けダッシュボードも追加。

---