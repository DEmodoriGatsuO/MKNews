# AI Tech Trends Digest (2025-09-21)


## Top Tech Articles from Qiita


### [私たちは生成AIを使って結局何を伝えたいのか？（re:Inventに行きたいだけなのに）](https://qiita.com/dnp_wada/items/4cb4d4d5943f9d45b6f6)
**Published:** 2025-09-20 06:55:46 UTC
**Likes:** 1
**Tags:** reinvent, Gemini, 生成AI, ChatGPT, NotebookLM

**Digest:**
生成AIで情報を膨らませる行為への疑問提起から、AWS re:Invent参加申請のエグゼクティブサマリー、GPT5の回答、画像生成、音声解説などを通じ、生成AIの活用例を紹介。最終的に、本質を伝えるのは難しく、人間ならではの熱意や想いが重要だと結論。ITコーディネータの経験を踏まえ、経営者へのプレゼンは内容よりプレゼンターの信頼性が重要と説いています。

---

### [WebエンジニアがAttention機構を理解する](https://qiita.com/R-Tone/items/24d8a1e2b805d69a13c1)
**Published:** 2025-09-21 05:36:27 UTC
**Likes:** 0
**Tags:** softmax, Attention, Transformer, LLM, ScaledDotProductAttention

**Digest:**
Attention機構を理解するため、WebエンジニアがSDPAを解説。文字列"Hello World！"を例に、トークン化、埋め込みベクトル化、Q/K/Vへの変換、内積による類似度計算、スケーリングとソフトマックスによる確率化、文脈付与の流れを説明。QKVは学習で生成、マスクも重要。PyTorch実装も紹介。

---

### [LangChainチュートリアル　(2)](https://qiita.com/GAOTENGXIAO/items/b4d82cdc5b5d03ab232d)
**Published:** 2025-09-21 02:54:21 UTC
**Likes:** 0
**Tags:** OpenAI, LangChain, LLM, langchain_core.output_parsers, LangChain実践入門

**Digest:**
LangChainの構造化出力では、JSONやPydanticモデルで出力形式を定義し、`with_structured_output()`やツールとしてLLMにバインドします。Memoryは短期・長期で情報を保持し、対話を文脈に沿わせます。Runnable Interfaceは`.invoke()`等でLLMやコンポーネントを統一的に扱い、LCECやCustom Runnableでチェーン化できます。

---

### [#126　ChatGPT＋Githubで自動コードレビューを実装してみる②](https://qiita.com/nxted_sapporo/items/d12ebf6e6e6efa65ba88)
**Published:** 2025-09-21 02:35:07 UTC
**Likes:** 0
**Tags:** GitHub, gpt

**Digest:**
GitHub ActionsとChatGPTを連携し、プルリクエスト作成・更新時に自動でコードレビューを行う設定を紹介。GitHub SecretsにAPIキーとトークンを登録し、`.github/workflows` にYAMLファイルを配置。Node.js環境でスクリプトを実行し、ChatGPTがレビューコメントを生成。プルリクエストの自動レビューで、開発効率を向上させます。

---

### [#125　ChatGPT＋Githubで自動コードレビューを実装してみる①](https://qiita.com/nxted_sapporo/items/5dd055653462b2837e80)
**Published:** 2025-09-21 02:34:23 UTC
**Likes:** 0
**Tags:** GitHub, gpt

**Digest:**
AWS CodeGuruに続き、ChatGPTとGitHub連携でコードレビュー自動化に挑戦。OpenAI APIとGitHub APIを使用し、Node.js環境でスクリプトを作成。`.env`でAPIキーとGitHubトークンを設定し、`openai`、`@octokit/rest`パッケージをインストール。プルリクエストの変更ファイルをChatGPTでレビューし、コメントを投稿。スクリプト実行結果も確認し、次回はGitHub Actionsとの連携を予定しています。

---