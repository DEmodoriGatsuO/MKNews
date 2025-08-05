# AI Tech Trends Digest (2025-08-05)


## Top Tech Articles from Qiita


### [「Claude × Draw.io × スイムレーン」で業務フロー図のたたきを瞬時に作るプロンプト](https://qiita.com/WdknWdkn/items/de2aeced1faf948ac125)
**Published:** 2025-08-04 09:33:22 UTC
**Likes:** 20
**Tags:** プロジェクト管理, プロンプト, Draw.io, 生成AI, Claude

**Digest:**
Cursor→Claudeを使った開発PMが、プロンプトでワークフロー図作成の課題解決に挑戦。ヒアリング漏れ防止のため、質問をプロンプト化し、ChatGPTに肩代わりさせます。分析アシスタントと図作成プロンプトを提供。**draw.io形式**で、スイムレーンやレイアウトの設計原則を指示し、若手でも使いやすい図を生成。**実践Tips**でよくある詰みを回避し、最初の30分をChatGPTに丸投げしてレビューする運用を推奨しています。

---

### [ClaudeCodeでSerenaMCP導入時にTerraformファイルがあるとエラーになる事がある](https://qiita.com/sodafloatlab/items/79958a7a492ba4e05188)
**Published:** 2025-08-04 17:06:42 UTC
**Likes:** 2
**Tags:** Terraform, Serena, MCP, Claude, ClaudeCode

**Digest:**
ClaudeCodeでSerenaMCPサーバ導入時にTerraformエラーが発生。原因は、2025/8/5時点でSerenaMCPがTerraform未対応であること。解決策は、「~/.serena/project.yml」のlanguageをpythonに、ignored_pathsにTerraform管理パスを追加すること。これにより、SerenaMCPサーバの初期化に成功しました。

---

### [Claude活用術：量子物理学ゲーム「フォトン・ハーモニー」を3分で実装する方法](https://qiita.com/daisuke-team-ai/items/fc142e82bd4a3834ffa5)
**Published:** 2025-08-05 00:17:53 UTC
**Likes:** 1
**Tags:** JavaScript, AI, プロンプトエンジニアリング, Claude, VibeCoding

**Digest:**
Claude Sonnet 4を用いて、Web Audio APIや物理演算を活用した教育ゲーム「フォトン・ハーモニー」を3分で実装。波長と音階のマップ、動的色変換、物理シミュレーション機能を搭載。AIへの段階的指示と物理的正確性の重視、ユーザビリティへの配慮が成功の鍵。VR/AR、機械学習、マルチプレイヤー対応など、今後の展開も期待されます。

---

### [ChatGPT/Claude活用術：Conway's Game of Life の人工生命を3分で実装する方法](https://qiita.com/daisuke-team-ai/items/dd3eb40479cf1a04e5a3)
**Published:** 2025-08-05 00:10:33 UTC
**Likes:** 1
**Tags:** JavaScript, AI, プロンプトエンジニアリング, Claude, VibeCoding

**Digest:**
AIを活用した**Vibe Coding**で、**3分**でConway's Game of Lifeを実装！  JavaScriptとAIの協働で、**インタラクティブなキャンバス**、再生/一時停止、プリセット、統計表示などを実現。効果的なプロンプト設計、UI改善、機能拡張の手法を公開。生命シミュレーションの基本概念と**AI活用開発**を学べます。

---

### [Google AI Studio (Gemini) API と LangChain で、RAG を実装してみた](https://qiita.com/nakano0328/items/916a4284f264b848c947)
**Published:** 2025-08-04 23:37:36 UTC
**Likes:** 1
**Tags:** AI, Gemini, rag, LLM

**Digest:**
株式会社HIBARIの中野氏が、Google AI StudioのGemini APIとLangChainを活用したRAGシステムを開発。`data`ディレクトリのテキストファイルをナレッジベースとし、質問に回答します。`build_vectordb.py`でベクトルデータベースを構築、`chat.py`で質問応答。APIキー設定、依存関係インストール後、`build_vectordb.py`でデータベースを構築し、`chat.py`でチャットを開始できます。

---

## Latest News from RSS Feeds


### [Cost tracking multi-tenant model inference on Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/cost-tracking-multi-tenant-model-inference-on-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-08-05 01:17:30 UTC
**Tags:** Advanced (300), Amazon Bedrock, Amazon QuickSight, Cloud Cost Optimization

**Digest:**
Amazon BedrockのConverse APIで、テナント別のモデル利用状況を分析する方法を紹介。`requestMetadata`パラメータでテナントIDなどを付与し、AWS GlueとQuickSightで可視化。これにより、コスト追跡、利用パターン分析、テナントごとの最適化が可能に。Application Inference Profilesと組み合わせて、より詳細なコスト管理も実現します。

---

### [AI judging AI: Scaling unstructured text analysis with Amazon Nova](https://aws.amazon.com/blogs/machine-learning/ai-judging-ai-scaling-unstructured-text-analysis-with-amazon-nova/)
**Source:** AWS ML Blog
**Published:** 2025-08-04 17:51:08 UTC
**Tags:** Amazon Bedrock, Amazon Nova, Artificial Intelligence, Technical How-to

