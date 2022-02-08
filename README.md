# java-on-docker

Docker によるシンプルな Java 開発環境

## How to Use

```
// dockerビルド
$ docker-compose build

// dockerをバックグラウンドで起動
$ docker-compose up -d

// インスペクション
$ docker-compose exec java bash

// コンパイル
root@xxx:/usr/src# javac Main.java

// 実行
root@xxx:/usr/src# java Main
Hello World!
```

参考：[Docker × Java シンプルすぎる開発環境構築](https://qiita.com/A-Kira/items/0dda255e00771f556e2a)
