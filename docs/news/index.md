# AI Tech Trends Digest (2025-09-25)


## Top Tech Articles from Qiita


### [GPT-5-Codex の API利用について OpenAI公式情報を見つつ Node.js で試してみた](https://qiita.com/youtoy/items/f0310267f0a9b62634e3)
**Published:** 2025-09-24 16:07:44 UTC
**Likes:** 2
**Tags:** JavaScript, Node.js, OpenAI, gpt-5-codex

**Digest:**
GPT-5-CodexのAPI利用について、公式情報を参照しNode.jsで試した記事です。APIはResponses APIを使用し、モデル名はgpt-5-codex、対応入力形式はテキスト・画像、料金はGPT-5と同等。Node.jsでの実装例として、openaiパッケージを用いてp5.jsのコード生成を試行。実行結果とダッシュボードログから、gpt-5-codexが正常に利用されていることを確認しました。

---

### [拡散モデルに学んで、反復的洗練フレームワーク「思考の拡散（DoT）」を考えてみた](https://qiita.com/fujinami/items/c4cdbeab7e88f319a2db)
**Published:** 2025-09-24 07:56:44 UTC
**Likes:** 2
**Tags:** Gemini, 推論, 拡散モデル, LLM, プロンプトエンジニアリング

**Digest:**
AIの推論を改善する新手法「Diffusion of Thoughts (DoT)」を提案。ノイズ除去プロセスを応用し、思考を反復的に修正・洗練します。初期の誤りを修正し、自己修正能力を向上。CoTの課題を克服し、ToTとも相補的な関係。課題はトークン消費量増加、推論時間、冗長性。実用的なプロンプト開発やToT/CoTとの連携で更なる発展を目指します。

---

### [プロンプトの意図を正しく伝えるには？](https://qiita.com/s0ukada025/items/675984ce673847864b56)
**Published:** 2025-09-25 05:17:33 UTC
**Likes:** 1
**Tags:** AI, プロンプト, 生成AI, Claude

**Digest:**
Claudeへの質問に対し、どのような仕様書のフォーマットを求めているのかを具体的に示す必要性が示唆されました。質問の意図を明確にするため、フォーマット指定やサンプル提示を意識した質問修正が重要であると結論づけられています。その結果、仕様書のサンプルが出力されています。

---

### [生成AIに質問するプロンプトを作ってくれるジェネレーターのセットアップめも](https://qiita.com/shinichi_yoshioka2/items/9f6ca2753db63699435a)
**Published:** 2025-09-25 02:14:27 UTC
**Likes:** 1
**Tags:** Python, AWS, Claude

**Digest:**
AWSが公開した生成AIプロンプト作成ツールを試す手順をメモ。AWS CLI、Pythonをインストールし、GitHubからソースコードをダウンロード・解凍後、必要なモジュールをpipでインストール。OpenAI APIキーを.envに設定し、起動。タスクと変数を入力し、プロンプトを生成します。

---

### [マルチモーダルAIの鍵「テンソル」とは？](https://qiita.com/s-age/items/b80e0020bdbcfb41d33c)
**Published:** 2025-09-24 23:32:16 UTC
**Likes:** 1
**Tags:** AI, マルチモーダル, LLM

**Digest:**
マルチモーダルAIは、画像や音声など複数データを**テンソル**という多次元配列で統一的に扱い、コンピュータ処理を可能にする技術です。データタイプごとに最適な階のテンソルを用い、テキストはベクトル、画像は3階、音声は時間と周波数を持つテンソルで表現します。異なるテンソルは**テンソル空間**で共通のベクトル（1階のテンソル）に変換され、データの関連付けを実現。マルチモーダルLLMなど応用も広がっています。

---

## Latest News from RSS Feeds


### [Copilot Chat が Microsoft 365 アプリに登場](https://blogs.windows.com/japan/2025/09/25/copilot-chat-comes-to-the-microsoft-365-apps/)
**Source:** Windows Blog for Japan
**Published:** 2025-09-25 02:07:10 UTC
**Tags:** Copilot, Copilot Chat, Microsoft 365

**Digest:**
Microsoft 365 Copilot Chatとエージェントが、Word、Excel、PowerPoint、Outlook、OneNoteで利用可能に。追加料金なしでCopilot Chatが利用でき、ファイル検索や画像共有が容易に。Microsoft 365 Copilotライセンスがあれば、**業務データ**に基づいた推論や**AI****搭載の検索支援**、**ノートブック**、**作成**などの高度な機能が利用可能。GPT-5などの最新テクノロジーへの**優先アクセス**も。IT管理者はCopilot Control Systemで管理。

---

### [生成AI活用のためのプロンプト設計：これだけは押さえたい5つの基本ポイント](https://blog.jbs.co.jp/entry/2025/09/25/144054)
**Source:** JBS Blog
**Published:** 2025-09-25 05:40:54 UTC
**Tags:** 生成AI, プロンプト

**Digest:**
生成AIで良い結果を得るには、プロンプト（指示文）の書き方が重要です。ChatGPTやCopilot初心者向けに、効果的なプロンプト設計の5つの基本ポイントを解説。プロンプトを対話の設計図と捉え、Role、Instruction、Context、Outputの基本構造を意識することで、より精度の高い回答を引き出せます。

---

### [Teams Phone自動応答へ複数の休日動作を設定する](https://blog.jbs.co.jp/entry/2025/09/25/115408)
**Source:** JBS Blog
**Published:** 2025-09-25 02:54:08 UTC
**Tags:** Teams Phone

**Digest:**
Teams Phoneの自動応答機能は、営業時間と営業時間外でそれぞれ異なる着信動作を設定できます。一方、祝日・休日については、特定の日にちごとに複数の着信動作を柔軟に設定することが可能です。

---

### [【Microsoft 365】Multi-Tenant Organization（MTO）機能の概要](https://blog.jbs.co.jp/entry/2025/09/25/110400)
**Source:** JBS Blog
**Published:** 2025-09-25 02:04:00 UTC
**Tags:** Microsoft 365, Microsoft

**Digest:**
Microsoft 365のMulti-Tenant Organization（MTO）は、大規模企業向けに、複数の組織を一元管理できる機能です。運用効率を高め、セキュリティを強化し、組織間の連携をスムーズにするソリューションとして注目されています。

---

### [タイタニックの乗客生存予測モデルをFabricで作成してみた。（その３）](https://blog.jbs.co.jp/entry/2025/09/24/164111)
**Source:** JBS Blog
**Published:** 2025-09-24 07:41:11 UTC
**Tags:** Microsoft Fabric, Python

**Digest:**
前回に続き、クレンジング済データで機械学習モデルをFabricで作成し、精度評価を行います。前回の記事の続編として、今回は訓練データとテストデータに分割し、評価用データを用いて性能検証モデルを構築。作成したモデルの精度を評価し、機械学習モデルの作成準備、モデル作成、性能検証の手順をまとめます。

---