**Digest:**
Amazon Bedrockを活用したLLM（大規模言語モデル） Jury Systemを紹介。顧客フィードバック分析を例に、複数LLMを「審査員」として活用し、テーマ別要約の質を評価します。Anthropic Claude 3 SonnetやAmazon Nova ProなどのモデルをAmazon SageMakerで展開。評価指標には、合意率、Cohen's kappa、Spearman's rho、Krippendorff's alphaを使用。効率的なデータ分析と、人手を介した監督の重要性を強調しています。

---

### [Building an AI-driven course content generation system using Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/building-an-ai-driven-course-content-generation-system-using-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-08-04 17:46:30 UTC
**Tags:** Advanced (300), Amazon Bedrock, Amazon Machine Learning, Education, Generative AI, Higher education, Public Sector, Technical How-to

**Digest:**
教育現場の課題解決のため、AWS上でAnthropicのClaude 3.5を利用し、AIが講義資料を生成するシステムを構築。**コースアウトライン**と**コンテンツ生成**の2つのコアモジュールを**WebSocket API**で連携。**Amazon Cognito**による認証、**AWS WAF**と**CloudFront**によるセキュリティとパフォーマンス向上も実現。AWS CDKでインフラをコード化。

---

### [How Handmade.com modernizes product image and description handling with Amazon Bedrock and Amazon OpenSearch Service](https://aws.amazon.com/blogs/machine-learning/how-handmade-com-modernizes-product-image-and-description-handling-with-amazon-bedrock-and-amazon-opensearch-service/)
**Source:** AWS ML Blog
**Published:** 2025-08-04 17:21:16 UTC
**Tags:** Amazon Bedrock, Amazon OpenSearch Service, Customer Solutions

**Digest:**
Handmade.comは、手作り品マーケットプレイスで、商品詳細の自動化を目指し、AIとベクトル検索を導入。AnthropicのClaude 3.7 Sonnetで初期説明を生成、Amazon OpenSearch Serviceでベクトル検索を実施。RAGでSEO最適化された説明を生成し、多言語対応も視野に。これにより、出品者向けコンテンツ作成を効率化し、顧客体験向上を目指しています。

---

### [How we’re using AI to help track and predict cyclones](https://blog.google/technology/google-deepmind/weather-lab-ai-cyclone-prediction-tracking/)
**Source:** Google DeepMind
**Published:** 2025-08-04 19:00:00 UTC
**Tags:** Research, Google DeepMind, AI

**Digest:**
今シーズン、我々はハリケーンの予測と警報を支援するため、国立ハリケーンセンターと提携します。このパートナーシップにより、より正確なハリケーン情報が提供され、災害への備えが強化されることが期待されます。

---

### [Rethinking how we measure AI intelligence](https://blog.google/technology/ai/kaggle-game-arena/)
**Source:** Google DeepMind
**Published:** 2025-08-04 16:00:00 UTC
**Tags:** Google DeepMind, AI

**Digest:**
Kaggleが、AIモデルが戦略ゲームで直接対決する新プラットフォーム「Kaggle Game Arena」を公開。複雑なゲーム環境で、AI同士が競い合い、その能力を試す場を提供します。これにより、AI技術の進化を促進し、新たな可能性を引き出すことが期待されます。

---

### [What’s new in Copilot Studio: July 2025](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/whats-new-in-copilot-studio-july-2025/)
**Source:** Microsoft 365 Blog
**Published:** 2025-08-04 15:05:00 UTC

**Digest:**
2025年7月のMicrosoft Copilot Studio新機能に関する月例まとめ記事をお届けします。詳細はMicrosoft 365 Blog内の「Copilot Studio新機能：2025年7月」で公開されており、今回のアップデート内容が詳しく解説されています。

---

### [Surface セルフサービスポータルに関する情報まとめ](https://blogs.windows.com/japan/2025/08/04/summary-of-information-about-the-surface-self-service-portal/)
**Source:** Windows Blog for Japan
**Published:** 2025-08-04 07:56:41 UTC
**Tags:** Surface

**Digest:**
法人・教育機関向けSurfaceサポートは、Services Hub経由での提供が8月31日で終了。最新サポートはSurfaceサポートポータルとSurface管理ポータルに移行し、既に利用可能です。移行のため、紹介動画や移行マニュアル一式を参考に、早めの切り替えを検討しましょう。詳細はWindows Blog for Japanで公開されています。

---

### [【OpManager使ってみた】第5回 OpManagerでのイベントログ・サービス監視](https://blog.jbs.co.jp/entry/2025/08/05/110845)
**Source:** JBS Blog
**Published:** 2025-08-05 02:08:45 UTC
**Tags:** Tech, OpManager, 監視, Windows

**Digest:**
OpManagerのイベントログとサービス監視を紹介。第5回では、イベントログ監視でWindowsのログを監視し、サービス監視でサービスの稼働状況を確認します。前回のリソース監視設定完了後、これらの設定手順を解説。設定方法と動作確認を行い、OpManagerでのシステム管理をより効率的にします。

---

### [Teams Phone通話キューの新機能「コールバック」を使ってみる](https://blog.jbs.co.jp/entry/2025/08/05/090812)
**Source:** JBS Blog
**Published:** 2025-08-05 00:08:12 UTC
**Tags:** Teams Phone, Microsoft Teams

**Digest:**
Teams Phoneの通話キューに「コールバック」機能が追加されました。今回はその設定と動作を検証。これにより、通話キューで応答できなかった場合に、相手にコールバックを促すことが可能になります。通話体験の向上に繋がる新機能、ぜひ活用したいですね。

---