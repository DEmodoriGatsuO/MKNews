# AI Tech Trends Digest (2025-05-12)


## Top Tech Articles from Qiita


### [[Oracle Cloud] Autonomous Database ) SELECT AI（自然言語によるクエリ実行）を活用するコツ 2025年5月分 (2024/05/12)](https://qiita.com/kenwatan/items/57bb9e164a45ad32c9f6)
**Published:** 2025-05-11 23:24:12 UTC
**Likes:** 5
**Tags:** oci, autonomous_database, GenerativeAI

**Digest:**
Oracle CloudのAutonomous Databaseにおける自然言語クエリ実行(SELECT AI)のAIプロファイル作成で、特定のスキーマの表全体、関連表の自動検出、大/小文字区別、表アクセス制限といった新オプションを試した結果を報告。`object_list_mode`の"auto"設定で関連表を自動検出、`case_sensitive_values`で大文字小文字の区別を制御、`enforce_object_list`で表アクセスを制限できる。

---

### [Amazon Bedrockで使えるモデルの日本語OCR能力を検証しました](https://qiita.com/moritalous/items/32df8f8872fb08fd8995)
**Published:** 2025-05-12 03:16:44 UTC
**Likes:** 3
**Tags:** AWS, OCR, bedrock, Claude, Llama4

**Digest:**
Amazon Bedrockの画像入力対応モデルで、総務省のPDFページ画像をHTML再現する検証を実施。**Claude 3.7 Sonnet**と**3.5 Sonnet**が優れた精度を示し、Llama 4も検討価値あり。**Nova**モデルは不適、**Pixtral**は誤読あり。**Claude**系はHTML再現、Llamaは一部情報欠落。料金も比較し、画像からの文字抽出にClaudeが有力という結果。

---

### [miiboのカスタムアクションのURLクロールで運行状況取得](https://qiita.com/n0bisuke/items/12f030e3183b01ee9031)
**Published:** 2025-05-11 15:22:13 UTC
**Likes:** 3
**Tags:** JavaScript, OpenAI, ChatGPT, Functioncalling, miibo

**Digest:**
miiboのカスタムアクションにURLクロール機能が追加されました。ヤフー路線情報から電車の運行状況を取得する例として、カスタムアクションとWebhookを設定。AIがURLを判断し、横浜線の運転見合わせ情報を取得に成功しました。テンプレコードでは、`input.url`にWebページのURLが渡され、`@{url}`でFunction Callingのパラメータを代入する仕組みです。

---

### [RAGとLLMを使用した自然言語ログクエリシステムの構築してみました ](https://qiita.com/phandinhloccb/items/3368c44c68999e64f736)
**Published:** 2025-05-12 01:53:40 UTC
**Likes:** 1
**Tags:** AI, SRE, bedrock, LLM

**Digest:**
RAGとLLMを用いた自然言語ログクエリシステムを構築。Slackインターフェースから自然言語でログ検索可能にし、AWSサービスとAI技術を活用。ベクトル検索により高い関連性でログを取得し、解決策も提案。主要コンポーネントはデータ処理パイプライン、クエリ処理フロー、技術にはRAG、LangChainなど。ハイブリッド検索や類似性メトリック選択が重要。

---

### [Webアプリ開発で生成AIを使い分け！VSCode + Copilot Chat + Roo Code + Google AI Studio 活用術](https://qiita.com/uk714/items/deb604c1e78eb24d885d)
**Published:** 2025-05-12 00:02:11 UTC
**Likes:** 1
**Tags:** VSCode, Gemini, 生成AI, Claude

**Digest:**
Webアプリ個人開発で、AWS/Azure/GitHub試験対策アプリを生成AI活用し効率化。VSCodeではCopilot Chat、Roo Code(Gemini 2.5 Flash)で大規模コード分析。Google AI Studio(Gemini 2.5 Pro)で高品質な演習問題作成。**Gemini 2.5 Flash** の圧倒的コンテキスト長が強力、**Pro** は精度の高い作問に貢献。生成AIの特性を活かしたツール使い分けで開発効率を向上。

---