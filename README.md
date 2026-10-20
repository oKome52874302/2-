# 演習ノート

大学の科目ごとの演習アプリ（GitHub Pages で公開）。

| 科目 | フォルダ | 内容 |
|---|---|---|
| 分子生物学Ⅱ | `molbio2/` | 第1〜4講＋予習範囲・382問（正誤・四択・記述・穴埋め） |

## 構成

- `index.html` … 科目一覧。`SUBJECTS` 配列に1行足すと科目が増える
- `<科目>/index.html` … 各科目の演習アプリ（1ファイル完結）
- 学習記録は各ブラウザの localStorage に保存（科目ごとに別キー）

## 公開設定

Settings → Pages → Source: **Deploy from a branch** / Branch: `main` / `/(root)`
