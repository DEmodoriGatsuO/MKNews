# AI Tech Trends Digest (2025-07-11)


## Top Tech Articles from Qiita


### [Dify：新しいOCI Gen AIモデル(Grok, Llama, Cohere Embed)をPluginに追加してみた](https://qiita.com/yushibats/items/660246390861f76fce37)
**Published:** 2025-07-11 01:33:56 UTC
**Likes:** 22
**Tags:** oci, grok, LLM, LLaMA, Dify

**Digest:**
DifyでOCI Generative AIのGrok、Llama、Cohereモデルを利用可能に。**オープンソースプラットフォーム**Difyのプラグインにモデルを追加し、**Pull Request**で公式リポジトリに貢献。**リモートデバッグ機能**でテストコードなしに動作確認、**OCI OpenAI互換API**との連携もスムーズ。Difyの**プラグイン構成のシンプルさ**と**開発のしやすさ**が貢献を容易にしました。

---

### [Geminiの「Gem」機能を使ってみた。](https://qiita.com/inukai-masanori/items/657b53a232575ee8c44f)
**Published:** 2025-07-10 13:35:39 UTC
**Likes:** 5
**Tags:** AI, Gemini, 生成AI

**Digest:**
Google Geminiの「Gemini Gems」は、自分好みのAIアシスタントを作成できる機能です。GeminiサイドバーからGemを作成し、名前とカスタム指示を入力することで、特定のテーマや目的に合わせたAIを簡単に作れます。記事では、Suno AI向けの歌詞生成ツール作成例を紹介し、作成のコツや使用方法を解説しています。

---

### [Grok 4と他3つのAIモデルを同じ問題で試してみた](https://qiita.com/Dinn/items/6f9b1c4bca45d57d59de)
**Published:** 2025-07-11 00:03:57 UTC
**Likes:** 1
**Tags:** AI, grok, ChatGPT, LLM, Claude

**Digest:**
xAIのGrok 4を、筆者が他のAIモデルと比較検証。発表会で「ほぼ全大学院生より賢い」とMuskが豪語も、実用テストでは期待外れの結果に。STEM分野特化だが、物理解説、プログラミング、OCR、論理推理全てで他モデルに劣り、高額な月額料金に見合う性能を示せず。Gemini 2.5 Pro、Claude Opus 4、GPT o3の方が優位との評価。

---

### [MLflow体験型学習アプリ](https://qiita.com/taka_yayoi/items/064b1e08119bd5b4ca50)
**Published:** 2025-07-10 23:52:46 UTC
**Likes:** 1
**Tags:** Databricks, MLflow, Claude

**Digest:**
MLflowの認知向上を目指し、学習アプリをClaudeのアーティファクトで作成。初心者向けに、概念や用語を視覚的に理解できるよう工夫。MLflow TrackingやProjects、モデルレジストリなどの主要コンポーネントを体験可能で、モデルレジストリの操作もできます。理解度チェックも用意されており、シリーズ化も期待されます。

---

### [巨大言語モデルQwen3-235Bをフルスペックで動かすためのGPU選定ガイド](https://qiita.com/ryoshin0830/items/02602e309cb405d0f233)
**Published:** 2025-07-10 14:56:56 UTC
**Likes:** 1
**Tags:** GPU, インフラ, AI, LLM, Qwen

**Digest:**
2025年発表の2350億パラメータLLM、Qwen3-235BをVast.aiで**非量子化**で動かす構成と費用を調査。8×H100構成で$13.87/時から、8×H200なら$22.59/時間。**A100ではメモリ不足**で不可。**Interruptibleインスタンス**利用で最大73%割引も。AMDは非推奨。用途により商用APIや他モデル、**量子化**も検討。

---

## Latest News from RSS Feeds


### [New capabilities in Amazon SageMaker AI continue to transform how organizations develop AI models](https://aws.amazon.com/blogs/machine-learning/new-capabilities-in-amazon-sagemaker-ai-continue-to-transform-how-organizations-develop-ai-models/)
**Source:** AWS ML Blog
**Published:** 2025-07-10 19:08:49 UTC
**Tags:** Amazon Bedrock, Amazon SageMaker AI, Amazon SageMaker HyperPod, Amazon SageMaker JumpStart, Announcements

**Digest:**
Amazon SageMaker AIが新機能を発表。SageMaker HyperPodでは、トラブルシューティング時間を短縮するオブザーバビリティ機能と、JumpStartモデルの迅速なインフラなしデプロイが可能に。また、ローカルIDEからの接続も可能になり、MLflow 3.0もフルマネージドで利用可能に。これにより、AIモデル開発が加速します。

---

### [Accelerate foundation model development with one-click observability in Amazon SageMaker HyperPod](https://aws.amazon.com/blogs/machine-learning/accelerate-foundation-model-development-with-one-click-observability-in-amazon-sagemaker-hyperpod/)
**Source:** AWS ML Blog
**Published:** 2025-07-10 18:37:26 UTC
**Tags:** Amazon Managed Grafana, Amazon Managed Service for Prometheus, Amazon SageMaker HyperPod, Intermediate (200)

**Digest:**
Amazon SageMaker HyperPod は、基盤モデル (FM) 開発タスクとクラスタリソースに関する洞察を提供するダッシュボードを導入。Amazon Managed Service for Prometheus と Amazon Managed Grafana での可視化により、GPU 使用率、タスクレベルのパフォーマンスを可視化。ワンクリックでインストールでき、問題診断を加速。カスタムアラート設定も可能で、FM開発の効率化、コスト削減に貢献します。

