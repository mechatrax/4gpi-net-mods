4gpi-net-mods
=============

4GPi を標準設定の Raspbian で使用するための設定ファイルを提供します。

## 提供ファイル
次のファイルがパッケージに含まれています。

### /etc/network/interfaces.d/00-eth0-manual.conf
NetworkManager インストール時に dhcpcd による eth0 の管理を行うための設定ファイルです。

### /etc/network/interfaces.d/00-wlan0-manual.conf
NetworkManager インストール時に dhcpcd による wlan0 の管理を行うための設定ファイルです。

### /etc/network/interfaces.d/00-wlan1-manual.conf
NetworkManager インストール時に dhcpcd による wlan1 の管理を行うための設定ファイルです。

### /etc/sysctl.d/97-net-4gpi.conf
4GPi を使用するためにカーネルパラメータの値を変更するファイルです。

### /etc/systemd/system/dhcpcd.service.d/ignore-wwan.conf
4GPi を使用するために dhcpcd の設定を変更するファイルです。

### /usr/share/doc/4gpi-net-mods/changelog.gz
パッケージの変更履歴を記録したファイルです。

### /usr/share/doc/4gpi-net-mods/copyright
著作権とライセンスを記載したファイルです。
