# AI Tech Trends Digest (2025-06-20)


## Top Tech Articles from Qiita


### [「Claude Code」導入をめっちゃスムーズにする「ドキュメントの下地」を作るプロンプト](https://qiita.com/WdknWdkn/items/2755301aebff878e0075)
**Published:** 2025-06-19 09:17:47 UTC
**Likes:** 29
**Tags:** プロジェクト管理, ドキュメント, 生成AI, Claude, ClaudeCode

**Digest:**
いえらぶGROUPのエンジニアが、AIによるコード生成・レビューの課題解決のため、Claude Codeの導入ハードルを下げる「初期設定プロンプト」を開発。既存ドキュメント探索、CLAUDE.mdへの追記、不足ドキュメント提案などを自動化し、開発者の「やってみる」を促進。結果、ドキュメント更新数2.7倍、レビュー短縮を実現。プロンプトを「運用装置」と捉え、心理的安全性を高めた。

---

### [GitHub Copilot Agent＋Claude Codeを併用してチーム開発を10倍効率化する方法](https://qiita.com/ShunnnEng/items/135ae1cb2eb5a85dd8f8)
**Published:** 2025-06-19 08:44:06 UTC
**Likes:** 1
**Tags:** copilot, Claude, ClaudeCode

**Digest:**
GitHub Copilot AgentとClaude Codeを組み合わせ、チーム開発を劇的に効率化する方法を紹介。issue駆動のCopilot Agentはバグ修正やテストに、複雑な設計・実装はClaude Codeが担当。設計、実装、品質向上という3段階アプローチで、開発速度62.5%向上、バグ発生率60%削減を実現。役割分担、知識共有、継続的な学習が成功の鍵。

---

### [vibe coding+supabaseで匿名キーからのDBアクセスを無効にした話](https://qiita.com/numekudi/items/f6b2ccdcec198e9be774)
**Published:** 2025-06-20 02:53:56 UTC
**Likes:** 0
**Tags:** Security, Next.js, ReactRouter, Supabase, LLM

**Digest:**
Supabaseの`anon key`からDB操作権限を剥奪し、安全性を優先。クライアントサイドからの直接アクセスを禁止し、Next.jsのServer ComponentsやReact Routerのloader/actionで`service_role key`を用いてサーバーサイドでDB操作を行う構成を採用。これにより、BaaSをより堅牢に活用し、情報漏洩リスクを低減。これはBaaSの否定ではなく、より主体的な活用方法である。

---

### [Geminiでキツネと遊ぶ魔法少女を描いてみた。](https://qiita.com/nori-channel/items/36e381cd6938896c05d5)
**Published:** 2025-06-19 21:55:38 UTC
**Likes:** 0
**Tags:** Gemini

**Digest:**
Geminiで「水のキツネと遊ぶ魔法少女」を描画する実験を実施。プロンプトは「水のキツネと遊ぶ魔法少女を描いてください」で、その結果の画像を公開。可愛らしいイラストが生成された。何かのお役に立てれば、とのこと。

---

### [【賢いMCP-Slackボット開発連載-1】AIが会話をすぐ忘れる問題。「Model Context Protocol」で賢いボットの土台を築く](https://qiita.com/QueryPie/items/4955baf9d2dcbbf9775d)
**Published:** 2025-06-19 16:16:53 UTC
**Likes:** 0
**Tags:** Python, Slack, MCP, LLM, ModelContextProtocol

**Digest:**
Slackボットが「忘れっぽい」問題を解決するため、**Model Context Protocol (MCP)**という設計思想を導入します。これは、LLMのステートレス性を補うもので、ボットの「記憶」と「思考」を設計します。MCPは、**システムプロンプト、短期記憶、長期記憶、動的コンテキスト**の4要素から成り、**Pythonで実装**することで、賢いSlackボット開発の土台を築きます。

---

## Latest News from RSS Feeds


### [Build a scalable AI video generator using Amazon SageMaker AI and CogVideoX](https://aws.amazon.com/blogs/machine-learning/build-a-scalable-ai-video-generator-using-amazon-sagemaker-ai-and-cogvideox/)
**Source:** AWS ML Blog
**Published:** 2025-06-19 19:47:41 UTC
**Tags:** Amazon SageMaker, Amazon SageMaker AI, Artificial Intelligence, Generative AI, Intermediate (200)

**Digest:**
AI/ML技術の進化による動画生成能力に着目し、AWS上でCogVideoXモデルを活用した動画生成ソリューションを紹介。Amazon S3、Fargate、SageMaker、Amazon Bedrockを連携し、テキストや画像から高品質な動画を生成。企業のマーケティングや教育分野での活用を想定。使いやすいStreamlit UIで操作し、動画制作の効率化と革新を促進します。

---

### [Building trust in AI: The AWS approach to the EU AI Act](https://aws.amazon.com/blogs/machine-learning/building-trust-in-ai-the-aws-approach-to-the-eu-ai-act/)
**Source:** AWS ML Blog
**Published:** 2025-06-19 19:41:11 UTC
**Tags:** Artificial Intelligence, Responsible AI

**Digest:**
EU AI Actへの対応が加速。調査では、欧州企業の68%が法規制理解に苦労し、40%がコンプライアンス費用に充当。AWSは、安全なAIソリューション提供のため、ISO/IEC 42001認証取得済。EU AI Actは2024年8月施行、2025年2月から禁止事項が適用。AWSは透明性確保、教育、ガバナンス支援を通じて、顧客のコンプライアンスを支援。

---

