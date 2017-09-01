# 概要
公共Wi-Fiなどに接続していてインターネットに繋がらなくなり、再接続が必要なときにコマンド1つでWi-Fiに再接続することができるツールです。

# 対応OS
- macOS(macOS Sierra 10.12.5で動作を確認)

# ダウンロード
以下のURLからダウンロードしてください。

https://github.com/kaichi1202/wifi/releases/tag/v1.0

# インストール方法
ダウンロードしたフォルダで
```console
$ chmod +x wifi
$ cp wifi /usr/local/bin/
# 上のコマンドが実行できない場合
$ sudo cp wifi /usr/local/bin/
```

# 使い方
```console
$ wifi
```
もしくは、wifi.appを実行

# 今後
インターネットへの接続チェックの結果に応じて自動的に再接続するような機能を実装したいです。もし実装してもいいよ！という方がおられましたら、ぜひPull Requestをお願い致します。
