# imasugu Chronicle

imasugu 開発日報アーカイブ。2026-03-01 から継続。

## 目的

- 何をやったか / なぜ逸れたかを後から辿れるようにする
- commit log だけでは分からない文脈を残す

## ディレクトリ構成

```
daily/
  index.md          ← 月別リンク一覧
  2026/
    03/
      index.md      ← 3月の日別リンク
      01.md
      02.md
      ...
    04/
      index.md
      ...
    05/
      index.md
      ...
```

## 閲覧方法

### GitHub Web / GitHub Mobile
- このリポジトリをブラウザで開く
- `daily/index.md` → 月 → 日と辿る
- GitHub Mobile アプリでも Markdown がそのまま表示される

### Obsidian (PC / スマホ)
1. このリポジトリを `git clone` する
2. Obsidian で「フォルダを Vault として開く」→ `imasugu-chronicle` を選択
3. `daily/index.md` を起点に内部リンクで移動できる

### スマホブラウザ
- GitHub Mobile アプリ推奨（Markdown レンダリングあり）
- または GitHub Web をブラウザで開く

## 記録フォーマット

各日ファイルは以下のセクションで構成:

- 最初にやろうとしてたこと
- 実際にやったこと
- 横道に逸れたこと / なぜ逸れたか
- 反省 / 学んだこと / 備忘
- commit / deploy
