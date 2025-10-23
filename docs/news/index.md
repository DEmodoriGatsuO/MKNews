# AI Tech Trends Digest (2025-10-23)


## Top Tech Articles from Qiita


### [Mermaid図経由でCopilotから情報流出 - 間接プロンプト注入型攻撃の新たな形](https://qiita.com/___nix___/items/90b157d20c819b2db2fa)
**Published:** 2025-10-22 11:23:07 UTC
**Likes:** 9
**Tags:** Security, AI, copilot, LLM, echoleak

**Digest:**
Microsoft 365 Copilotの脆弱性に関する注意喚起。Copilotは業務データにアクセスでき、悪意ある文書による情報漏洩リスクがある。GBHackersが報告した「Mermaid型」攻撃は、Copilotによる内部データ収集と偽UI生成により、ユーザが誘導されるワンクリック型の情報流出。対策として、自動解析の無効化、コネクタ権限最小化、パッチ適用、ユーザ教育などが重要です。

---

### [Mastra + Next.jsをECSで動かす際のPPTX画像認識](https://qiita.com/Syoitu/items/d8e546f0d70260941212)
**Published:** 2025-10-22 09:09:48 UTC
**Likes:** 3
**Tags:** OCR, ECS, Next.js, Claude, Mastra

**Digest:**
Mastra製のAIエージェントでPPTXの画像と文字を認識させるため、外部サービスを使わず実装。Amazon BedrockのCitations機能は不採用。LibreOfficeでPDF化し、ImageMagickとGhostscriptでPNGに変換、Base64化してMastraに渡す方法を採用。解像度調整でClaude APIの画像サイズ制限に対応。ECS環境では依存ライブラリインストールと`readonlyRootFilesystem`設定が必要。

---

### [Next.js + SQLite で開発できる Claude Code の Plugin を作ってみた](https://qiita.com/megmogmog1965/items/992f1a25f87e5915c295)
**Published:** 2025-10-23 03:12:14 UTC
**Likes:** 1
**Tags:** TypeScript, Next.js, LLM, Claude, ClaudeCode

**Digest:**
[Claude Code] を用いた Next.js + SQLite アプリ開発の効率化事例。プラグインで Subagents, Agent Skills, Hooks などを統合し、なんちゃって手順書を卒業。`/init` で初期設定、`/spec` で実装計画書生成、指示で実装開始。これにより、Next.js と SQLite を使った Web アプリ開発が手順書なしで可能に。プラグインは Slash Commands, Subagents, Agent Skills, Hooks を含み、開発を自動化します。

---

### [ChatGPT Atlas プロンプトインジェクションで遊ぼう](https://qiita.com/numekudi/items/4e9922da7b8324dcad37)
**Published:** 2025-10-22 16:07:14 UTC
**Likes:** 1
**Tags:** OpenAI, ChatGPT

**Digest:**
ChatGPT謹製のAIブラウザ「Atlas」が登場。チャットUIが特徴で、Webサイトを読み取りLLMとツールで楽しくしてくれる。著者は、プロンプトインジェクションの実験を行い、Webサイトの指示で猫化に成功。悪意あるテキストの影響を否定できず、情報源確認の重要性を指摘。スキル診断では過大評価ながら客観評価の可能性も示唆している。

---

### [Jules APIが公開されたのでVSCode拡張機能を作ってみた](https://qiita.com/Opabinium/items/190eff0194cd6cef4b78)
**Published:** 2025-10-22 13:26:52 UTC
**Likes:** 1
**Tags:** AI, VSCode, Gemini, AIエージェント, Jules

**Digest:**
GoogleのAIコーディングエージェント「Jules」のVSCode拡張機能「Jules Extension」を紹介。**GitHub**連携し**非同期**でバグ修正や機能追加を行うJules APIを活用し、VSCodeからセッション管理が可能に。Gemini 2.5 Proベースで無料利用でき、カスタムプロンプトや自動更新機能も搭載。2025年10月にはJules APIが公開され、拡張機能の可能性が広がる。

---

## Latest News from RSS Feeds


### [Quantic Echoes を発表、量子コンピューティングの実用化に向けた大きな一歩](https://blog.google/intl/ja-jp/company-news/technology/quantic-echoes/)
**Source:** Google Japan Blog
**Published:** 2025-10-23 08:16:00 UTC
**Tags:** AI

**Digest:**
本日、量子コンピュータが従来型スーパーコンピュータの13,000倍の速度で、検証可能なアルゴリズムをハードウェア実行することに成功しました。これにより、分子構造計算が可能となり、実用化への大きな一歩を踏み出しました。長年の研究と6年間のブレークスルーを経て実現した画期的な成果です。

---

### [プライバシー サンドボックス技術に関する計画の最新情報](https://blog.google/intl/ja-jp/products/android-chrome-play/update-on-plans-for-privacy-sandbox-technologies/)
**Source:** Google Japan Blog
**Published:** 2025-10-22 12:00:00 UTC
**Tags:** Android, Chrome

