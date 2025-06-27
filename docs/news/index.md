# AI Tech Trends Digest (2025-06-27)


## Top Tech Articles from Qiita


### [Gemini CLI を試したいので Claude Code でも同じことをしてみて感じた活路](https://qiita.com/hokutohagi/items/4eae63a48e74966aeebd)
**Published:** 2025-06-26 15:25:02 UTC
**Likes:** 9
**Tags:** Gemini, Claude

**Digest:**
GoogleのGemini CLIとClaude Codeを、Remixプロジェクトの技術調査で比較検証。GeminiはREADME読み込みやnpmコマンド実行で技術スタックを分析、改善点を提案。Claudeは、セキュリティ脆弱性やテスト体制など多角的な調査で詳細な改善計画を提示。両者の特性を活かし、Geminiをオーケストレータ、Claudeを遊撃手として共存させ、開発効率向上を図る可能性を考察しています。

---

### [Ryzen AI APU でローカルLLMを立ち上げる手順](https://qiita.com/y-mrkm/items/07a8e770decba227e0cc)
**Published:** 2025-06-26 08:00:10 UTC
**Likes:** 5
**Tags:** Ryzen, ROCm, LLM, ollama, open-webui

**Digest:**
Ryzen AI 9 HX 370搭載ミニPCで、ollamaとopen-webuiを利用しチャット環境を構築。UbuntuにROCmを導入するため、BIOSのSecure Bootを無効化。ドライバインストール後、ollamaは環境変数設定、open-webuiはDockerで起動。ユーザー追加やモデル公開設定も必要。dGPUとの速度比較では劣るものの、96GBメモリを生かした活用を模索。

---

### [Gemini CLI から Imagen を呼び出し！ MCPサーバー経由で画像生成](https://qiita.com/te_yama/items/db572cad90a3ae221847)
**Published:** 2025-06-26 13:44:17 UTC
**Likes:** 4
**Tags:** MCP, Gemini, GoogleCloud, GeminiCLI

**Digest:**
Google Cloudの生成メディアAPI（Imagen、Veoなど）を利用できるMCP ServersをGemini CLIから利用する方法を紹介。リポジトリからインストールし、認証設定後、Gemini CLI設定でImagenを呼び出す。ローカル保存とGCS保存に対応しており、`~/.gemini/settings.json`で設定。プロンプトを入力して画像を生成し、期待通りの結果を得られました。

---

### [Gemini CLIでMCPを使ってみた](https://qiita.com/n0bisuke/items/8686a74d8edcb5d29265)
**Published:** 2025-06-27 03:30:49 UTC
**Likes:** 3
**Tags:** JavaScript, Node.js, MCP, Gemini, VibeCoding

**Digest:**
Gemini CLIでMCP設定を試しました。`npm install -g @google/gemini-cli`でインストール後、`~/.gemini/settings.json`を編集し、MCPサーバー設定を記述します。Node.jsで自作したQiitaとGyazoアップローダーを設定し、`/mcp`で確認。画像アップロードを試したところ、MCP経由でGyazoへのアップロードに成功しました。

---

### [VSCodeで動かすGemini CLI](https://qiita.com/yukima77/items/1631d7cf21c2a6eadbc3)
**Published:** 2025-06-26 06:33:14 UTC
**Likes:** 2
**Tags:** VSCode, Gemini, GeminiCLI

**Digest:**
2025年6月リリースの「Gemini CLI」は、ターミナルでGemini 2.5 Proモデルを利用できるAIエージェント。本記事では、導入後のVisual Studio Codeターミナルでの動作結果を紹介。Gemini CLIをインストール後、VS Codeを起動し、ターミナルで`npx`コマンドを実行すると、無事起動することを確認しました。

---

## Latest News from RSS Feeds


