###simpleWebServer

pythonのsimplehttpserver的な物です．

起動したディレクトリをドキュメントルートディレクトリとして簡易的なwebserverを立ち上げます。

ブラウザのセキュリティ機能によってXMLHttpRequestでローカルファイルが読み込めないときに使います。

<br />

使い方

```sh
$ node server.js 
```

デフォルトでは8888ポートで起動します。

ブラウザでhttp://127.0.0.1:8888/にアクセスするとindex.htmlが表示されます。

ポートを指定したい時は以下


```sh
$ node server.js 8000
```