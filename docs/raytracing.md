# ボクセルレイトレーサを作った

学校の課題でProcessingというプログラミング言語を使って好きなプログラムを作成するという課題が出されたので、以前から気になっていたレイトレーシングという3Dグラフィックスの技術を使って何か作ってみようと思った。

Processing単体では描画速度が遅く、使い物にならないのでKotlinでProcessingの外部ライブラリを作り、それを用いる。
C++にはクラスのオペレーターをオーバーロードできる機能があるが、JavaにはそれがなかったのでKotlinを用いた。

また、プログラムを作るのにあたって[このサイト](https://inzkyk.xyz/ray_tracing_in_one_weekend/)
が非常に役に立った。

[成果物](https://github.com/Kair1jtr/Protracer)
