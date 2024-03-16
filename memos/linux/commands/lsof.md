# lsof

オープンしているファイルやネットワーク接続を表示するコマンド。
セキュリティの観点から、すべての情報を表示するにはsudoで実行する必要がある。

## option

| option | description                                        |
| ------ | -------------------------------------------------- |
| -i     | ネットワーク接続に関連する情報をフィルタリングする |
| -n     | ホスト名の代わりにIPアドレスを表示する             |
| -P     | ポート名の代わりにポート番号を表示する             |

## output

LISTEN: 他のホストからの待ち受けをしているポート
ESTABLISHED: 他のホストと通信しているポート
どちらでもないものはUDPのデータである。