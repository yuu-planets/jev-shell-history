# StudioYebisu Jev系リポジトリ 30本 フォーク一覧

**元ツイート**: [@studio_yebisu status 2101065176069886152](https://x.com/studio_yebisu/status/2101065176069886152)
**取得日**: 2026-09-26
**フォーク先アカウント**: [yuu-planets](https://github.com/yuu-planets?tab=repositories&type=fork)
**総数**: 30/30 成功

> Metaが出してるCV(SAM3.1)もAPIで使えるようになり、JevもOpenRouterで使えるようになった時期のキュレーション。
> CV × Jev の組み合わせで何か作るヒント集として。

---

## 【ブラウザ・PC・スマホ操作】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 1 | [yuu-planets/jev-ultrafast](https://github.com/yuu-planets/jev-ultrafast) ← [browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast) | 4,891 | **圧倒的大人気**！JevといえばUse系。ブラウザ操作と対象要素の選択をJevが担当し、テキスト入力時のみ小型LLMを呼び出す構成 |
| 2 | [yuu-planets/typesafe-computer-use](https://github.com/yuu-planets/typesafe-computer-use) ← [awlevin/typesafe-computer-use](https://github.com/awlevin/typesafe-computer-use) | 203 | macOS画面のOCRやアクセシビリティ情報を読み取り、クリックや文字入力を自動化するMac専用ツール |
| 3 | [yuu-planets/mobile-jev](https://github.com/yuu-planets/mobile-jev) ← [droidrun/mobile-jev](https://github.com/droidrun/mobile-jev) | 103 | Mobilerun接続のAndroid端末を操作。CLIやWeb画面、実行ログを確認しながら操作を進められる |
| 4 | [yuu-planets/jev-voice-browser](https://github.com/yuu-planets/jev-voice-browser) ← [moritzkremb/jev-voice-browser](https://github.com/moritzkremb/jev-voice-browser) | 40 | **☆Yebisu注目**☆ ブラウザの音声認識から意図を抽出し、Playwright経由でWebページを操作する実験的実装 |

---

## 【AI開発・コードレビュー】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 5 | [yuu-planets/fast-jev-compaction](https://github.com/yuu-planets/fast-jev-compaction) ← [tamaratran/fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) | 2,790 | Claude Codeの履歴から、不要と判断したツール呼び出しや結果を削除・短縮。残す会話文は原文のまま |
| 6 | [yuu-planets/foreman](https://github.com/yuu-planets/foreman) ← [thruwire/foreman](https://github.com/thruwire/foreman) | 279 | Codexの自律作業をJevが監督し、作業の継続や検証、停止を判断する開発プロセスの実験(Codex版) |
| 7 | [yuu-planets/jev-review](https://github.com/yuu-planets/jev-review) ← [devagrawal09/jev-review](https://github.com/devagrawal09/jev-review) | 251 | Gitの差分やリポジトリ全体を段階的にレビューし、潜在リスクやテスト不足をローカル画面に表示 |
| 8 | [yuu-planets/jev-router](https://github.com/yuu-planets/jev-router) ← [gargpratyush/jev-router](https://github.com/gargpratyush/jev-router) | 121 | Claude CodeやCodexの各ターンで、要求タスクの性質に合わせて呼び出すモデルを自動で振り分ける |
| 9 | [yuu-planets/jev-rules](https://github.com/yuu-planets/jev-rules) ← [EliaAlberti/jev-rules](https://github.com/EliaAlberti/jev-rules) | 3 (新顔) | 依頼内容や編集対象ファイルに応じて、Claude Codeへ渡す指示ルールや参照資料を選ぶ |

---

## 【MCP・スキル・CLI】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 10 | [yuu-planets/skillbox](https://github.com/yuu-planets/skillbox) ← [kitze/skillbox](https://github.com/kitze/skillbox) | 153 | エージェント用スキルを管理・MCP配信する基盤。追加のJev連携で、タスクに合うスキルを推薦する。**ハーネスの一部として使えるのが面白い** |
| 11 | [yuu-planets/system-one-connector](https://github.com/yuu-planets/system-one-connector) ← [itsmostafa/typesafe-mcp](https://github.com/itsmostafa/typesafe-mcp) (元名: typesafe-mcp → system-one-connector に改名) | 62 | ClaudeやCodexなどのMCP対応環境から、Jevの選択・採点・真偽判定を直接呼べる非公式ツール |
| 12 | [yuu-planets/jev-shell-history](https://github.com/yuu-planets/jev-shell-history) ← [mrnugget/jev-shell-history](https://github.com/mrnugget/jev-shell-history) | 30 | zshで入力中の内容に合う過去のコマンドをJevが選び、履歴から補完する |

---

## 【検索・データベース】

> Yebisu注: Jevの評価機能でソートをハックする発想。ユーザー行動にリアルタイムで合わせて選択をフィルタリング → Webと相性が良さそう。

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 13 | [yuu-planets/pg-jev](https://github.com/yuu-planets/pg-jev) ← [realZachi/pg-jev](https://github.com/realZachi/pg-jev) | 143 | PostgreSQLの行を、SQL内の自然言語条件で絞り込み・分類・順位付け。対象データは外部APIへ送信 |
| 14 | [yuu-planets/jev-search](https://github.com/yuu-planets/jev-search) ← [superagents-lab/jev-search](https://github.com/superagents-lab/jev-search) | 48 | 検索語の選定や対象期間の指定、取得したWeb検索結果の関連度ソートをJevに任せる検索パイプライン |
| 15 | [yuu-planets/neo4jev](https://github.com/yuu-planets/neo4jev) ← [jexp/neo4jev](https://github.com/jexp/neo4jev) | 17 | Neo4jのグラフ構造において、次にたどる関係をJevに選ばせ、データのつながりを探索・可視化するデモ |

---

## 【動画・Web閲覧】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 16 | [yuu-planets/unclutter](https://github.com/yuu-planets/unclutter) ← [kitze/unclutter](https://github.com/kitze/unclutter) | 73 | Webページ内の広告枠や邪魔なポップアップをJevで識別し、画面から非表示化するブラウザ拡張 |
| 17 | [yuu-planets/jevmeter](https://github.com/yuu-planets/jevmeter) ← [ChetasLua/jevmeter](https://github.com/ChetasLua/jevmeter) | 52 | 動画内の発言を指定した観点で採点し、メーター付きの動画を作る。事実確認や嘘の判定ではない |
| 18 | [yuu-planets/youtube-sponsor-detection](https://github.com/yuu-planets/youtube-sponsor-detection) ← [trungdq88/youtube-sponsor-detection](https://github.com/trungdq88/youtube-sponsor-detection) | 46 | YouTubeの字幕や音声から動画内のスポンサー紹介区間を判定して自動スキップ |

---

## 【ガードレール・コミュニティ管理】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 19 | [yuu-planets/pi-warden](https://github.com/yuu-planets/pi-warden) ← [DevMortimer/pi-warden](https://github.com/DevMortimer/pi-warden) | 61 | Piエージェントを監視し、プロジェクトのルール違反、同じ失敗の繰り返し、未検証の完了報告をチェック |
| 20 | [yuu-planets/Jev-Moderation-Bot](https://github.com/yuu-planets/Jev-Moderation-Bot) ← [brainstormity/Jev-Moderation-Bot](https://github.com/brainstormity/Jev-Moderation-Bot) | 25 | Discordのスパムや詐欺URLを判定し、メッセージ削除や警告、タイムアウトを管理。誤判定への管理者対応は必要 |

---

## 【マーケティング】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 21 | [yuu-planets/notra](https://github.com/yuu-planets/notra) ← [usenotra/notra](https://github.com/usenotra/notra) | 171 | **☆Yebisu注目GEO☆** AI回答でのブランド言及を追跡するGEOツール。言及の好意度や掲載順位などの分類処理にJevを活用。事前A/Bテスト的に使うのが良さそう |

---

## 【スマートホーム】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 22 | [yuu-planets/HA-Jev](https://github.com/yuu-planets/HA-Jev) ← [AboveColin/HA-Jev](https://github.com/AboveColin/HA-Jev) | 6 (新顔) | Home Assistantの家の状態をJevで判定。洗濯物通知など日常の自動化向けで、安全設備には使わない |

---

## 【ゲーム・ロボットのシミュレーション】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 23 | [yuu-planets/typesafe-mario](https://github.com/yuu-planets/typesafe-mario) ← [fhshaik/typesafe-mario](https://github.com/fhshaik/typesafe-mario) | 260 | エミュレーターから抽出したゲーム状態データをもとに、Jevにマリオの行動を選択させる制御実験 |
| 24 | [yuu-planets/jevpilot](https://github.com/yuu-planets/jevpilot) ← [standardagents/jevpilot](https://github.com/standardagents/jevpilot) | 58 | Three.js製の走行シミュレーター上で、提示された進路と速度の候補からJevが行動を選択する実験 |
| 25 | [yuu-planets/jev-drone](https://github.com/yuu-planets/jev-drone) ← [RomanSlack/jev-drone](https://github.com/RomanSlack/jev-drone) | 58 | 物理エンジンMuJoCo上のドローンシミュレーションで、障害物の回避行動の判断をJevに委ねる実験 |

---

## 【売買ボットの実験】

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 26 | [yuu-planets/jev-trader](https://github.com/yuu-planets/jev-trader) ← [jarrodwatts/jev-trader](https://github.com/jarrodwatts/jev-trader) | 804 | Monad上のKuruで売買判断を試す実験。既定は模擬判断のmock、鍵なしは模擬取引のdry-run。**収益性は未検証** |

---

## 【ローカル・オープンモデル研究(公式Jevとは別)】

> 以下4件は独立した研究・実装。公式Jevの公開版ではない。

| # | フォーク | ★ | 解説 |
|---|---------|---|------|
| 27 | [yuu-planets/SemIf-OpenJev](https://github.com/yuu-planets/SemIf-OpenJev) ← [TheoLeeCJ/SemIf](https://github.com/TheoLeeCJ/SemIf) (元名: SemIf → SemIf-OpenJev に改名) | 1,500 | 公開モデルで選択肢の確率を直接読み出す独立研究(旧OpenJev)。ブラウザ上で動くデモも提供 |
| 28 | [yuu-planets/jevlike](https://github.com/yuu-planets/jevlike) ← [vinnylarouge/jevlike](https://github.com/vinnylarouge/jevlike) | 851 | 可変長の選択肢群を一度に評価する小型モデル学習の独立研究。公式Jevの複製ではなく研究の出発点 |
| 29 | [yuu-planets/NanoJev](https://github.com/yuu-planets/NanoJev) ← [TianyuCodings/NanoJev](https://github.com/TianyuCodings/NanoJev) | 313 | Qwen3-0.6Bベースの並列判断モデル。重みや学習コードを公開し、ゲーム制御デモなどを同梱した独立実装 |
| 30 | [yuu-planets/openjev-sglang](https://github.com/yuu-planets/openjev-sglang) ← [ekzhang/openjev-sglang](https://github.com/ekzhang/openjev-sglang) | 127 | QwenとSGLangによる互換APIの独立実装。B200などGPUサーバーでの稼働を想定した構成 |

---

## 補足メモ

- ★数は StudioYebisu リサーチ時点のもの
- 各フォークの GitHub description には `[Yebisu#N ★数] 解説…` を設定済み(GitHub上でも一覧で見返せる)
- 2件だけ元リポの名前が変わっていた:
  - typesafe-mcp → **system-one-connector** に改名 (#11)
  - SemIf → **SemIf-OpenJev** に改名 (#27)
- フォーク一覧: https://github.com/yuu-planets?tab=repositories&type=fork
