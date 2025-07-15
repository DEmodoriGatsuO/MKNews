# AI Tech Trends Digest (2025-07-15)


## Top Tech Articles from Qiita


### [AWSの新しいAIエージェント搭載IDE「Kiro」のSpecモードを使用して開発する](https://qiita.com/nasuvitz/items/e3226758fbb1c402aa9f)
**Published:** 2025-07-14 18:20:23 UTC
**Likes:** 30
**Tags:** AWS, IDE, Claude, AIエージェント, Kiro

**Digest:**
AWSが2025/7/14に発表したAI搭載IDE「Kiro」を試用。MacOSにインストールし、SNS/AWS IDでログイン、VS Code設定もインポート可能。テーマ選択後、プロジェクトを作成し、Steeringファイル生成。VibeとSpecの2モードがあり、Specでは要件定義から設計、実装までを体系的に進め、タスク実行でコード生成。Agent Hooks設定やMCPサーバ連携も可能。プレビュー期間は無料、Pro/Pro+プランも用意。

---

### [Kiroが来た！純AWSのAIコーディングエージェント搭載IDEをちょっとだけ試してみた](https://qiita.com/shimagaji/items/a8f2049e7f178f33abd4)
**Published:** 2025-07-14 17:14:14 UTC
**Likes:** 16
**Tags:** AWS, IDE, GenerativeAI, AmazonQDeveloper, Kiro

**Digest:**
2025年7月、AWSから生成AI搭載IDE「Kiro」が登場。VS CodeにAIコーディングエージェントが統合され、競合はCursor。仕様駆動開発（Spec-driven development）を特徴とし、プロンプトから要件定義、システム設計、タスクへと変換。Mac/Windows/Linux版あり。IAM Identity Center認証、日本語対応。プレビュー期間は無料、正式版はサブスクリプション制。モデルはAnthropic Claude Sonnet。Amazon Q Developer Proとの関係性にも注目が集まっています。

---

### [Tips: /hooksを使ってClaude Codeに実行完了したら通知音を鳴らしてもらう](https://qiita.com/getty104/items/986c323ea5c9cc32f72d)
**Published:** 2025-07-14 14:52:21 UTC
**Likes:** 7
**Tags:** tips, AI, Claude, ClaudeCode

**Digest:**
Claude Codeの処理時間に着目し、完了通知を設定する方法を紹介します。 `/hooks`機能を使って、実行停止時に通知音を再生するようにします。Macユーザー向けに、`afplay`コマンドで音声を再生する手順を説明。Claude Codeで`/hooks`を実行し、イベントを`Stop`に設定、`User settings`で保存すれば、作業完了時に通知が受け取れます。

---

### [マルチエージェント論争と AutoGen: 次世代コンテキストエンジニアリングメモ](https://qiita.com/nohanaga/items/f974bcc4b1d49702c320)
**Published:** 2025-07-14 08:33:23 UTC
**Likes:** 6
**Tags:** Azure, LangChain, Anthropic, AutoGen

**Digest:**
Cognition AI, Anthropic, LangChain Blog がマルチエージェント開発を論じ、AutoGen の機能が各主張をどう吸収するかを考察。Cognition AI はコンテキスト共有の重要性、Anthropic は並列化による効果、LangChain はコンテキストエンジニアリングを強調。AutoGen は、GroupChat、GraphFlow、Memory、UserProxyAgent などの機能で、各社の懸念や利点を踏まえつつ、研究用途でのマルチエージェント活用を支援する。

---

### [ClaudeはPRを綴った - GitHub Actions × Bedrock 物語](https://qiita.com/naka_kyon/items/f34e13f71c5b3cdc9c25)
**Published:** 2025-07-15 04:31:35 UTC
**Likes:** 4
**Tags:** ポエム, AI, bedrock, GitHubActions, Claude

**Digest:**
GitHub ActionsとAWS Bedrockを連携し、AI Claudeを活用する技術記事。  著者は、Claude CodeとGitHub Appを準備し、AWS IAM OIDC Provider設定でBedrockアクセス権限を付与。  GitHubリポジトリにシークレットとアクション定義を記述。  Issueに@claudeと記述するとコード生成とPR作成が行われ、開発効率向上を確認。  舞台裏では、GitHub Actions, OIDC, AWS, Bedrockが連携してAIを呼び出す。

---

## Latest News from RSS Feeds


### [Build AI-driven policy creation for vehicle data collection and automation using Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/build-ai-driven-policy-creation-for-vehicle-data-collection-and-automation-using-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-07-14 16:58:48 UTC
**Tags:** Amazon Bedrock, Artificial Intelligence, Automotive, Intermediate (200)

