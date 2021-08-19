# NicoCommeDon v1.0.1

## NicoCommeDonとは？
グリーンバック上にMastodonのトゥートがニコニコのコメントみたいに流れていくElectronアプリです．  
Mastodonに流れるトゥートをLTやゲーム中に配信画面上にニコ生のコメント風に載せられたらいいなという個人的願いを叶えるために作りました．  
もし修正点が見つかった場合は何とかして私に連絡いただけると幸いです．

## 起動方法
0. 初回のみNPMのパッケージをダウンロードするために`npm install`を叩く．
1. `npm run build:win64`でビルド．
2. `./dist`内にインストーラが生成されるのでインストールするとデスクトップに実行ファイルが生成される．

## コメント画面の開き方
1. インスタンスのURL(MastodonのURL)を入力して認証コードを発行する．
2. 発行した認証コードを貼り付けてコメント画面に移る．(インスタンスによってはストリーミングを許可していない場合もありますのでご了承ください．)
3. 右下のヒントを参考にコメントを取得する．(ストリーミング開始してすぐの一つ目の，削除や投稿などのストリーミング情報が取得できないバグを観測していますのでご容赦ください．)

## 使用例
OBS StudioのウインドウキャプチャでNicoCommeDonを選択し，クロマキーフィルタをかけて配信映像の上に載っけるとニコニコのコメントっぽくトゥートが流れていきます．アイコンが透ける場合はクロマキーの度合いを調整するのをおすすめします．
