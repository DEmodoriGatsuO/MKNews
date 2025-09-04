# AI Tech Trends Digest (2025-09-04)


## Top Tech Articles from Qiita


### [「npx create-mastra」で作った Mastra のプロジェクト（ツールを使うエージェントの実装）と LM Studio でのローカルLLM（OpenAI互換API を扱うもの）を組み合わせる](https://qiita.com/youtoy/items/09b953f2f1ef91cb6b6e)
**Published:** 2025-09-03 15:19:25 UTC
**Likes:** 2
**Tags:** OpenAI, LMStudio, ローカルLLM, Mastra, vercelaisdk

**Digest:**
MastraでローカルLLMを試す記事。過去記事を組み合わせ、LM Studioでローカルサーバーを準備、OpenAI互換APIを利用。`create-mastra`でプロジェクト作成後、`@ai-sdk/openai-compatible`を導入し、コードを修正。 `weather-agent.ts`でOpenAIの代わりにLM StudioのローカルLLM（jan-v1-4b）を指定。

---

### [【生成AI】プロンプトインジェクションを防ぐ方法【LLM】](https://qiita.com/keiichileograph/items/b6d76fcb5f90883ea9f7)
**Published:** 2025-09-03 09:55:46 UTC
**Likes:** 2
**Tags:** アーキテクチャ, プロンプト, 生成AI, LLM, プロンプトエンジニアリング

**Digest:**
プロンプトインジェクションは、生成AIへの悪意ある命令でシステムを不正動作させる攻撃。プロンプトハッキングとの違い、防御策として、リクエスト回数制限、機密情報非開示、String Format、LLM2台構成が有効。LLMへの良いプロンプトはタスクをシンプルにし、XMLライクな記述が推奨される。

---

### [今更だけど「生成AI」「LLM」「AIエージェント」の違いをまとめてみた](https://qiita.com/keiichileograph/items/31b20116cf85e243a150)
**Published:** 2025-09-04 05:02:04 UTC
**Likes:** 1
**Tags:** DeepLearning, AI, 生成AI, ChatGPT, LLM

**Digest:**
本記事は、LLM、生成AI、AIエージェントの違いを整理。LLMは文章生成に強み、生成AIは画像・音声なども含む広範なAIで、AIエージェントは外部ツールを駆使してタスクを完遂するシステムを指します。OpenAI ChatGPT、Google Imagen、Zoom AI Companionなどが例として挙げられています。

---

### [LLM／AGI／ASIこの違いを理解しよう](https://qiita.com/Andhy/items/a88181a9f975a31a3557)
**Published:** 2025-09-03 13:45:55 UTC
**Likes:** 1
**Tags:** agi, ASI, LLM

**Digest:**
大規模言語モデル(LLM)は予測変換に特化し、文章生成や翻訳に強みを持つ。一方、汎用人工知能(AGI)は自律的に課題を解決する"何でも屋"、人工超知能(ASI)はAGIを凌駕し人間には理解不能なレベルに達する。LLMは道具、AGIは代理人であり、ASIは人間の知能差を無意味にするほどの能力を持つ。その速度とスケールの暴力は、人間を"魚"のような存在に変える可能性がある。

---

### [OpenAI Realtime APIをSIPでつなぐ - Twilio Programmable Voice連携](https://qiita.com/halapolo/items/c71b7783e820c4b4cbff)
**Published:** 2025-09-04 05:16:45 UTC
**Likes:** 0
**Tags:** twilio, sip, voice, OpenAI

**Digest:**
OpenAI Realtime API を SIP で Twilio と連携する際、Programmable Voice の設定手順を解説。前回は Elastic SIP Trunking を紹介したが、Programmable Voice は通話制御や TwiML での柔軟なロジック挿入、アウトバウンド発信の容易さがメリット。TwiML 作成、電話番号との紐付けで設定完了。課金体系の違いを考慮し、用途に合わせて使い分けるのが重要です。

---

## Latest News from RSS Feeds


### [9 月の Pixel Drop：Material 3 Expressive などの機能アップデートをご紹介](https://blog.google/intl/ja-jp/products/devices-services/september-2025-pixel-drop/)
**Source:** Google Japan Blog
**Published:** 2025-09-04 11:05:00 UTC
**Tags:** Pixel

**Digest:**
Google Pixel Watchのマップ表示が改善され、Google Pixel Budsにも新機能が追加されました。Pixelデバイスの使い勝手が向上しており、詳細については続報にご期待ください。

---

### [Authenticate Amazon Q Business data accessors using a trusted token issuer](https://aws.amazon.com/blogs/machine-learning/authenticate-amazon-q-business-data-accessors-using-a-trusted-token-issuer/)
**Source:** AWS ML Blog
**Published:** 2025-09-03 16:44:14 UTC
**Tags:** Amazon Q, Amazon Q Business, AWS IAM Identity Center

**Digest:**
Amazon Q Businessの**データアクセサー**は、2024年GA以降、ISVが自社SaaSで顧客のエンタープライズデータに安全にアクセス可能に。**TTI**認証により、ISVは自社OIDCプロバイダーでユーザー認証を行い、二重認証を回避しつつセキュリティを維持。IT管理者はISVのOAuth情報からTTIを作成、データアクセサーを設定。ISVは顧客のAmazon Qインデックスに安全にアクセス可能になります。

