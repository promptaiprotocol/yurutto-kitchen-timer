# ゆるっとキッチンタイマー 🍳

ベージュ〜パステルカラーの、ブラウザで使える無料キッチンタイマーです。
外部API・広告・会員登録はありません。

## 主な機能

- 🍜 3分 / 🍲 5分 / 🍝 8分のプリセット
- −1分 / ＋1分 / ＋5分 / ＋10分で調整
- 終了後も `+00:23` のように経過時間を表示
- 🥚 ゆで卵：お湯から / 水から
- 水からモード：火をつける → 沸騰した！ の2段階
- ♨️ 温泉卵モード
- やさしいベル / しっかりアラーム / 音なし
- 対応ブラウザではタイマー中に画面スリープを抑制
- PWA対応・一度読み込めばオフラインでも利用可能

## GitHub Pagesで公開

1. GitHubで新しいPublicリポジトリを作成（例：`yurutto-kitchen-timer`）
2. このフォルダ内のファイルをリポジトリ直下にアップロード
3. `Settings` → `Pages`
4. `Build and deployment` の `Source` を `Deploy from a branch`
5. Branchを `main`、フォルダを `/(root)` にして `Save`
6. Pages画面の `Visit site` から公開ページを確認

同じGitHubアカウントが `promptaiprotocol` の場合、URLは通常：

`https://promptaiprotocol.github.io/yurutto-kitchen-timer/`

## 補足

ブラウザの省電力・バックグラウンド制限により、画面を完全に閉じた状態では終了音が遅れる場合があります。キッチンで使うときはページを開いたままの利用がおすすめです。
