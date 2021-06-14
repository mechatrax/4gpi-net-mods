4gpi-net-mods
=============

4GPi を標準設定の Raspbian で使用するための設定ファイルを提供します。

## 提供ファイル
次のファイルがパッケージに含まれています。

### /etc/sysctl.d/97-net-4gpi.conf
4GPi を使用するために カーネルパラメータ の値を変更するファイルです。

### /etc/systemd/system/dhcpcd.service.d/ignore-wwan.conf
4GPi を使用するために dhcpcd の設定を変更するファイルです。

### /usr/share/doc/4gpi-net-mods/changelog.gz
パッケージの変更履歴を記録したファイルです。

### /usr/share/doc/4gpi-net-mods/copyright
著作権とライセンスを記載したファイルです。
