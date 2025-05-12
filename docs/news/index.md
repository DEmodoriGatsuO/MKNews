# AI Tech Trends Digest (2025-05-12)


## Top Tech Articles from Qiita


### [[Oracle Cloud] Autonomous Database ) SELECT AI（自然言語によるクエリ実行）を活用するコツ 2025年5月分 (2024/05/12)](https://qiita.com/kenwatan/items/57bb9e164a45ad32c9f6)
**Published:** 2025-05-11 23:24:12 UTC
**Likes:** 5
**Tags:** oci, autonomous_database, GenerativeAI

**Digest:**
Oracle Cloud Autonomous DatabaseのSELECT AIで、AIプロファイル作成時の新オプションを試した。特定スキーマの表全体を対象、関連表の自動検出、大/小文字区別の設定、表アクセスの制限が可能。`object_list_mode` を `auto` にすると関連表を自動検出、`case_sensitive_values` で大文字小文字区別、`enforce_object_list` で表アクセス制限を制御できる。

---

### [Amazon Bedrockで使えるモデルの日本語OCR能力を検証しました](https://qiita.com/moritalous/items/32df8f8872fb08fd8995)
**Published:** 2025-05-12 03:16:44 UTC
**Likes:** 4
**Tags:** AWS, OCR, bedrock, Claude, Llama4

**Digest:**
Amazon Bedrockの画像入力対応モデルを検証し、PDFの画像をHTMLで再現する実験を実施。Claude 3.7/3.5 Sonnetが正確に文字を抽出し、Llama 4も健闘。一方、NovaモデルやPixtralは日本語性能が課題に。料金比較も提示し、画像からの文字列抽出にはClaudeが有力という結果でした。

---

### [miiboのカスタムアクションのURLクロールで運行状況取得](https://qiita.com/n0bisuke/items/12f030e3183b01ee9031)
**Published:** 2025-05-11 15:22:13 UTC
**Likes:** 3
**Tags:** JavaScript, OpenAI, ChatGPT, Functioncalling, miibo

**Digest:**
miiboのカスタムアクションにURLクロール機能が追加され、Webページ情報を取得可能に。ヤフー路線情報から電車の運行状況を取得するデモでは、AIがURLを判別し、横浜線の遅延状況をリアルタイムに取得することに成功しました。Webhook設定でカスタムアクションと連携し、Function CallingでURLパラメータを渡しています。

---

### [RAGとLLMを使用した自然言語ログクエリシステムの構築してみました ](https://qiita.com/phandinhloccb/items/3368c44c68999e64f736)
**Published:** 2025-05-12 01:53:40 UTC
**Likes:** 2
**Tags:** AI, SRE, bedrock, LLM

**Digest:**
LLM初心者による自然言語ログクエリシステム構築の記録。**RAG**と**LLM**を活用し、Slackで自然言語検索を実現。**AWS**上で、ログを構造化、ベクトル化し、**OpenSearch**で検索。結果は、高い関連性と意味理解を示し、ハイブリッド検索で精度向上。ベクトル埋め込みの選択的利用、余弦類似度、k値調整が重要。今後は、IaC化、自動アラート、マルチモーダル化などを計画。

---

### [生成AI活用して簡単な(Switchbotの温度を表示する)Webサイトを作った感想](https://qiita.com/t2murata/items/e0dc014e4c2a13f9406c)
**Published:** 2025-05-12 11:18:10 UTC
**Likes:** 1
**Tags:** Webアプリケーション, Swichbot, Claude

**Digest:**
Switchbot温湿度計のデータを可視化するウェブサイトを6時間で構築。**生成AIを活用**し、Switchbot APIから取得したデータをAWSのサーバーレス構成で処理、CloudFrontで公開。ChatGPTで構成を相談、Claude3.7 sonnetでコードを生成し高速なプロトタイピングを実現。要件定義やレビュー、修正には人間の工夫が必要だが、**開発速度は格段に向上**した。

---

## Latest News from RSS Feeds


### [法人向け Surface: Copilot+ PC のポートフォリオを拡充](https://blogs.windows.com/japan/2025/05/12/expanding-the-surface-for-business-copilot-pc-portfolio/)
**Source:** Windows Blog for Japan
**Published:** 2025-05-12 06:46:26 UTC
**Tags:** Surface

**Digest:**
マイクロソフトは、AI対応の法人向け「Surface Pro 12インチ」と「Surface Laptop 13インチ」を発表。Snapdragon X Plusプロセッサ搭載で、高いパフォーマンスと最大23時間のバッテリー駆動を実現。セキュリティを重視し、Windows HelloやMicrosoft Plutonを搭載。Copilot+ PCで、AIを活用した効率的な業務を支援。7月22日発売予定。

---

### [People Skills の一般提供開始と新しい Skills エージェントを発表](https://blogs.windows.com/japan/2025/05/12/announcing-people-skills-general-availability-and-new-skills-agent/)
**Source:** Windows Blog for Japan
**Published:** 2025-05-12 00:52:44 UTC
**Tags:** Copilot, Viva Insights

**Digest:**
マイクロソフトは、**People Skills** の一般提供を開始。これは、Microsoft 365 Copilot や Viva に統合され、従業員のスキルを AI で推論・可視化する新機能です。2025 年 5 月に Copilot と Viva 向け、同年 6 月に Skills エージェントが提供開始予定。リーダーは人材を見つけ、従業員は自己成長に役立てられます。プライバシー保護も重視され、スキル分類やサードパーティ統合も可能。

---

### [AI 導入スコアの一般提供を開始](https://blogs.windows.com/japan/2025/05/12/announcing-general-availability-of-ai-adoption-score/)
**Source:** Windows Blog for Japan
**Published:** 2025-05-12 00:52:36 UTC
**Tags:** Copilot

**Digest:**
マイクロソフトが、Microsoft 365 Copilot の導入状況を評価する「AI 導入スコア」の一般提供を開始。組織内でのCopilot利用状況を評価し、類似組織との比較が可能。週3日以上Copilot利用でスコア100を目指す。機能別利用状況や組織メッセージによる導入促進も可能。AI導入スコアレポートで、効果的な活用を支援します。

---

### [TerraformでAzureリソース構築後にAzure Potal上から変更を加えた場合の動作](https://blog.jbs.co.jp/entry/2025/05/12/140115)
**Source:** JBS Blog
**Published:** 2025-05-12 05:01:15 UTC
**Tags:** Azure, Terraform

**Digest:**
TerraformでAzureリソースを構築後、状態はterraform.tfstateに保存されます。Azure PortalでTerraform管理のリソースを変更すると、Terraform再実行時に変更が上書きされ、Portalでの変更は失われます。Terraform管理のリソース変更は、定義ファイルに反映させ、terraform applyで適用し、クラウド...

---

### [【vSphere Replication】拡張レプリケーション導入時の注意点](https://blog.jbs.co.jp/entry/2025/05/12/102411)
**Source:** JBS Blog
**Published:** 2025-05-12 01:24:11 UTC
**Tags:** VMware, vSphere, vSphere Replication, Disaster Recovery

**Digest:**
vSphere Replicationの拡張レプリケーションに関する記事のダイジェストです。従来のレプリケーションとの比較に加え、導入時に発生しうる問題点について解説しています。仮想マシンの保護、災害対策（BCDR）の実現に向けた、検討ポイントが示唆されている内容です。

---