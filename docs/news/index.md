# AI Tech Trends Digest (2025-08-09)


## Top Tech Articles from Qiita


### [意地悪テスト用の入力データ作成で躓いた話](https://qiita.com/steelpipe75/items/2489c86a73ef60f7980e)
**Published:** 2025-08-08 20:34:18 UTC
**Likes:** 2
**Tags:** プロンプト, Marp, LLM

**Digest:**
LLMのプロンプトインジェクション耐性テストのため、人間には見えないがLLMが読めるPDF作成を試みました。透明度調整やMarpのhidden設定は失敗。成功したのは、文字を背景色で覆い隠す方法と、背景と同色で文字を書く方法でした。これはGoogleスライド、PowerPoint、Marpで実現可能で、隠蔽文字を用いてLLMの誤認識を誘う実験が行われました。

---

### [【Node.js】 OpenAI公式の情報をもとに「GPT-5 の API」の従来との違いを少し見てみる（reasoning.effort minimal や verbosity の設定）](https://qiita.com/youtoy/items/edf41b9b733769b60cc0)
**Published:** 2025-08-08 22:50:27 UTC
**Likes:** 1
**Tags:** JavaScript, Node.js, OpenAI, GPT-5, gpt-5-nano

**Digest:**
GPT-5 APIの新機能「reasoning.effort」と「verbosity」を試す記事のダイジェストです。OpenAI公式ドキュメントに基づき、推論速度を最適化する「minimal」、簡潔な回答を得る「low」設定を試しました。モデルはgpt-5とgpt-5-nanoを使用し、前回よりレスポンスが向上。今後のプロンプトや設定の検証、クックブックの活用も検討します。

---

### [OpenAI API GPT-5を試してみた](https://qiita.com/tama_genai/items/87a49160723ff49a5092)
**Published:** 2025-08-08 22:21:12 UTC
**Likes:** 1
**Tags:** Python, OpenAI, 生成AI, GPT-5

**Digest:**
2025年8月、OpenAIからGPT-5がリリース。APIも公開され、Pythonで実行可能に。APIキー取得後、`pip install openai`でパッケージをインストールし、環境変数でAPIキーを設定。サンプルコードでGPT-5を実行し、GPT-4.1との比較や実行時間・コスト検証も実施。Dockerコンテナでの実行方法も解説。

---

### [Jupyter Notebook + RTX5000シリーズで gpt-oss-20b を試す](https://qiita.com/hgodai/items/5fedc8f168e31b4e8247)
**Published:** 2025-08-08 19:38:01 UTC
**Likes:** 1
**Tags:** LLM, RTX5090, LocalLLM, gpt-oss, GPT-OSS-20B

**Digest:**
OpenAIが公開したオープンLLMモデル、gpt-oss-20bは、Apache 2.0ライセンスで商用利用可能。16GB GPUで動作するが、MXFP4量子化対応のRTX5000シリーズ以降が必要。旧世代GPUではメモリ不足で動作せず。苦労の末、RTX5080(16GB)で動作成功。日本語応答は精度低め。ローカル環境での利用に期待。

---

### [【Claude Code】複数のルールを義務化させ効率的に開発を進める方法](https://qiita.com/NUKKOSPECIAL/items/6f63afe68cd46c32536b)
**Published:** 2025-08-08 16:08:59 UTC
**Likes:** 1
**Tags:** AI, Claude, ClaudeCode

**Digest:**
Claude CodeのAIコーディングアシスタントがmd形式の開発ルールを無視する問題に対し、Hooks機能を使った対策を紹介。Laravelプロジェクトを例に、`PreToolUse`イベントでシェルスクリプトを実行し、ファイルパスに応じてコーディング規約などのmdファイル確認を義務化。`jq`インストール後、`.claude/base-rule.sh`を作成し、`/hooks`コマンドで`PostToolUse`に登録。サブエージェントの利用は、無限ループの可能性から推奨しません。

---