姫路IT系勉強会 Webサイト移行検討用リポジトリ
============================================

姫路IT系勉強会のWebサイトをGoogle Sitesから[Hexo](https://hexo.io/)とGitHub Pagesを利用したサイトへの移行を検討するためのリポジトリです。


テスト方法
--------------------------------------------

サイトの生成にHexoを利用しているので利用するためのパッケージをインストールします。

    $ sudo apt install git nodejs nodejs-legacy npm

Hexoをインストールします。

    $ sudo npm install -g hexo-cli

このリポジトリをクローンします。

    $ git clone https://github.com/histudy/website.git

クローンしたリポジトリに必要なパッケージをインストールします。

    $ cd website/
    $ npm install

ビルドしてHexoのサーバーを起動します。

    $ hexo g
    $ hexo s

ブラウザで http://localhost:4000 にアクセスすると内容の確認ができます。


検討課題
--------------------------------------------

- テンプレートのカスタマイズとか
    - 現在は[hueman](https://github.com/ppoffice/hexo-theme-hueman)を少し変更して使用中
- 更新方法の検討とか

