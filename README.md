## 必要な環境
- php5: 5.3以上(Composer)を使用するため
- php5-mcrypt
- Composer(パッケージ管理にComposerを使用しています)
- curl(あると便利です)

## 概要
簡単にcakephpを使用したREST(?)APIアプリケーションのひな形をつくってみました。

## 使用方法
1. git clone git@github.com:oh240/cakephp_simple_api
2. cd cakephp_simple_api
3. php composer.phar install
4. Console/cake server -p 9999
5. curl localhost:9999/posts/1 とかで動作確認する

## 詳細情報
[http://oh240.github.io/2014/10/simple-api-cakephp/](http://oh240.github.io/2014/10/simple-api-cakephp/)

