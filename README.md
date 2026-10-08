# misc-tools

小さなWebツールをまとめて管理するリポジトリです。

## ツール一覧

- [Memo Rescue — 消えないメモ帳](./memo-rescue/) — ブラウザ内に自動保存する複数メモ対応のメモ帳

## GitHub Pages 公開設定

このリポジトリの Settings → Pages → Build and deployment で、
**Deploy from a branch / main / (root)** を選び **Save** してください。

公開後のURL:
- ツール一覧: https://projectdesk-lab.github.io/misc-tools/
- Memo Rescue: https://projectdesk-lab.github.io/misc-tools/memo-rescue/

## メモデータについて

- 公開するのはHTML/JavaScript本体のみ。メモ本文をGitHubに保存・公開しません。
- メモ内容はブラウザの localStorage に保存され、端末・ブラウザをまたいだ自動同期はありません。
- 別PC/別ブラウザへの移行は「全メモをJSONで書き出す」→「JSONを読み込む」を使用してください。
- ブラウザの保存データを消すとメモが消えることがあるため、重要なメモは定期的にJSONでバックアップしてください。