### [Tailor responsible AI with new safeguard tiers in Amazon Bedrock Guardrails](https://aws.amazon.com/blogs/machine-learning/tailor-responsible-ai-with-new-safeguard-tiers-in-amazon-bedrock-guardrails/)
**Source:** AWS ML Blog
**Published:** 2025-06-26 22:41:26 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Guardrails, Artificial Intelligence, Best Practices, Generative AI, Responsible AI, Technical How-to, Thought Leadership

**Digest:**
Amazon Bedrock Guardrailsに、用途に合わせて保護レベルを選べる「セーフガードティア」が登場。コンテンツフィルタと拒否トピックに対し、低レイテンシのClassicと、多言語対応・高精度なStandardを選択可能に。 Standardは多言語対応が強化され、Cross-Region Inferenceもサポート。AWSコンソールまたはSDKで設定し、テストデータで評価できます。

---

### [Structured data response with Amazon Bedrock: Prompt Engineering and Tool Use](https://aws.amazon.com/blogs/machine-learning/structured-data-response-with-amazon-bedrock-prompt-engineering-and-tool-use/)
**Source:** AWS ML Blog
**Published:** 2025-06-26 15:46:20 UTC
**Tags:** Amazon Bedrock, Best Practices, Generative AI, Intermediate (200), Technical How-to

**Digest:**
Amazon Bedrockで構造化された応答を生成する2つの方法を紹介。1つは、プロンプトエンジニアリングで、明確なプロンプトでLLMのJSON出力を制御。もう1つは、Tool Useで、JSONスキーマをツール定義に統合し、API連携を容易にする。Claudeモデルのテストでは、Tool Useが優勢。構造化データは、APIやデータ活用に重要で、Bedrockで活用可能。

---

### [Using Amazon SageMaker AI Random Cut Forest for NASA’s Blue Origin spacecraft sensor data](https://aws.amazon.com/blogs/machine-learning/using-amazon-sagemaker-ai-random-cut-forest-for-nasas-blue-origin-spacecraft-sensor-data/)
**Source:** AWS ML Blog
**Published:** 2025-06-26 15:41:46 UTC
**Tags:** Aerospace & Satellite, Amazon SageMaker, Amazon SageMaker AI, Amazon Simple Storage Service (S3), Amazon VPC, Artificial Intelligence, Intermediate (200), Python, Technical How-to

**Digest:**
AWS SageMaker AI を利用し、NASAとBlue Originの月面着陸データから、宇宙機の異常を検出する手法を紹介。Random Cut Forest アルゴリズム（RCF）を用いて、位置、速度、姿勢データの異常を解析。データの前処理、RCFモデルの学習、バッチ処理による大規模データ対応、可視化、S3への保存を行い、宇宙ミッションの安全性向上に貢献します。

---

### [Terraformにてwrite-only attributeを利用する](https://blog.jbs.co.jp/entry/2025/06/27/132841)
**Source:** JBS Blog
**Published:** 2025-06-27 04:28:41 UTC
**Tags:** Azure, Terraform

**Digest:**
Terraform v1.11.0で導入された「write-only attributes」機能を解説。秘匿性の高い属性値をTerraformステートファイルに保存しないようにできる新機能です。従来のステートファイル確認と、write-only属性適用後のステート比較を通して、その違いとメリットを検証します。

---

### [【Microsoft×生成AI連載】Microsoft 365 Copilotの画像生成機能を使ってみた](https://blog.jbs.co.jp/entry/2025/06/27/090232)
**Source:** JBS Blog
**Published:** 2025-06-27 00:02:32 UTC
**Tags:** Microsoft×生成AI連載, 生成AI, M365, Microsoft 365 Copilot, Microsoft Copilot

**Digest:**
マイクロソフトの生成AI連載記事、今回はMicrosoft 365 Copilotの画像生成機能に焦点を当てています。ブランドキット作成やロゴ・色・フォントの追加、画像の生成、ポスターやバナー作成について解説。利用シーン、メリット、注意点も紹介しており、Copilot Chatによる要約も掲載。過去連載記事へのリンクもあります。

---