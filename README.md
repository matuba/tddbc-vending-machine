VendingMachine
==============


## ステップ0
- 総計を取得できる
- お金を投入できる
  - お金はオブジェクト？ #=> とりあえず数値で
  - 複数回投入できる
- 払い戻しができる
  - 総計が返ってくる
  - 投入金額が0になる

## ステップ1
- 1円玉は投入できない
  - そのまま返ってくる
  - 5円玉とか五千円札も
  - とりあえずinsertで弾く