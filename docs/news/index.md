# AI Tech Trends Digest (2025-08-12)


## Top Tech Articles from Qiita


### [Claude Code カスタムコマンドで品質チェック！レビュー指摘を激減させてみんなハッピー大作戦](https://qiita.com/tomada/items/5e6d566684b19b34759a)
**Published:** 2025-08-11 23:26:30 UTC
**Likes:** 2
**Tags:** 初心者向け, 生成AI, Claude, AIエージェント, ClaudeCode

**Digest:**
Claude Code のカスタムコマンドを活用した品質チェック自動化を紹介。セキュリティ、パフォーマンス、SEOなどを実装直後にチェックし、レビュー指摘を激減させる。総合レビュー、パフォーマンス、セキュリティ、SEO、テストカバレッジ、UI/UXなど多角的なチェックが可能。問題の早期発見と修正により、実装者の不安を解消し、高品質なコード作成を促進する。

---

### [Hierarchical Reasoning Model (HRM)をRTX 3060 (VRAM 12GB)1つで再現実装する](https://qiita.com/CLRR/items/e061c5bb33c51ada30c6)
**Published:** 2025-08-11 11:01:39 UTC
**Likes:** 2
**Tags:** AI, WSL2, LLM, 推論モデル, HRM

**Digest:**
新しい推論AI、Hierarchical Reasoning Model (HRM)を、VRAM 12GBのGPUで数独Extremeの学習・評価を試みた。結果は論文通りだが、学習に1日7時間38分、推論に1時間25分と時間がかかった。正解率は48.2%で、論文の55%を下回るも範囲内。VRAMの小さいGPUでは高速な学習・推論は難しく、高性能GPUが必須。

---

### [Gemini Storybookで自動でサウンドイラストノベル作成](https://qiita.com/Yh_Taguchi/items/40df48fafb13f394afb8)
**Published:** 2025-08-11 21:49:07 UTC
**Likes:** 1
**Tags:** storybook, Gemini

**Digest:**
生成AIでアニメ制作が実現する未来を提唱。ChatGPTとGemini Storybookを使い、過去に作成したラノベを元に、Gemini Storybookが約3分のサウンドイラストノベルを生成。物語は変更されるものの、設定丸投げで絵本化できる点がポイント。まさに「朝起きて生成AIにアニメ制作を依頼」に近づき、その実現もそう遠くないと感じている。

---

### [Selenaを使ってみる | Claude Codeに長期記憶を持たせる](https://qiita.com/usayamadausako/items/bddd227c6de290ef07f7)
**Published:** 2025-08-11 06:01:30 UTC
**Likes:** 1
**Tags:** Serena, LLM, Claude, ClaudeCode, VibeCoding

**Digest:**
Selenaは、Claude Codeのセッション内容を`.serena/memories/`に.md形式で保存するツールです。これにより、Claude Codeがセッションを忘れる問題を解決し、トークンの無駄遣いを防ぎます。インストールはuvを使用し、`claude mcp add-json`コマンドでMCPに登録。プロジェクトディレクトリで実行すると、`claude`起動時に自動起動します。セッション内容の要約やコード変更記録にも活用可能です。

---

### [ubuntu へのLM Studio Install方法](https://qiita.com/gonnta/items/e33dbf7314159756d5d7)
**Published:** 2025-08-12 05:43:32 UTC
**Likes:** 0
**Tags:** 生成AI, LLM, ローカルLLM

**Digest:**
UbuntuへのLM Studioインストール手順は以下の通りです。まず、公式サイトからLinux版をダウンロードし、`sudo apt update`でパッケージを更新します。次に`libfuse2t64`をインストールし、LM StudioのAppImageファイルを`/opt/LMStudio`に配置します。最後に、デスクトップに起動アイコンを作成すれば、LM Studioを利用できるようになります。

---

## Latest News from RSS Feeds


