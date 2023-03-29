# DiscordVoiceBot
Discord用の文章読み上げBot

# 環境構築
## node.js
nvmを使ってnodeバージョンを管理しています．
```
$ nvm install
```
をすると，このリポジトリに適したnodeバージョンを入れることができます．  
nvmを導入してないよって人は [こちら](https://github.com/nvm-sh/nvm) を参照.

## yarn
パッケージ管理はyarnで行っていますので，
```
$ yarn
```
でパッケージをインストールしてください．  
yarnを導入してないよって人は [こちら](https://qiita.com/suisui654/items/1b89446e03991c7c2c3d) を参照.

## .env
以下のコマンドを実行して.envファイルを作った後，値を入力してください．
```
$ cp .env_sample .env
```

# 実行方法
## 動くか試す
```
$ yarn dev
```

## コンパイルして吐き出す
```
$ yarn build
```
## コンパイル済みのものを実行する
```
$ yarn start
```
## コードをフォーマットする
```
$ yarn format
```