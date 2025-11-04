# AI Tech Trends Digest (2025-11-04)


## Top Tech Articles from Qiita


### [小型LLM同士を"橋渡し"して性能向上！Gated Cross-Attention Bridgeの実装と効果](https://qiita.com/katsuki_ono/items/bb41b1e01b8750381c8f)
**Published:** 2025-11-03 17:09:25 UTC
**Likes:** 2
**Tags:** Python, 機械学習, PyTorch, Transformer, LLM

**Digest:**
**Qwen2.5-3B**と**Gemma-2-2B**を繋ぐ**Gated Cross-Attention Bridge**を発表。学習不要で、Gemmaの知識をQwenが参照し、より正確な出力を実現。4層にゲートを配置し、ベイズの定理説明タスクで改善を確認。SDPA対応でA100での高速動作も可能。

---

### [LLMの力を100%引き出す「プロンプトノウハウ」勉強会資料](https://qiita.com/suetaketakaya/items/b90ca9ea5b618dda9a64)
**Published:** 2025-11-03 14:59:41 UTC
**Likes:** 2
**Tags:** gherkin, AI, ChatGPT, LLM, プロンプトエンジニアリング

**Digest:**
AI社内勉強会のダイジェスト。LLMは**条件付き確率**に基づき、膨大なテキストデータから単語間の関係性を学習します。Transformerモデルと**Attention**機構により高性能化。得意なのは、学習済みの知識を組み合わせる「**内挿**」で、プロンプトでは明確な指示、役割設定、文脈提供が重要です。基本原則を踏まえ、構造化やFew-shotなどの技術を駆使して能力を引き出します。

---

### [【AIエージェントの新常識】MCP（Model Context Protocol）サーバーとは？仕組みと活用法を徹底解説](https://qiita.com/okokok/items/cbe416a82249e3de6d85)
**Published:** 2025-11-03 08:19:49 UTC
**Likes:** 1
**Tags:** プロトコル, AI, MCP, LLM, MCPサーバー

**Digest:**
大規模言語モデル（LLM）と外部の連携を可能にする「AIのUSBポート」ことMCPサーバー。Anthropic提唱のMCP規格に基づき、AIがツール、リソース、プロンプトを通じて外部と通信します。PCのUSB-Cポートのように、AIと様々なデータやツールを繋ぎ、リアルタイム情報取得や外部システム操作を実現。クライアント/サーバー構造で動作し、AIエージェントの可能性を広げ、AIの活用を高度化します。

---

### [AI開発ツールの「気づきの壁」 - 非エンジニアの95%が知らない選択肢](https://qiita.com/tomota53/items/8f7ce67d78cf35989832)
**Published:** 2025-11-03 22:52:22 UTC
**Likes:** 0
**Tags:** ポエム, キャリア, ChatGPT, Claude, AI活用

**Digest:**
エンジニアが1週間で4つの教育アプリを開発。ClineとClaude APIを使った経験から、AI開発ツールの情報格差を指摘。非エンジニアは「AIでアプリ制作」を知らない現状に警鐘を鳴らし、情報不足、専門用語の壁、無関心が原因と分析。情報格差を埋めるため、発信、翻訳、正直な情報伝達を呼びかけ、人への情報伝達が重要と訴えています。

---

### [Codex CLIの/reviewコマンドを使ってコードレビューを効率化する方法](https://qiita.com/tomada/items/6c11d5c4750ba2724fdf)
**Published:** 2025-11-03 15:34:49 UTC
**Likes:** 0
**Tags:** OpenAI, codex, ChatGPT, AIエージェント, CodexCLI

**Digest:**
Codexの`/review`コマンドは、AIがコードをチェックし、問題点指摘に役立ちます。4つのプリセットがあり、ブランチ差分（PR Style）、未コミット変更、過去コミット、カスタム指示に対応。ローカル開発段階やコミット前、AI生成コードの確認、プロジェクト固有ルールにも対応可能です。内部ではバグ報告基準やコメント作成ルールが定義され、効率的なコードレビューを実現します。

---

## Latest News from RSS Feeds


### [How Switchboard, MD automates real-time call transcription in clinical contact centers with Amazon Nova Sonic](https://aws.amazon.com/blogs/machine-learning/how-switchboard-md-automates-real-time-call-transcription-in-clinical-contact-centers-with-amazon-nova-sonic/)
**Source:** AWS ML Blog
**Published:** 2025-11-03 17:25:22 UTC
**Tags:** Amazon Bedrock, Amazon Nova, AWS Lambda, Kinesis Video Streams

**Digest:**
Switchboard, MDは、医療現場でのAI活用を目指し、リアルタイム音声認識に課題を抱えていた。Amazon Nova Sonicを採用し、高い精度と低コストを実現。Amazon ConnectとKinesis Video Streamsを活用したサーバーレスアーキテクチャにより、75%の待ち時間削減と59%の放棄率削減を達成。正確な文字起こしで、電子カルテ連携や業務効率化を促進し、患者とのコミュニケーションに注力できる環境を構築した。

---

### [ファイルサーバーのデータをCopilotで活用する方法](https://blog.jbs.co.jp/entry/2025/11/04/085652)
**Source:** JBS Blog
**Published:** 2025-11-03 23:56:52 UTC
**Tags:** Microsoft 365 Copilot Chat, Copilot, ファイルサーバー, ファイル共有Microsoft 365 Copilot コネクタ

**Digest:**
Microsoft 365 Copilotで、オンプレミスファイルサーバーのデータ活用が可能に。ファイルサーバー内のドキュメントやマニュアルを自然言語で検索、要約し、業務効率化を実現します。前提条件、構成、導入手順を解説しており、情報活用を加速させるための具体的な方法を紹介しています。

---