### [Demystifying Amazon Bedrock Pricing for a Chatbot Assistant](https://aws.amazon.com/blogs/machine-learning/demystifying-amazon-bedrock-pricing-for-a-chatbot-assistant/)
**Source:** AWS ML Blog
**Published:** 2025-08-11 19:33:10 UTC
**Tags:** Amazon Bedrock, Cloud Cost Optimization, Foundational (100), Generative AI, Intermediate (200), Thought Leadership

**Digest:**
Amazon Bedrockの費用を理解するための記事。顧客サービスチャットボットを例に、トークン、埋め込み、モデル選択など、主要コンポーネントに分解してコストを見積もる方法を解説。オンデマンド料金体系で、ClaudeやAmazon Nova、Meta Llamaといった様々なモデルの月額費用を試算。トークン単価を比較し、性能とコストのバランスを考慮した最適なモデル選択を推奨しています。

---

### [Fine-tune OpenAI GPT-OSS models on Amazon SageMaker AI using Hugging Face libraries](https://aws.amazon.com/blogs/machine-learning/fine-tune-openai-gpt-oss-models-on-amazon-sagemaker-ai-using-hugging-face-libraries/)
**Source:** AWS ML Blog
**Published:** 2025-08-11 19:25:19 UTC
**Tags:** Amazon SageMaker, Amazon SageMaker AI, Announcements, Artificial Intelligence, Foundation models

**Digest:**
OpenAIのGPT-OSSモデル（gpt-oss-20b/120b）がAmazon SageMaker AIとBedrockで利用可能に。MoEアーキテクチャで推論性能と低コストを実現し、コード、科学分析、数学的推論に特化。128,000のコンテキスト長、多言語対応、CoTによる推論も可能。SageMaker AIで、Hugging Face TRL/Accelerate、DeepSpeed ZeRO-3などを活用し、多言語推論データセットでファインチューニングできます。

---

### [Azure AI Foundry Agent ServiceのDeep Researchを使ってみた](https://blog.jbs.co.jp/entry/2025/08/12/130459)
**Source:** JBS Blog
**Published:** 2025-08-12 04:04:59 UTC
**Tags:** Azure AI Foundry Agent Service, 大規模言語モデル, Python

**Digest:**
Deep ResearchがAzure AI Foundry Agent Serviceに登場し、Web情報取得と調査結果組み込みが可能に。検証のため、Python環境でポータル設定とソースコード実装を実施。Bing Search利用条件やストリーミング非推奨事項に注意し、azure-ai-agentsライブラリを用いて動作を確認しました。

---

### [Microsoft FabricのEventstreamとEventhouseを使ってみた](https://blog.jbs.co.jp/entry/2025/08/12/102527)
**Source:** JBS Blog
**Published:** 2025-08-12 01:25:27 UTC
**Tags:** Microsoft Fabric

**Digest:**
Microsoft FabricのEventstreamとEventhouseを試用。Eventstreamはリアルタイムデータ処理、Eventhouseはデータ保存に利用。サンプルデータで簡単に試せる。Eventstream作成、ストリーム設定編集、Eventhouseでのデータ確認が可能。Fabricで手軽にリアルタイムデータ分析を始められます。

---

### [Microsoft Purview : 電子情報開示のコマンドレットの接続性の変更](https://shanqiai.lekumo.biz/sharepoint_technical_note/2025/08/microsoft-purvi-b2aa.html)
**Source:** SharePoint Technical Notes
**Published:** 2025-08-11 12:24:41 UTC
**Tags:** Microsoft Purview

**Digest:**
Microsoftは、セキュア フィーチャー イニチアチブ（SFI）の一環として、Windowsのセキュリティ強化に注力しています。具体的には、安全な機能のデフォルト化や、脆弱性リスクの低減を目指し、OSの信頼性向上を図っています。これにより、ユーザーはより安全なWindows環境でPCを利用できるようになります。

---