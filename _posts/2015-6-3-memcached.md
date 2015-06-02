# memcachedの基礎の基礎

## 何故memcachedを導入するのか

- 動的なウェブアプリケーションの高速化やスケーラビリティの向上を行う。
    - 多くのWebアプリケーションは，RDBMSにデータを格納し，アプリケーションサーバでそのデータを引き出してブラウザ等に表示させている。
しかしデータが大量になったり，アクセスが集中すると，RDBMSの負荷があがり，データベースのレスポンスが悪化し，Webサイトの表示が遅延するなど大きな影響がでてしまう。

## memcachedは何をしてくれるのか

- 高性能な分散メモリキャッシュサーバ。
- データベースへの問い合わせ結果を一時的にキャッシュすることで，データベースへのアクセス回数を減らす。

## 参考URL

- http://www.ibm.com/developerworks/jp/opensource/library/os-memcached/
- http://gihyo.jp/dev/feature/01/memcached/0001
- http://yuuki.hatenablog.com/entry/facebook-memcached-paper
