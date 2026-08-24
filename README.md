# PK合戦 Firebase通信試作 α v018

## 修正内容
- ホストの一時的な切断で部屋全体を削除しないよう修正
- onDisconnect では hostOnline=false のみ保存
- タブ復帰・フォーカス復帰時に hostOnline=true へ戻す
- 明示的な退出時のみ部屋削除の方針
- Firebase診断表示を追加
  - 認証状態
  - UID
  - 部屋番号
  - ホスト/ゲスト役割
  - 部屋作成/入室/相手入室検知
