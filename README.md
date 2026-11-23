# ひるメシ投票 LP

2〜5人チームのランチ決めアプリ「ひるメシ投票」の紹介ページです。
11:55に自動で締め切り、同票なら「先にその票数に届いたお店」に決まります。

## ファイル

| ファイル | 内容 |
|---|---|
| `index.html` | ランディングページ本体（これ1つで動きます） |
| `.claude/serve.ps1` | 手元でプレビューするための小さなWebサーバー |
| `.claude/launch.json` | Claude Code がプレビューを起動するための設定 |

## 手元で見る

`index.html` をブラウザで開くか、PowerShellで次を実行して http://localhost:8080 を開きます。

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .claude\serve.ps1
```

## つくり方

Claude Design でデザインし、Claude Code で実装しました。
