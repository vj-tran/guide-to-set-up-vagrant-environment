下記の開発環境を作るガイド

・OS Ubuntu precise 64

・PHP 5.5.3

・MySQL 5.5

・nginx 1.1.19


環境構築手順

1)Vagrantサイトより、最新版のVagrantをダウンロードし、インストールをする

http://downloads.vagrantup.com/

2)同様にVirtualboxをインストールする

https://www.virtualbox.org/wiki/Downloads

3)本"Miso Development Environment"のソース一式をgitで自分のPCにダウンロードする

4)下記の「フォルダ構成」に従い、環境フォルダを構成する

5)コマンドラインからVagrantfileのあるフォルダに移動し、下記のコマンドを実行する

Vagrant up

6)ブラウザより、下記のリンクで正常に環境ができたかどうかをチェックする

http://127.0.0.1:8080/

※手順5)を実行する前に他のサービスがポート8080を使っているかチェックする必要がある

環境内容

OS Ubuntu precise 64

PHP 5.5.3

MySQL 5.5

nginx 1.1.19

Document Root

/vagrant_data/www

フォルダ構成
.

├── Environment

│ ├── Vagrantfile

│ └── cookbooks

│ └── omusubi

│ ├── README.md

│ ├── attributes

│ │ └── default.rb

│ ├── recipes

│ │ ├── default.rb

│ │ └── gentoo.rb

│ └── templates

│ └── default

│ ├── php-fpm.conf.erb

│ └── www2.conf.erb

└── Source

└── www

└── index.php


SourceフォルダはゲストOSの/vagrant_dataフォルダと連動

SourceフォルダはGitでは管理していないので自分で作成


アクセスリンク

http://127.0.0.1:8080/