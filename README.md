# ホロライブお宝マウンテンのRTA用タイマー
[ダウンロード](https://github.com/lotus0509ch/hololiveTreasureMountain_RTAstopwatch/archive/refs/heads/main.zip)

これでいいのか不安...（単純にリポジトリの[Download Zip]のリンク張ってるだけ）

## 必要ソフト
- [LiveSplit](https://livesplit.org/downloads/)
- [RunLeash](https://autosplithelper-firebase.web.app/docs/02install/)

## 3timesDouble_ShuffleDeck
### ランダムデッキで3回ダブルのRTAする用のセットです
- RunLeashによるタイマーの挙動
  1. デッキシャッフル画面でタイマーリセット＆停止
  2. デッキ選択画面（シャッフル後自動で遷移する画面）でタイマースタート
  3. 最大お宝の演出で記録
  4. 合計6回の記録でカウントストップ
- 推奨ゲームウィンドウサイズ：1920x1080px

- LiveSplitの設定ファイル
  - お宝マウンテン_3ダブル.lsl
    - 右クリックメニューの[Open Layout]->[From File]にて選択してください
      ![image](https://github.com/user-attachments/assets/68e6e0e2-82d5-4138-a5d6-4f19d2f64cdf)
  - お宝マウンテン_3ダブル.lss
    - 右クリックメニューの[Open Splits]->[From File]にて選択してください
      ![image](https://github.com/user-attachments/assets/3a2a8518-679e-421d-9886-432f97847544)
- RunLeashの設定フォルダ
  - お宝マウンテン_シャッフル3ダブル
    - Fileメニューの[プロファイルをインポート]にて選択してください
      ![image](https://github.com/user-attachments/assets/bf754802-7429-4620-9a86-b688d8d9a579)
