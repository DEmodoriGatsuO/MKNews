# AI Tech Trends Digest (2025-09-20)


## Top Tech Articles from Qiita


### [Awesome Claude Code まとめ | コミュニティが作った便利ツール・ワークフロー・設定集を徹底紹介](https://qiita.com/tomada/items/363018389e9cd68e5ffb)
**Published:** 2025-09-19 15:10:48 UTC
**Likes:** 4
**Tags:** 個人開発, Claude, AIエージェント, ClaudeCode, SuperClaude

**Digest:**
Claude Codeの効率的な活用法として、海外コミュニティのツール群を紹介。ワークフロー、IDE統合、使用量監視など多岐にわたり、GitHubリポジトリに多数公開。特に、タスク管理、コード改善エンジン、料金監視ツールが人気。EmacsやNeovimとの連携、TDD、ステータスライン表示、フック機能も。詳細なツール一覧と、活用例を提示。

---

### [【保存版】ChatGPTでMCPを作成する](https://qiita.com/relu/items/d518bbad2b828e1e6649)
**Published:** 2025-09-19 14:33:11 UTC
**Likes:** 1
**Tags:** AI, MCP, 生成AI, ChatGPT, LLM

**Digest:**
MCPは、LLMアプリと外部ツール/データ間の標準プロトコルで、JSON-RPC 2.0を使用。OpenAIのAgents SDKでHosted MCP (Responses API委任)、Streamable HTTP、stdioの3形態をサポート。セキュリティ重要で、OAuth 2.1、Origin検証、ローカルバインド等が推奨。CloudflareはSSEとStreamable HTTPの両対応例を提示。まずはstdioで最小サーバー、次にHosted MCP、将来的にはStreamable HTTPへの移行が効果的。

---

### [OpenAI Responses APIでExcelファイルを読み込み・解析する方法](https://qiita.com/Bakio202076/items/783fd3f603f7387837a1)
**Published:** 2025-09-19 12:04:10 UTC
**Likes:** 1
**Tags:** PHP, API, OpenAI, ChatGPT, CodeInterpreter

**Digest:**
OpenAIのResponses APIで、フォーマット不定のExcelファイルを扱う方法を紹介。 **Code Interpreter** とファイルアップロード機能を活用し、ExcelファイルをAPIにアップロード後、IDを指定して解析する。  PHPのコード例も記載。 アップロードファイル容量制限や、ファイルの有効期限、削除についても言及。  **file-search** ではExcelに対応していない。

---

### [llama.cpp + OpenCLでAdreno GPUを活用したLLM推論をする](https://qiita.com/chibibaku/items/7892af02c722504dcf4f)
**Published:** 2025-09-19 11:36:07 UTC
**Likes:** 1
**Tags:** OpenCL, qualcomm, snapdragon, LLM, llama.cpp

**Digest:**
Qualcomm Snapdragon搭載Android端末で、OpenCLバックエンドを利用したllama.cppを実行する手順を紹介。Android NDKのインストールから、OpenCLヘッダーとICDローダーの導入、llama.cppのビルド、モデルの転送と実行までを解説。Snapdragon 8 Gen 2搭載POCO F6 Proで試した結果、CPU推論より遅かった。

---

### [Codex CIモードをGithub Actionsで試してみた！](https://qiita.com/s0ukada025/items/aeee255e7f75f071ce3a)
**Published:** 2025-09-19 07:04:27 UTC
**Likes:** 1
**Tags:** CI, AI, OpenAI, codex

**Digest:**
CodexのCIモードをGithub Actionsで試した結果です。OpenAI CodexをNode.js環境でセットアップし、APIキーを設定して「こんにちは！」と出力するワークフローを実装。`.codex`ディレクトリ未作成時のエラーにも注意が必要です。`codex exec`コマンドでCIモードを実行し、挨拶が出力されることを確認。手動実行も可能です。

---

## Latest News from RSS Feeds


### [Android のマイナンバーカード：現在できること、これからできるようになること](https://blog.google/intl/ja-jp/products/android-chrome-play/mynumbercard-on-android/)
**Source:** Google Japan Blog
**Published:** 2025-09-19 12:00:00 UTC
**Tags:** Android

**Digest:**
マイナンバーカードのスマホ用電子証明書サービスに加え、来年秋頃には身分証明書として利用可能なAndroid版マイナンバーカードの提供が開始予定です。これにより、より手軽にマイナンバーカードを利用できるようになり、利便性が向上することが期待されます。

---

### [Move your AI agents from proof of concept to production with Amazon Bedrock AgentCore](https://aws.amazon.com/blogs/machine-learning/move-your-ai-agents-from-proof-of-concept-to-production-with-amazon-bedrock-agentcore/)
**Source:** AWS ML Blog
**Published:** 2025-09-19 16:09:26 UTC
**Tags:** Amazon Bedrock, Best Practices, Technical How-to

**Digest:**
Amazon Bedrock AgentCore は、AIエージェントを本番環境で運用するための包括的なサービスです。PoCから本番移行の課題、具体例として顧客サポートエージェントを取り上げ、会話の継続性やパーソナライズを実現する永続的なメモリ機能を紹介。AgentCore Memoryを活用し、顧客の好みや過去の情報を記憶させ、より良い顧客体験を提供します。

---

### [AI Builderのプロンプトを利用する](https://blog.jbs.co.jp/entry/2025/09/19/150649)
**Source:** JBS Blog
**Published:** 2025-09-19 06:06:49 UTC
**Tags:** AI Builder, PowerPlatfirm, 初心者向け

**Digest:**
AI Builderのプロンプト機能は、Power Platform内で生成AIをノーコードで利用可能にする機能です。Power Apps、Power Automate、Copilot Studioで利用でき、特定のタスクを実行するAIモデルを簡単に構築できます。プロンプトの作成から実行、フローへの組み込みまでを解説しています。

---

### [SharePoint の新機能 Knowledge Agent (ナレッジ エージェント) の登場!](https://shanqiai.lekumo.biz/sharepoint_technical_note/2025/09/sharepoint-076d.html)
**Source:** SharePoint Technical Notes
**Published:** 2025-09-19 16:39:38 UTC
**Tags:** Microsoft 365 - SharePoint, Microsoft 365 Copilot

**Digest:**
Microsoft 365 Copilot（有償版）の組織内活用は、利用規約の確認と、Microsoft Purviewコンプライアンス設定が重要です。データ保護、アクセス制御、プライバシー対策を講じ、情報漏洩リスクを最小限に抑えつつ、Copilotの生産性向上効果を最大化する必要があります。

---