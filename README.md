# tomatobot

Discord向けのサーバー管理Bot。  
荒らし対策、プライベートVC、認証、地震速報、グローバルチャットなど色々入ってます。

---

## 機能

### 荒らし対策 (`/antitroll`, `/trap`)
- スパム・メンション連打・招待リンクの自動検知＆削除、タイムアウト
- 荒らしBotの自動BAN（ユーザーインストール型は実行者を30日タイムアウト）
- 他サーバーで違反歴があるユーザーが入ってきたときにログへ自動通知
- トラップチャンネル：書き込んだら自動処罰（タイムアウト/キック/BAN）される罠チャンネルを設置

### プライベートVC・チケット (`/setprivatevc`, `/ticket`)
- トリガーVCに入ると専用VCが自動作成される
- `/vcinvite`・`/vckick` でメンバーの出入りを管理
- ボタン1つで問い合わせ用の非公開チャンネルを作れるチケットパネル

### 認証・グローバルチャット (`/setverify`, `/setglobalchat`)
- 絵文字リアクションで認証ロールを付与するパネル
- 他サーバーの参加者とリアルタイムで話せるグローバルチャット

### 地震速報・投票 (`/earthquake`, `/poll`)
- P2P地震情報と連携。震度や通知種別（地震情報・津波予報・緊急地震速報）を細かく設定可能
- 最大20択の投票。時間が来たら自動で集計して結果を表示

### メンバー数カウント (`/membercount`)
- ボイスチャンネル名にメンバー数をリアルタイム表示（Bot除外）

### レベル機能 (`/level`, `/setlevel`)
- メッセージを送るとXPが貯まる。ランクカードやランキングの確認もできる

### ロールパネル (`/setrolepanel`, `/removerolepanel`)
- 絵文字を押すとロールが付く／外れるパネルを設置

### パタトクカシー (`/patatokukashii`)
- 2つの文字列を交互に混ぜたり、混ざった文字列を分解したりする遊びコマンド

### 金曜ロードショー (`/kinro`)
- 今週の金曜ロードショーの放送情報を表示。Googleカレンダー登録もできる

### その他ツール
- `/check_warnings` — 違反履歴のあるユーザーを検索
- `/warmuser` — 悪質なBotを管理者に報告
- `/delmes` — メッセージの一括削除
- `/ban` / `/timeout` — ユーザーIDを指定して処分
- `/qrcode` — テキストやURLからQRコード画像を生成
- `/userinfo` / `/serverinfo` — ユーザーやサーバーの詳細表示
- `/top` — チャンネルの一番古いメッセージへジャンプ

---

## コマンド一覧

| コマンド | 説明 | 権限 |
|---|---|---|
| `/help` | 使い方ガイドを表示 | 全員 |
| `/antitroll` | 荒らし対策の設定パネル | 管理者 |
| `/trap create` / `delete` | トラップチャンネルの作成・削除 | 管理者 |
| `/setprivatevc` | プライベートVC自動作成の設定 | 管理者 |
| `/disableprivatevc` | プライベートVC機能を無効化 | 管理者 |
| `/vcinvite` / `/vckick` | プライベートVCへの招待・追い出し | VC所有者 |
| `/ticket setup` | チケットパネルの設置 | 管理者 |
| `/setverify` | 認証パネルの設置 | 管理者 |
| `/setrolepanel` | ロール付与パネルの設置 | 管理者 |
| `/removerolepanel` | ロールパネルの削除 | 管理者 |
| `/setglobalchat` | グローバルチャットの設定 | 管理者 |
| `/join_global` | グローバルチャット参加ロールを取得 | 全員 |
| `/earthquake` | 地震通知の設定 | 管理者 |
| `/poll` | タイマー付き投票の作成 | 全員 |
| `/membercount` | メンバー数VCカウントの設定 | 管理者 |
| `/level action:rank` | 自分のレベル確認 | 全員 |
| `/level action:leaderboard` | ランキング上位10名 | 全員 |
| `/setlevel` | レベル機能のON/OFF | 管理者 |
| `/kinro` | 今週の金曜ロードショー | 全員 |
| `/patatokukashii make` / `decode` | パタトクカシー作成・解読 | 全員 |
| `/check_warnings` | 警告履歴の検索 | 管理者 |
| `/warmuser` | 悪質Botの報告 | 全員 |
| `/delmes` | メッセージ一括削除 | メッセージ管理権限 |
| `/ban` | ユーザーBAN | BAN権限 |
| `/timeout` | タイムアウト | タイムアウト権限 |
| `/qrcode` | QRコード生成 | 全員 |
| `/userinfo` | ユーザー情報 | 全員 |
| `/serverinfo` | サーバー情報 | 全員 |
| `/top` | 最初のメッセージへジャンプ | 全員 |
| `/ping` | 応答速度の確認 | 全員 |

---

## リンク

- **[Botを招待する](https://discord.com/oauth2/authorize?client_id=1455558664042582028&permissions=8&integration_type=0&scope=bot)**
- **[チュートリアル動画 (YouTube)](https://www.youtube.com/@tomato_bothelp)**