**Digest:**
Sonatusは、自動車向けSoftware-Defined Vehicle（SDV）で、データ収集と自動化ポリシーを生成するシステムを開発。Amazon Bedrockと連携し、自然言語入力からCollector AIとAutomator AIのポリシーを生成する。これにより、ポリシー作成時間を大幅短縮、非エンジニアも利用可能に。複雑なイベント構造やデータ形式、品質管理などの課題を克服し、多エージェントアプローチで精度向上を図った。

---

### [How Rapid7 automates vulnerability risk scores with ML pipelines using Amazon SageMaker AI](https://aws.amazon.com/blogs/machine-learning/how-rapid7-automates-vulnerability-risk-scores-with-ml-pipelines-using-amazon-sagemaker-ai/)
**Source:** AWS ML Blog
**Published:** 2025-07-14 16:55:56 UTC
**Tags:** Amazon Machine Learning, Amazon SageMaker AI, Customer Solutions, DevOps

**Digest:**
Rapid7は、ソフトウェア脆弱性の深刻度を予測する機械学習モデルを、Amazon SageMaker AIで自動化。CVSSスコアの予測精度を向上させ、手作業を削減。CI/CDパイプラインを構築し、モデルの継続的な訓練とデプロイを実現。Inference Componentsにより、低コストで迅速なインフラ運用を達成。結果、運用コストを半減、エンジニアは高価値業務に集中可能になった。

---

### [Build secure RAG applications with AWS serverless data lakes](https://aws.amazon.com/blogs/machine-learning/build-secure-rag-applications-with-aws-serverless-data-lakes/)
**Source:** AWS ML Blog
**Published:** 2025-07-14 16:51:39 UTC
**Tags:** Amazon Machine Learning, Amazon SageMaker, Amazon SageMaker Data & AI Governance, Amazon SageMaker Lakehouse, Amazon Simple Storage Service (S3), Best Practices, Customer Solutions, Generative AI, Technical How-to

**Digest:**
生成AIの成功には堅牢なデータ戦略が不可欠で、RAGアプリケーションが注目されています。本記事では、AWS S3やDynamoDBを用いたセキュアなRAG構築を解説。データレイクを基盤とし、アクセス制御、データプライバシー、データ分類を徹底することで、セキュリティとコンプライアンスを両立。Amazon ComprehendによるPIIのマスキングも紹介しています。

---

### [【GxP社プレスリリース】 Copilot+ PC 向けオフライン AI アプリを開発 —  NPU 活用でエンタープライズ現場に革新を](https://blogs.windows.com/japan/2025/07/15/gxp-press-release-copilot-pc-ai-app-development/)
**Source:** Windows Blog for Japan
**Published:** 2025-07-15 02:23:18 UTC
**Tags:** Surface, Surface Copilot+ PC

**Digest:**
GxP社が、Surface Copilot+ PC の NPU を活用し、オフライン環境でも高い応答性とセキュリティを実現するカスタム AI アプリを開発。製造現場や医療・公共分野など、ネットワーク接続が難しい環境でも生成 AI を活用可能に。Windows AI Foundry を利用し、企業固有の業務に最適化されたアプリを開発支援。Microsoft も次世代のエンタープライズ DX を象徴する取り組みと評価しています。

---

### [【OpManager使ってみた】第2回 OpManagerの初期設定](https://blog.jbs.co.jp/entry/2025/07/15/105552)
**Source:** JBS Blog
**Published:** 2025-07-15 01:55:52 UTC
**Tags:** Tech, OpManager, 監視, Windows

**Digest:**
OpManagerの初期設定について解説します。インストール後の初期設定として、起動、ログインパスワード変更、AD認証設定を行います。また、設定ファイル（wrapper.conf、threads.conf、aaproduct_ext.conf）の編集も必要です。

---

### [JamfとIntuneにおけるグループ作成方法の違い](https://blog.jbs.co.jp/entry/2025/07/15/090859)
**Source:** JBS Blog
**Published:** 2025-07-15 00:08:59 UTC
**Tags:** Jamf, Jamf Pro, Intune, Microsoft Intune

**Digest:**
Jamf ProとIntuneは、デバイス管理ツールとして成熟していますが、対象プラットフォームが異なります。Jamf ProはmacOSなどAppleデバイスに特化し、IntuneはWindows、iOS、Androidなどに対応しています。本記事では、両者の「グループ作成」に着目し、手順や特徴の違いを比較検討しています。

---

### [Power Apps での画像の扱いと Power Automate を使った SharePoint への画像の保存](https://shanqiai.lekumo.biz/sharepoint_technical_note/2025/07/power-apps-powe-e036.html)
**Source:** SharePoint Technical Notes
**Published:** 2025-07-14 22:15:39 UTC
**Tags:** Microsoft 365 - SharePoint, Power Apps, Power Automate

**Digest:**
今年の2月、Power Apps研修でモバイルアプリにカメラ機能を実装。Power Appsのカメラコントロールで写真撮影、画像保存、ギャラリー表示を体験。データソースとしてSharePointリストを活用し、研修を通してPower Appsの基礎を習得しました。

---