# AI Tech Trends Digest (2025-09-27)


## Top Tech Articles from Qiita


### [Awesome Gemini Roboticsを紹介：Gemini Robotics-ER 1.5のユースケース＆プロンプト集](https://qiita.com/7mpy/items/6200677472d65cefe54c)
**Published:** 2025-09-26 15:59:40 UTC
**Likes:** 6
**Tags:** AI, robotics, Gemini, 生成AI, LLM

**Digest:**
Googleの**Gemini Robotics-ER 1.5**向けオープンソースギャラリー「Awesome Gemini Robotics」は、実践的なユースケースとコピペ可能なプロンプト集。**空間理解**、**長期タスク計画**、**ツール呼び出し**に長けたER 1.5を、最小コード（Python）で試せます。**MITライセンス**で、PRも歓迎。2025年9月25日に**Gemini API**でプレビュー公開。

---

### [AIに110個のSQLテストを作らせたら地獄を見た話 〜Claudeとの問答で見えた真実〜](https://qiita.com/yo2158/items/e3782ead62c353b3f1a1)
**Published:** 2025-09-27 04:37:17 UTC
**Likes:** 1
**Tags:** 失敗談, 生成AI, Claude, ClaudeCode, GeminiCLI

**Digest:**
AI(ClaudeCode)に110のSQLテストケース作成を依頼も、40個目から品質崩壊。原因はコンテキスト圧縮による「疲労」で、憲法やロックシステムも無効。10個分割も失敗。AIの「できます」は30%品質、200ccコップに10L入れるようなものと認識。GeminiCLIでは成功も、モデルごとの相性がある。

---

### [LLMへのプロンプト例。SQLクエリ編](https://qiita.com/ken1math/items/e4cef540ab950163437e)
**Published:** 2025-09-26 21:03:15 UTC
**Likes:** 1
**Tags:** SQL, プロンプト, LLM

**Digest:**
LLMにSQLクエリ作成を依頼したプロンプト例を公開。ストアドプロシージャ、テーブル値関数、スカラー値関数など、様々なSQLコード生成に成功。プロンプト次第で実用的なコードが得られ、修正も容易。一方で、LLM利用により「自分で書く力」の低下も懸念されるため、コード理解の重要性を強調しています。

---

### [OpenAI、ChatGPT Pulseを発表。朝刊を自動作成](https://qiita.com/brookszd129/items/f88e27dc0995b4b3dcd6)
**Published:** 2025-09-26 16:02:17 UTC
**Likes:** 1
**Tags:** OpenAI, Gemini, ChatGPT

**Digest:**
OpenAIが、ChatGPTの新たな能動的機能「ChatGPT Pulse」を発表。Proサブスクリプションユーザー向けに、毎日の予定やニュースなどパーソナライズされた更新情報を提供する。AIが過去のチャット履歴や接続アプリからデータを収集し、朝刊のように情報を提示。将来的には全ユーザーへの展開を目指す。プライバシーや計算能力の課題はあるものの、自律性の向上も視野に入れている。

---

### [続・「AIがルールを無視する」の正体](https://qiita.com/s-age/items/8c931ae8abfffb400e1b)
**Published:** 2025-09-27 05:00:20 UTC
**Likes:** 0
**Tags:** AI, マルチエージェントシステム, LLM

**Digest:**
FizzBuzz実験の失敗原因はLLMのSpecificity Bias、つまり具体的な条件優先にあり、ルール順序で結果が変化。ルール上書きプロトコルを追加も、Geminiコマンド認識やサブエージェント起動問題が発生。API制限対策の逐次実行や単一セッション実行の失敗も。AIは推論エンジンであり、コンテキスト最小化によるFew-Shot Learning効果で精度向上。

---

## Latest News from RSS Feeds


