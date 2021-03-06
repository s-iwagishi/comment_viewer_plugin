# コメントビューア プラグイン

# 概要
本ソフトウェアは以下のソフトウェアの非公式プラグインになります。
* やります！アンコちゃん (http://yarimasu.ankochan.net/)
* Showroom Comment Log viewer しょころ(仮） (http://ameblo.jp/nyon-neco)
* MultiCommentViewer (https://github.com/CommentViewerCollection/MultiCommentViewer/) 
* NicoNamaCommentViewer (https://www.posite-c.com/application/ncv/)

本プラグインを導入し、VRライブ・コミュニケーションサービス「バーチャルキャスト」で使用可能な以下のVCIアイテムと連携することで、
VCIアイテムの機能でサポートされていない運営コメント、YouTube, Twitchのコメントをバーチャルキャスト内に表示することが出来ます。

[コメントビューア連携コメビュ(受信表示側)](https://seed.online/items/c27a748bc2125f5f038ac841a612cdea2248377feee00b5cafb7974b16d4bfe1)

[コメントビューア連携コメビュ(あんこちゃん送信用)](https://seed.online/items/e373145bb2c97f98b4b045cbeeaec2660f3dd2f713ba1d6551b2ff2a245cca5b)

[コメントビューア連携コメビュ(しょころ送信用)](https://seed.online/items/f9a5b33c6a71d4f325f3771e577e2982defbab2f3c6d63ac6bc6e41c6952fd58)

[コメントビューア連携コメビュ(MCV送信用)](https://seed.online/items/c1f5bd1852c9a0182c59c8f1a14d7492cab922928fb18e7ebd501af47ac561b8)

[コメントビューア連携コメビュ(NCV送信用)](https://seed.online/items/af6f9f11ab98bb01bddb6b47dfd39c18293d8ec3c7a5b770c1292ff210824588)

# ダウンロード
[ダウンロードページ](https://github.com/chinng-inta/comment_viewer_plugin/releases)

# 導入方法
## やります！アンコちゃん
ankoPlugin_forVCas.dllをやります！アンコちゃんのpluginフォルダにコピーします。

## Showroom Comment Log viewer しょころ(仮）
shocoroPrugin.dllをShowroom Comment Log viewer しょころ(仮）のpluginフォルダにコピーします。

## MultiCommentViewer
MCVPluginforVCas\MCV_VCasPlugin.dllをフォルダごと、MultiCommentViewerのpluginフォルダにコピーします。

## NicoNamaCommentViewer
NCV_plugin_for_VCas.dllをフォルダNicoNamaCommentViewerのpluginフォルダにコピーします。

# 削除方法
ファイルをフォルダから削除します


# 使い方
## やります！アンコちゃん
メニューのプラグインからankoPlugin_forVCasを選択します。
別ウィンドウが起動します。

![ankoPlugin_forVCas](https://github.com/chinng-inta/comment_viewer_plugin/blob/master/resource/image/ankoPlugin_forVCas.jpg)
1. 参照をクリックし、コメントビューア連携コメビュ(あんこちゃん送信用)のmain.lua(※1)を選択。
2. 開始を押すことで、VCIアイテムへのコメント送信が開始されます。
3. 運営コメントのみVCIに送信にチェックを入れることで、ニコニ広告やニコ生クルーズのコメントのみVCIに送信することも可能です。

※1 デフォルトでは、"C:\Users\(ユーザ名)\AppData\LocalLow\infiniteloop Co,Ltd\VirtualCast\EmbeddedScriptWorkspace\コメントビューア連携コメビュ(あんこちゃん送信用)\main.lua"になります。
　ファイルが存在しない場合は、同じフォルダの_main.luaをmain.luaという名前でコピーしてください。

## Showroom Comment Log viewer しょころ(仮）
メニューのプラグインからShocoroToluaを選択します。
別ウィンドウが起動します。

![shocoroPrugin](https://github.com/chinng-inta/comment_viewer_plugin/blob/master/resource/image/shocoroPrugin.jpg)
1. 参照をクリックし、コメントビューア連携コメビュ(しょころ送信用)のmain.lua(※2)を選択。
2. 開始を押すことで、VCIアイテムへのコメント送信が開始されます。
3. ギフトのみVCIに送信にチェックを入れることで、ギフトのコメントのみVCIに送信することも可能です。

※2 デフォルトでは、"C:\Users\(ユーザ名)\AppData\LocalLow\infiniteloop Co,Ltd\VirtualCast\EmbeddedScriptWorkspace\コメントビューア連携コメビュ(しょころ送信用)\main.lua"になります。
　ファイルが存在しない場合は、同じフォルダの_main.luaをmain.luaという名前でコピーしてください。

## MultiCommentViewer

メニューのプラグインからVCasを選択します。
別ウィンドウが起動します。

![MCV_VCasPlugin](https://github.com/chinng-inta/comment_viewer_plugin/blob/master/resource/image/MCV_VCasPlugin.jpg)
1. 参照をクリックし、コメントビューア連携コメビュ(MCV送信用)のmain.lua(※3)を選択。
2. 開始を押すことで、VCIアイテムへのコメント送信が開始されます。

※3 デフォルトでは、"C:\Users\(ユーザ名)\AppData\LocalLow\infiniteloop Co,Ltd\VirtualCast\EmbeddedScriptWorkspace\コメントビューア連携コメビュ(MCV送信用)\main.lua"になります。
　ファイルが存在しない場合は、同じフォルダの_main.luaをmain.luaという名前でコピーしてください。

## NicoNamaCommentViewer
メニューのプラグインからNCV_plugin_for_VCasを選択します。
別ウィンドウが起動します。

![NCV_plugin_for_VCas](https://github.com/chinng-inta/comment_viewer_plugin/blob/master/resource/image/NCV_plugin_for_VCas.jpg)
1. 参照をクリックし、コメントビューア連携コメビュ(しょころ送信用)のmain.lua(※2)を選択。
2. 開始を押すことで、VCIアイテムへのコメント送信が開始されます。
3. ギフトのみVCIに送信にチェックを入れることで、ギフトのコメントのみVCIに送信することも可能です。

※2 デフォルトでは、"C:\Users\(ユーザ名)\AppData\LocalLow\infiniteloop Co,Ltd\VirtualCast\EmbeddedScriptWorkspace\コメントビューア連携コメビュ(NCV送信用)\main.lua"になります。
　ファイルが存在しない場合は、同じフォルダの_main.luaをmain.luaという名前でコピーしてください。

# 連絡先
twitter : https://twitter.com/chinng_inta

# 更新履歴

| version | date       | detail  |
| ------- | ---------- | -------- |
| v1.0.0  | 2019/12/16 | 初版公開 |
| v1.0.1  | 2019/12/20 | "\"や"/"等のluaのjsonで処理できない文字を全角に変換する対応<br/>"$"がファイル書き出し時に正しく処理できない問題の修正 |
| v1.1.0  | 2019/12/23 | NCV対応 |
| v1.1.1  | 2020/3/1 | 全般<br/>VCIのmain.luaが指定されていない状態でプラグインを実行しようとした場合、メッセージウィンドウで通知するよう修正<br/>MCV<br/>v0.5.13対応<br/>あんこちゃん<br/>こてはんが表示されない問題修正<br/>NCV<br/>全てのコメントが運営コメント扱いされる問題を修正 |

# 免責事項
本ソフトウェアはフリーソフトであり、バグ等についても修正する義務を負わないものとします。
また、本ソフトウェアを使用したことによるデータの破壊等の責任は負わないものとします。

## License
MIT