---

### [Unlocking the future of professional services: How Proofpoint uses Amazon Q Business](https://aws.amazon.com/blogs/machine-learning/unlocking-the-future-of-professional-services-how-proofpoint-uses-amazon-q-business/)
**Source:** AWS ML Blog
**Published:** 2025-09-03 16:39:10 UTC
**Tags:** Adoption, Amazon Q Business, Business Productivity, Customer Solutions, Enterprise Strategy, Generative AI, Innovation and Reinvention, Intermediate (200)

**Digest:**
Proofpointは、Amazon Q Businessを導入し、顧客サービスを革新。2024年1月に開始、10月にはサービスチームで本稼働、管理業務で40%の生産性向上を実現。年間18,300時間以上の時間短縮を実現し、顧客データ分析、レポート作成、会議の要約などに活用。30以上のカスタムアプリを開発し、顧客対応の効率化と質の向上を図っています。今後は、データソースの拡大、アクションの活用、自動化ワークフローの強化を計画しています。

---

### [Enhancing LLM accuracy with Coveo Passage Retrieval on Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/enhancing-llm-accuracy-with-coveo-passage-retrieval-on-amazon-bedrock/)
**Source:** AWS ML Blog
**Published:** 2025-09-03 16:32:47 UTC
**Tags:** Amazon Bedrock Agents, Partner solutions, Technical How-to

**Digest:**
CoveoとAWSが共同で、LLMの信頼性向上を目指すPassage Retrieval APIを紹介。企業内データを元に、Amazon Bedrock Agentsが正確な回答を提供。CoveoのAI-Relevance Platformは、ハイブリッドインデックスとMLで関連情報を高速検索。アクショングループとしてAPIを統合し、企業向けRAGシステムを構築。詳細はGitHubを参照。

---

### [Power Automateで事前設定したタイミングに通知メールを送る](https://blog.jbs.co.jp/entry/2025/09/04/145049)
**Source:** JBS Blog
**Published:** 2025-09-04 05:50:49 UTC
**Tags:** Power Automate, Power Platform

**Digest:**
Power Automateで、あらかじめ設定したタイミングで通知メールを送信するには工夫が必要です。本記事では、別途用意した「通知日と参加日程の対応表」を参照することで、通知タイミングを柔軟にコントロールする方法を解説します。

---

### [【Copilot Studio エージェントの拡張】 スキルとBot Framework SDKの概要](https://blog.jbs.co.jp/entry/2025/09/04/130325)
**Source:** JBS Blog
**Published:** 2025-09-04 04:03:25 UTC
**Tags:** Microsoft Copilot Studio, Bot Framework, スキルボット

**Digest:**
MicrosoftのBot Framework SDKを用いたスキルボット作成ガイドです。Copilot Studioでの高度なチャットボット開発を支援するため、具体的な手順を詳細に解説しています。これにより、スキルボット構築の基本から応用までを網羅的に理解できます。

---

### [Palo Alto評価版を使用してみた](https://blog.jbs.co.jp/entry/2025/09/04/102836)
**Source:** JBS Blog
**Published:** 2025-09-04 01:28:36 UTC
**Tags:** Tech, Paloalto, ネットワーク

**Digest:**
Palo Alto Networksの次世代ファイアウォール製品「Palo Alto」は、VMware ESXi/KVM用の仮想アプライアンスも提供。評価版があり、導入前の動作確認、メンバー育成、自主学習に役立ちます。評価版仮想マシンの申請とセットアップ手順を解説する記事があります。

---

### [Azure AI Foundryで各種Azure AIサービス・Azure OpenAIモデルを一元管理する](https://blog.jbs.co.jp/entry/2025/09/03/164846)
**Source:** JBS Blog
**Published:** 2025-09-03 07:48:46 UTC
**Tags:** Azure AI Foundry, Azure OpenAI, 大規模言語モデル, Python, AI

**Digest:**
Azure AI FoundryとAI Hubの違いを解説し、Azure OpenAIやCognitive Serviceを含むリソースのデプロイ手順を紹介します。AI FoundryとAI Hub、それぞれの特徴や利用方法、更には具体的なデプロイプロセスについて、分かりやすく説明します。

---

### [ドメイン未参加端末に対するMicrosoft 365 Apps for enterpriseのOffice展開ツールを用いた展開時の懸念事項と対策（共有フォルダを利用するケース）](https://blog.jbs.co.jp/entry/2025/09/03/155245)
**Source:** JBS Blog
**Published:** 2025-09-03 06:52:45 UTC
**Tags:** M365Apps

**Digest:**
M365AppsのOffice展開で、ドメイン未参加端末がバッチファイルと共有フォルダ経由でインストールする際、ゲストアクセス無効が問題に。解決策として、バッチファイル内に資格情報を記述することで、認証突破しインストール可能に。これにより、ドメイン参加不要で展開を実現できます。

---