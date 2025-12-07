# [Kair1jtrのホームページ](https://kair1jtr.github.io/)
## ボクセルレイトレーサを作った

### はじめに
学校の課題でProcessingというプログラミング言語を使ってオリジナルの作品を作成するという課題が出されたので、以前から気になっていたレイトレーシングという3Dグラフィックスの技術を使って何か作ってみようと思った。

Processing単体では描画速度が遅く使い物にならないのでKotlinでProcessingの外部ライブラリを作ってそれをメインにして実行する。
Javaにはオペレーターのオーバーロード機能がなかったのでKotlinを用いた。

また、プログラムを作るのにあたって[このサイト](https://inzkyk.xyz/ray_tracing_in_one_weekend/)
が非常に役に立った。

### 方法
ボクセルレイトレーシングという方法を使う。


### 成果物
今回作ったコード↓\
[成果物](https://github.com/Kair1jtr/Protracer)
