# webpack
## 開発環境
### minimum
課題 webpack.config.js なしでも行けるようにしたい
we
#### webpack.config.js
* loader<br>babel, sass, css,
* source map
* multiple entry point
* webpack-dev-server
<!-- * watch mode?<br>localhost たてれればいらなかも -->
* webpack.config.js<br>本番と開発をわける（改善の余地あり）
<!-- * Tree Shaking あまり理解できていない -->
* SplitChunksPlugin<br>jQueryなどの共通ライブラリを使用しているときに有効
<!-- *  -->
<!-- *  -->

## 機能について
### 必須
#### multiple entry point
複数のエントリーポイントを持つことが可能
#### webpack-dev-server
開発用のローカルサーバーをたてる
#### webpack.config.js
開発用と本番用の設定を分ける
* 開発用はビルドではなくサーバー立ち上げ？
  - 開発用のpubulicにあたるディレクトリが必要？
* 本番用は公開用のファイルをビルド
  - cosole log 削除
#### SplitChunksPlugin
> SplitChunksPluginは「複数のエントリーポイントで利用している共通モジュールをバンドルしたファイル」を出力するプラグインです。
webpack 4 の optimization.splitChunks の使い方、使い所 〜廃止された CommonsChunkPlugin から移行する〜
https://qiita.com/soarflat/items/1b5aa7163c087a91877d



### 検討・調査中
#### watch mode
watch modeは、ファイルを監視して変更があったら `build` を再実行する機能です。
`npm run build` を実行後、ファイルの更新が入るたびに `build` 実行してくれる。
※ localhost たてれればいらなかも…





##
##
1. [Chapter1](#Chapter1)
1. [Chapter2](#Chapter2)
1. [参考文献](#reference)

<!-- 各チャプター -->
<a id="#Chapter1"></a>
# Chapter1

<a id="#Chapter2"></a>
# Chapter2

<a id="#reference"></a>
# 参考文献
- [リンクテキスト](URL)
- [リンクテキスト](URL)


```言語名:ファイル名.拡張子
コードブロック
```

`インライン表示`

>引用文

[リンクテキスト](URL)

| No |    内容     |    備考    |
|---:|-------------|------------|
| 1  |             |            |
| 2  |             |            |