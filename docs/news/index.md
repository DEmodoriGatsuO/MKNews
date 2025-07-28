# AI Tech Trends Digest (2025-07-28)


## Top Tech Articles from Qiita


### [「この画像の、この部分」を"テキスト"で Gemini に伝える会話型セグメンテーション](https://qiita.com/te_yama/items/668013e599a96b5cd944)
**Published:** 2025-07-27 23:53:56 UTC
**Likes:** 3
**Tags:** Python, Gemini, GoogleCloud, 生成AI, LLM

**Digest:**
Gemini 2.5のセマンティックセグメンテーション機能を試す記事。画像内の電卓やペンを自然言語で指示し、JSON形式でマスクを取得。さらに、電卓の液晶やUSBの金属部分など、より詳細な領域も指定可能で、正確な抽出を確認。画像解析の柔軟性を感じ、今後の活用に期待を示しています。

---

### [SnowflakeのデータにApache IcebergとADBを使って自然言語(NL2SQL)で問い合わせてみた](https://qiita.com/ssfujita/items/cb037b47fa0114d6128c)
**Published:** 2025-07-27 23:31:21 UTC
**Likes:** 3
**Tags:** oci, Snowflake, iceberg, autonomous_database, LLM

**Digest:**
ADBとSnowflake間のデータ連携を、Apache IcebergとADBのSELECT AIで実現。Snowflake上のIcebergデータをS3に配置し、ADBから外部テーブルとして参照。ADBのSELECT AIで自然言語クエリを実行し、Iceberg形式のデータにアクセスすることに成功しました。これにより、多様なDWHからのデータ参照が可能になり、データ活用の幅が広がります。

---

### [Claude Code 内で専門家を作成！新機能 Sub agents で用途専門AIを作って品質改善してみた](https://qiita.com/tomada/items/a6fba5876dbc9304ca5a)
**Published:** 2025-07-27 21:16:06 UTC
**Likes:** 3
**Tags:** 個人開発, 生成AI, Claude, AIエージェント, ClaudeCode

**Digest:**
AnthropicのClaude Codeに搭載された**Sub agents**機能は、Claude内に専門家を作成するものです。コードレビューやUI/UX改善に役立ち、各Sub agentは独自のコンテキスト、カスタムプロンプト、ツールを持ちます。Learning Nextで試した結果、Apple風デザインに特化したSub agentを作成し、UI改善に成功しました。`MUST BE USED`で自動呼び出しも可能。プロジェクト固有のドキュメント参照で、より専門的なサポートが実現します。

---

### [🎤→🤖→✍️ 音声入力からAI執筆、人間校正まで ── 新時代の記事執筆ワークフローを実践してみた](https://qiita.com/torifukukaiou/items/f0be16e3ee5dc5599877)
**Published:** 2025-07-27 23:30:23 UTC
**Likes:** 2
**Tags:** ポエム, 猪木, 闘魂, ChatGPT, Claude

**Digest:**
Qiita Tech Festa 2025体験記を書くため、音声入力で思考整理、Claudeで構造化、人間校正というAI記事執筆ワークフローを実践。ChatGPT音声モードでインタビュー形式で思考をまとめ、Claudeで記事構造化・文章化。最終校正で固有名詞やニュアンスを調整。発信力こそ重要と結論。

---

### [ローカルLLMで無課金バイブコーディングできる環境を整えてみた【Qwen2.5-Coder】](https://qiita.com/TacoLover/items/9eb9fb0cdf19f3916594)
**Published:** 2025-07-27 07:00:47 UTC
**Likes:** 2
**Tags:** LLM, #Qwen2.5-Coder, #Cotinue, #無課金バイブコーディング

**Digest:**
Qwen2.5-Coderをローカルで無課金利用し、バイブコーディング環境を構築する手順を紹介。Ollamaを導入し、RTX 3090搭載PCでQwen2.5-Coder:32bを実行。Windows PCでOllamaを稼働させ、ネットワーク経由でMacからもアクセス可能に。VScodeのContinue拡張機能で統合し、別PCからも利用可能に。ただし、Continue経由だとGPU使用率が上がらない問題がある。

---

## Latest News from RSS Feeds


### [【Outlook】グループアドレスをグローバルアドレス帳から非表示にする](https://blog.jbs.co.jp/entry/2025/07/28/133852)
**Source:** JBS Blog
**Published:** 2025-07-28 04:38:52 UTC
**Tags:** Outlook, Exchange Online

**Digest:**
Outlookのグローバルアドレス帳からグループアドレスを非表示にする設定方法を解説します。具体的には、Microsoft 365グループ、配布リスト、動的配布リスト、メールが有効なセキュリティグループなどの非表示設定について言及。設定反映には時間がかかる場合があるため、その目安も説明します。

---

### [【Power Apps】タイマーコントロールを使用して自動的にアプリを終了する](https://blog.jbs.co.jp/entry/2025/07/28/120045)
**Source:** JBS Blog
**Published:** 2025-07-28 03:00:45 UTC
**Tags:** Power Apps, Power Platform, 初心者向け

**Digest:**
Power Apps の「タイマー」コントロールは、時間ベースのアクションを実現する強力な機能です。画面更新や別画面への移動、定期的なアクション実行などが可能で、アプリ自動終了も実現できます。 コントロール追加や主要プロパティ設定を経て、アプリの終了処理を実装できます。

---

### [Azure Red Hat Enterprise Linux 仮想マシンにおけるVNC導入](https://blog.jbs.co.jp/entry/2025/07/28/102603)
**Source:** JBS Blog
**Published:** 2025-07-28 01:26:03 UTC
**Tags:** Azure, Linux, RHEL

**Digest:**
AzureのRHEL VMでGUIを利用する方法を紹介します。まず、VNC Serverをインストールし、設定変更を行います。次に、セキュリティグループでVNCポートを開放し、VNCクライアントソフトで接続します。これにより、Azure上のRHEL VMでGUI操作が可能になります。

---