### [Update on the AWS DeepRacer Student Portal](https://aws.amazon.com/blogs/machine-learning/update-on-the-aws-deepracer-student-portal/)
**Source:** AWS ML Blog
**Published:** 2025-06-19 19:29:01 UTC
**Tags:** Announcements, Artificial Intelligence, AWS DeepRacer

**Digest:**
AWS DeepRacer Student Portalは2025年9月15日に終了。7月14日からは新規登録が停止され、既存ユーザーは9月まで利用可能。今後はAWS Solutions LibraryでDeepRacerが利用できるようになる。AI/ML教育の一環として、5月28日にジェネレーティブAIに焦点を当てた「AWS AI & ML Scholars」プログラムが再開。学習継続には、awsaimlscholars.comやAWS Skill Builderを活用。

---

### [Accelerate foundation model training and inference with Amazon SageMaker HyperPod and Amazon SageMaker Studio](https://aws.amazon.com/blogs/machine-learning/accelerate-foundation-model-training-and-inference-with-amazon-sagemaker-hyperpod-and-amazon-sagemaker-studio/)
**Source:** AWS ML Blog
**Published:** 2025-06-19 19:26:44 UTC
**Tags:** Amazon SageMaker, Amazon SageMaker AI, Amazon SageMaker HyperPod, Amazon SageMaker Studio, Artificial Intelligence, Intermediate (200)

**Digest:**
大規模な生成AIモデルの学習には、SageMaker HyperPodとFSx for Lustreを活用し、耐障害性と高いスループットを実現します。SageMaker HyperPodは、障害発生時に自動修復し、学習の中断を最小限に抑えます。FSx for Lustreは、SageMaker StudioとHyperPod間の高速なデータ共有を可能にし、開発効率を向上。CloudFormationによる環境構築や、SLURMまたはAmazon EKSをオーケストレーターとして選択できます。

---

### [Surface Copilot+ PC で Windows 11 への移行を後押し](https://blogs.windows.com/japan/2025/06/20/accelerate-your-move-to-windows-11-with-surface-copilot-pcs/)
**Source:** Windows Blog for Japan
**Published:** 2025-06-20 01:13:37 UTC
**Tags:** Surface, Surface Copilot+ PC

**Digest:**
2025年10月でWindows 10のサポートが終了。セキュリティと生産性向上のため、Windows 11への移行が重要です。Microsoft Surface Copilot+ PCは、Windows 11 Proとの連携により、セキュリティインシデントを削減し、導入も容易に。パフォーマンスも向上し、多様な働き方に対応、AI機能を活用できます。

---

### [手を動かして考える: Surface ペンのデジタル手描き入力](https://blogs.windows.com/japan/2025/06/20/hinking-by-hand-digital-inking-with-surface-pen/)
**Source:** Windows Blog for Japan
**Published:** 2025-06-20 01:11:49 UTC
**Tags:** Surface, Surface ペン

**Digest:**
Surfaceペンのデジタル手書き入力は、アイデア創出、コラボレーション、イノベーションを促進。Surface MVPが、OneNoteやWhiteboardでのスケッチ、会議でのメモ活用、PowerPointへの注釈など、様々な場面での生産性向上を紹介。脳の活性化、スムーズなチームワーク、繊細な表現力も実現し、場所を選ばず創造性を高めるツールとして有効です。

---

### [Copilot+ PC で NPU を活用して生成 AI タスクを実行する](https://blogs.windows.com/japan/2025/06/20/leveraging-the-power-of-npu-to-run-gen-ai-tasks-on-copilot-pcs/)
**Source:** Windows Blog for Japan
**Published:** 2025-06-20 01:10:18 UTC
**Tags:** Surface, Copilot+ PC, NPU

**Digest:**
Microsoftは、Copilot+ PCでNPUを活用し、SLMを効率的に実行する方法を解説。Qualcomm AI Hubを利用し、Snapdragon X Plus搭載Surface Laptop 13インチでPhi-3.5モデルをローカル実行する事例を紹介。QNN SDK、Hugging Faceのトークナイザー、構成ファイルの準備、テストプロンプト実行の手順を説明し、エッジAIの実現可能性を示す。

---

### [【Microsoft×生成AI連載】【最新情報】Copilot Studioエージェントビルダーのナレッジにチャットとサイトが対応しより便利に](https://blog.jbs.co.jp/entry/2025/06/20/085940)
**Source:** JBS Blog
**Published:** 2025-06-19 23:59:40 UTC
**Tags:** Copilot, Microsoft Copilot, Microsoft 365 Copilot, 生成AI, Microsoft×生成AI連載

**Digest:**
Microsoft Copilot Studioが進化！Teamsチャット、メール、SharePointサイトを知識源としてAIエージェントに統合可能になりました。最新機能により、AIエージェントはさらに便利に。記事では、Copilot Studioエージェントビルダーを使った具体的な作成手順も解説されています。

---

### [SharePoint Framework Extensions: フィールドカスタマイザーの廃止について](https://shanqiai.lekumo.biz/sharepoint_technical_note/2025/06/sharepoint-fram-7c2d.html)
**Source:** SharePoint Technical Notes
**Published:** 2025-06-19 15:19:32 UTC
**Tags:** Microsoft 365 - SharePoint, SharePoint Framework

**Digest:**
SharePoint Framework (SPFx) Extensions を活用したフィールドカスタマイズについて解説。フィールドカスタムizer を使用することで、SharePoint リストやライブラリの表示方法を柔軟に変更できます。これにより、データの表示や操作を向上させ、ユーザーエクスペリエンスを最適化することが可能です。

---