### [Gemini Robotics 1.5 を発表、AI エージェントを物理世界に](https://blog.google/intl/ja-jp/company-news/technology/gemini-robotics-15-ai/)
**Source:** Google Japan Blog
**Published:** 2025-09-26 09:55:00 UTC
**Tags:** AI

**Digest:**
Googleは、現実世界での応用を目指し、Geminiのマルチモーダルな理解力を発展させています。本日、高度な思考力で自律的にタスクをこなし、エージェント体験を提供する2つの新モデルを発表しました。これにより、インテリジェントで汎用的なロボットの実現へ大きく近づいています。

---

### [Building health care agents using Amazon Bedrock AgentCore](https://aws.amazon.com/blogs/machine-learning/building-health-care-agents-using-amazon-bedrock-agentcore/)
**Source:** AWS ML Blog
**Published:** 2025-09-26 16:03:41 UTC
**Tags:** Advanced (300), Amazon Bedrock, Artificial Intelligence, AWS HealthLake, Technical How-to, AI/ML, Generative AI

**Digest:**
Amazon Bedrock AgentCoreを活用し、医療におけるAIエージェントの革新を紹介。 Innovaccerは、Amazon Bedrock AgentCore Gatewayを用いて、既存のAPIをHMCPツールに変換し、セキュリティとコンプライアンスを確保。患者の予防接種予約を自動化するなど、AIエージェントの導入で、医療機関の負担軽減と患者体験向上を目指します。

---

### [Build multi-agent site reliability engineering assistants with Amazon Bedrock AgentCore](https://aws.amazon.com/blogs/machine-learning/build-multi-agent-site-reliability-engineering-assistants-with-amazon-bedrock-agentcore/)
**Source:** AWS ML Blog
**Published:** 2025-09-26 15:58:34 UTC
**Tags:** Amazon Bedrock, Amazon Bedrock Agents, Amazon Bedrock Knowledge Bases, Amazon Machine Learning, Artificial Intelligence, Generative AI, Technical How-to

**Digest:**
SREチームは、Amazon Bedrock AgentCoreとLangGraph、MCPを活用した多エージェントAIアシスタントを構築。Kubernetes、ログ、メトリクス、ランブックを連携し、自然言語での問い合わせに対応。インシデント対応を効率化し、原因特定や対策を支援。Amazon Bedrock AgentCore GatewayとMemory、Runtime、Observabilityなどの機能も活用し、本番環境へのデプロイを容易にしている。

---

### [Microsoft 365 Copilot の新機能 | 2025 年 8 月](https://blogs.windows.com/japan/2025/09/26/whats-new-in-microsoft-365-copilot-august-2025/)
**Source:** Windows Blog for Japan
**Published:** 2025-09-26 07:16:55 UTC
**Tags:** Copilot, What's new in Copilot

**Digest:**
2025年8月のMicrosoft 365 Copilot最新情報では、管理センターでCopilot Search利用状況の指標確認や、リスクの高いAI利用の特定が可能に。ユーザー向けには、SharePointエージェントへのCopilotアプリからのアクセス簡素化、Copilot ChatのGPT-5対応、画像推論・編集機能追加、Edge for Businessでの要約、Teamsでのカスタム辞書対応などが発表されました。

---

### [VSCodeとGitHub Copilotで始めるテストデータ・ファイルの自動生成](https://blog.jbs.co.jp/entry/2025/09/26/151049)
**Source:** JBS Blog
**Published:** 2025-09-26 06:10:49 UTC
**Tags:** VS Code, Copilot, GitHub, GitHub Copilot

**Digest:**
ソフトウェア開発の品質確保にはテストが不可欠。特に、テストデータ準備に多くの時間と手間がかかっている。巨大ファイル（199MBや200MB）、10万文字以上のテキストファイル、2000ページ以上のPDFファイルなど、手作業での作成は大変。閾値テストや、長文テキスト、大量ドキュメント処理性能の検証で必要となる、こうした面倒なテストデータ作成が課題。

---