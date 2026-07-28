# PK合戦 Firebase通信試作 α v011

## 実装済み
- Firebase Authenticationの匿名ログイン
- Realtime Databaseへの6桁部屋作成
- QRまたは6桁番号による別端末からの参加
- ホスト・ゲスト双方で接続成功をリアルタイム表示
- 退出・切断時の部屋情報整理

## まだ未実装
- 試合中の上下・A入力同期
- ゴール／セーブ結果の同期
- 再接続、再戦

## Firebase側で必要な追加設定
Authentication → Settings → 承認済みドメインに `pixypickles.github.io` を追加してください。

Realtime Databaseがテストモードの場合、期限後に通信できなくなるため、動作確認後は匿名認証ユーザーだけに絞るルールへ変更してください。