**Digest:**
Googleは、ChromeのサードパーティCookie廃止に向け、プライバシーサンドボックス関連APIの方向性を決定するため、エコシステムからのフィードバックを基に検討を重ねています。その結果、今後の重点分野と、APIの変更に関する最新情報を発表しました。ビジネス、開発者、ユーザーにとって最大の価値を提供することを目指しています。

---

### [Build scalable creative solutions for product teams with Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/build-scalable-creative-solutions-for-product-teams-with-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-10-22 23:02:04 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Guardrails, Amazon Bedrock Knowledge Bases, Amazon Machine Learning, Amazon OpenSearch Service, AI/ML

**Digest:**
Amazon Bedrockを活用し、クリエイティブワークフローを加速する方法を紹介。**Amazon Nova**モデルで商品紹介やマーケティングコピーを生成、**Amazon Bedrock**でブランドガイドラインを遵守。**知識ベース**で情報集約し、**Guardrails**で統制。**Amazon S3**へのアセット保存から、**API Gateway**を通じた**Lambda**関数による情報連携まで、一連の流れを解説。

---

### [Build a proactive AI cost management system for Amazon Bedrock – Part 2](https://aws.amazon.com/blogs/machine-learning/build-a-proactive-ai-cost-management-system-for-amazon-bedrock-part-2/)
**Source:** AWS ML Blog
**Published:** 2025-10-22 18:58:16 UTC
**Tags:** Advanced (300), Amazon Bedrock, AWS Step Functions, Cloud Cost Optimization, Generative AI, Technical How-to

**Digest:**
Amazon Bedrockのコスト管理強化として、APIリクエストへのタグ付与による詳細なコスト配分を実現。AWS Step Functionsでリアルタイム制限、CloudWatchでメトリクス分析、Cost Explorerで可視化します。アプリケーションインテリジェンスプロファイルを使用し、コストセンター、環境、アプリケーションごとの費用を可視化し、予算管理を強化します。

---

### [Build a proactive AI cost management system for Amazon Bedrock – Part 1](https://aws.amazon.com/blogs/machine-learning/build-a-proactive-ai-cost-management-system-for-amazon-bedrock-part-1/)
**Source:** AWS ML Blog
**Published:** 2025-10-22 18:58:05 UTC
**Tags:** Advanced (300), Amazon Bedrock, AWS Step Functions, Cloud Cost Optimization, Generative AI, Technical How-to

**Digest:**
Amazon Bedrockのトークン料金管理課題に対応し、AWS Step FunctionsとDynamoDBを活用した**コスト管理ソリューション**を紹介。**先行指標**と**後行指標**を組み合わせ、トークン使用量制限を設定することで、予算超過を防ぎます。**CloudWatch**でトークン使用量を監視し、DynamoDBでモデルごとの予算を設定。テストでは、低コストかつ高いパフォーマンスを示し、**Step Functions Express**の利用で月額3.75ドルで10万リクエストに対応可能です。

---

### [Streamline code migration using Amazon Nova Premier with an agentic workflow](https://aws.amazon.com/blogs/machine-learning/streamline-code-migration-using-amazon-nova-premier-with-an-agentic-workflow/)
**Source:** AWS ML Blog
**Published:** 2025-10-22 18:48:48 UTC
**Tags:** Amazon Bedrock, Amazon Nova, Technical How-to, Generative AI

**Digest:**
Amazon Bedrock Converse APIとAmazon Nova Premierを利用し、レガシーCコードをJava/Springへ移行する手法。専門エージェントを使い、コード分析から変換、検証、統合までを段階的に実施。**自動化で時間とコストを削減、コード品質向上、リスク最小化**を実現。Strandsフレームワークとカスタム処理で、トークン制限を克服。

---

### [Metagenomi generates millions of novel enzymes cost-effectively using AWS Inferentia](https://aws.amazon.com/blogs/machine-learning/metagenomi-generates-millions-of-novel-enzymes-cost-effectively-using-aws-inferentia/)
**Source:** AWS ML Blog
**Published:** 2025-10-22 13:53:20 UTC
**Tags:** AWS Inferentia, AWS Neuron, Customer Solutions, Life Sciences

**Digest:**
Metagenomiは、AIを活用した酵素バリアント生成のコスト削減を目指し、Progen2モデルをAWS Inferentiaで実装。AWS BatchとEC2 Spot Instancesを使用し、最大56%のコスト削減を達成しました。検証の結果、GPUと比較してInf2は高効率で、大規模なタンパク質シーケンス生成に適していることが示されました。

---

### [Microsoft Authenticator アプリを使った3つのサインイン方法](https://blog.jbs.co.jp/entry/2025/10/23/094646)
**Source:** JBS Blog
**Published:** 2025-10-23 00:46:46 UTC
**Tags:** MFA, Microsoft Authenticator, Microsoft, 多要素認証(MFA)

**Digest:**
Microsoft Authenticatorアプリのサインイン方法を解説。プッシュ通知、ワンタイムパスワード（OTP）、パスキーの特徴を説明し、設定方法や動作検証まで解説します。アプリ登録、サインイン設定、各方法での検証手順を網羅。Microsoft Authenticatorを活用し、安全なサインインを実現しましょう。

---