###simpleWebServer

pythonのsimplehttpserver的な物です．
起動したディレクトリをドキュメントルートディレクトリとして簡易的なwebserverを立ち上げます。
ブラウザのセキュリティ機能によってXMLHttpRequestでローカルファイルが読み込めないときに使います。

<br />

使い方

```sh
$ node server.js 
```

でフォルトでは8888ポートで起動します。
ポートを指定したい時は以下


```sh
$ node server.js 8000
```