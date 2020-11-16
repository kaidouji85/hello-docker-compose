# Docker Composeチュートリアルの写経

[クィックスタート: Compose と Django](https://docs.docker.jp/compose/django.html) のチュートリアルを写経しました。
このままだと動かなかったので、[このQiita記事](https://qiita.com/takos/items/c04ac2a64d519894ee13) を参考にプロジェクトを修正しました。

## 前提条件
* docker(19.03.13以上)がインストールされている
* docker composer(1.27.4以上)がインストールされている
* ホスト環境のポート8000が使われていない

## 動かし方
```shell script
cd <本リポジトリをクローンした場所>
docker-compose up

# 環境構築にしばらくかかる
# 全部終わったらブラウザからhttp://localhost:8000/を開く
```
