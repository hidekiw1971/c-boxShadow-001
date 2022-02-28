# box-shadow(width: 100%;に影を付ける)

## 説明
- 親要素・子要素共に横幅を100％しているとmargin-rightは描画位置が変わらないので、marginができない。（存在するけど見えない）
- margin-leftは描画位置が変わるからmarginが見える。
- margin-rightは描画位置が変わらないのでmarginが見えない。
- marginは要素の外に逃げていく形になるので効かないようにみえているだけ。

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
- margin-rightが効かない！？margin-leftは効く、どういうことなのか【HTML/CSS】
- https://daichan-blog.com/archives/3042
- CSS - box-shadow
- https://www.tohoho-web.com/css/prop/box-shadow.htm
- これはダメ(そもそもwidth: 100%;にmargin-rightが付かないから)
- https://www.nyamucoro.com/entry/2019/02/01/201231

## 更新履歴

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
- rem記述
- ルートフォントをvwで設定していることからPCサイズのレイアウトをタブレットで表示させることが出来ます（remで書いた場合のみ）。
