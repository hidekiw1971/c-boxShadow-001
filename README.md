# box-shadow(width: 100%;に影を付ける)

## 説明

- 親要素・子要素共に横幅を 100％していると margin-right は描画位置が変わらないので、margin ができない。（存在するけど見えない）
- margin-left は描画位置が変わるから margin が見える。
- margin-right は描画位置が変わらないので margin が見えない。
- margin は要素の外に逃げていく形になるので効かないようにみえているだけ。

## イメージ画像

<img width="391" alt="image" src="https://user-images.githubusercontent.com/99580997/156009011-6e2cea5e-828f-46a8-b6a1-7d1ff8d05f18.png">
<img width="778" alt="image" src="https://user-images.githubusercontent.com/99580997/156009064-3843f40b-9943-4ce8-8764-4599c599b085.png">
<img width="1018" alt="image" src="https://user-images.githubusercontent.com/99580997/156009124-6ac98b1b-036d-4734-8189-0e33b0fd3330.png">

## portfolio url:

- https://css-md-0013.wtb.cfbx.jp/

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## 参考にしたサイト

- margin-right が効かない！？margin-left は効く、どういうことなのか【HTML/CSS】
- https://daichan-blog.com/archives/3042
- CSS - box-shadow
- https://www.tohoho-web.com/css/prop/box-shadow.htm
- これはダメ(そもそも width: 100%;に margin-right が付かないから)
- https://www.nyamucoro.com/entry/2019/02/01/201231

## 更新履歴

- 2022/3/8 リポジトリ名変更(css-box-shadow-001 -> c-boxShadow-001)
- 2022/2/28 初版 作成完了

## 環境・使い方

- ダウンロードしたフォルダを開く
- ターミナルを開き、 npm i とコマンドを入力
- node_modules と package-lock.json が生成されるのを確認する
- 「 npx gulp 」とコマンドを入力すると動き出します

## 仕様

-
-

## 備考

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
