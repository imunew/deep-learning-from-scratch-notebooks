# deep-learning-from-scratch-notebooks

本プロジェクトは、`ゼロから作る Deep Learning`のソースコードを`jupyter notebook`に写経し、自分なりの実装を加えたものになります。

- [oreilly-japan/deep-learning-from-scratch: 『ゼロから作る Deep Learning』のリポジトリ](https://github.com/oreilly-japan/deep-learning-from-scratch)

実行環境には、jupyterの公式イメージである[jupyter/tensorflow-notebook - Docker Hub](https://hub.docker.com/r/jupyter/tensorflow-notebook/)を使用しています。 

## Dockerのインストール
下記のページから、Dockerをダウンロードし、インストールしておいてください。

- https://www.docker.com/products/docker#/mac
- https://www.docker.com/products/docker#/windows

## `Jupyter Notebook`の起動方法

1. dockerイメージを起動

    ```
    $ docker-compose up -d --build
    ```

1. ブラウザから`http://127.0.0.1:8888`にアクセス