---

### [Accelerating generative AI development with fully managed MLflow 3.0 on Amazon SageMaker AI](https://aws.amazon.com/blogs/machine-learning/accelerating-generative-ai-development-with-fully-managed-mlflow-3-0-on-amazon-sagemaker-ai/)
**Source:** AWS ML Blog
**Published:** 2025-07-10 18:35:01 UTC
**Tags:** Amazon SageMaker AI, Announcements, Technical How-to

**Digest:**
Amazon SageMakerのMLflow 3.0が完全マネージドで登場。AI実験を効率化し、生成AI開発を加速します。新機能により、実験追跡、モデル挙動の可視化が可能になり、デバッグやコスト最適化に貢献。生成AIアプリケーションのトレーシングやバージョン管理も容易に。AWS CLI、API、SageMaker Studioから利用開始でき、AWSアカウントとSageMaker Studio AIドメインが必要です。

---

### [Amazon SageMaker HyperPod launches model deployments to accelerate the generative AI model development lifecycle](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-hyperpod-launches-model-deployments-to-accelerate-the-generative-ai-model-development-lifecycle/)
**Source:** AWS ML Blog
**Published:** 2025-07-10 18:34:14 UTC
**Tags:** Amazon SageMaker HyperPod, Announcements

**Digest:**
Amazon SageMaker HyperPodが、JumpStartモデルやS3/FSxのカスタムモデルのデプロイに対応。Kubernetes上で大規模AIモデルのトレーニングからデプロイ、スケーリングまでを効率化。ワンクリックデプロイ、自動スケーリング、SageMakerエンドポイント連携など新機能も追加。HyperPod CLI、SDK、kubectlでの柔軟なデプロイを可能にし、運用を簡素化します。

---

### [Supercharge your AI workflows by connecting to SageMaker Studio from Visual Studio Code](https://aws.amazon.com/blogs/machine-learning/supercharge-your-ai-workflows-by-connecting-to-sagemaker-studio-from-visual-studio-code/)
**Source:** AWS ML Blog
**Published:** 2025-07-10 18:33:58 UTC
**Tags:** Advanced (300), Amazon SageMaker Studio, Technical How-to

**Digest:**
Amazon SageMaker Studioの機能をローカルVS Codeで利用可能になり、AI開発者やMLエンジニアは、慣れたIDE環境で開発できます。AWS Toolkitを使い、SageMaker Studioに接続し、カスタム拡張機能やデバッグツール、AIアシスト開発ツールなどを利用しつつ、SageMakerのAIリソースにアクセスできます。これにより、既存のワークフローを維持し、生産性を向上させつつ、機械学習モデルの開発、トレーニング、デプロイが可能になります。

---

### [What’s new in Copilot Studio: June 2025](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/whats-new-in-copilot-studio-june-2025/)
**Source:** Microsoft 365 Blog
**Published:** 2025-07-10 16:00:00 UTC
**Tags:** AI, Copilot Studio

**Digest:**
Microsoft 365 Blogの月次まとめ記事によると、2025年6月にリリースされたMicrosoft Copilot Studioの新機能が紹介されています。今回の記事では、Copilot Studioのアップデート内容を詳しく解説しており、ユーザーにとって役立つ情報が満載です。

---

### [【Microsoft Azure】共有ディスクを利用したWSFCの構築方法](https://blog.jbs.co.jp/entry/2025/07/11/135816)
**Source:** JBS Blog
**Published:** 2025-07-11 04:58:16 UTC
**Tags:** Windows Server, Azure, Azure Virtual Machines, ディスク

**Digest:**
Azure共有ディスクは、複数のVMから1つのディスクに同時接続を可能にします。Windows Server Failover Clustering（WSFC）と組み合わせることで、VM障害時もダウンタイムなくディスクへアクセスできます。この記事では、この共有ディスクを活用したWSFC構築方法を解説します。

---

### [Veeamを使ってAmazon S3へバックアップしてみる第3弾 バックアップ編](https://blog.jbs.co.jp/entry/2025/07/11/105454)
**Source:** JBS Blog
**Published:** 2025-07-11 01:54:54 UTC
**Tags:** Veeam, AWS, Amazon S3

**Digest:**
前回の続きで、VeeamからAmazon S3へのバックアップ動作検証を行います。Veeamコンソールでバックアップジョブを作成し、仮想マシンを選択後、S3ストレージを設定します。ジョブを手動で実行し、バックアップが正常に行われるか確認します。詳細手順と結果は、後ほど説明します。

---

### [【Microsoft×生成AI連載】【ノートブック】Microsoft 365 Copilot ノートブックを使ってみた](https://blog.jbs.co.jp/entry/2025/07/11/094400)
**Source:** JBS Blog
**Published:** 2025-07-11 00:44:00 UTC
**Tags:** Copilot, Microsoft Copilot, Microsoft 365 Copilot, 生成AI, Microsoft×生成AI連載

**Digest:**
Microsoft 365 Copilot ノートブックの使い方を紹介する連載記事です。ノートブックの作成、参考資料の追加、Copilotへのプロンプト適用方法、チャット内容の追加などを解説。利用シーン、メリット、注意点も説明し、過去の連載記事へのリンクもあります。

---