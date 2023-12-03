# Install_Check-run-passについて
<br>

## 概要
<li>指定したソフト、適切なバージョンがインストールされているか確認を行い、実行の可否を判断するもの
<li>ログオンバッチで毎日実行するなど、継続してチェックしたい場合に有効
<br>
<br>

## 注意点
<li>ビルドが違う場合を前提に作成、同じソフトで同じビルドの場合は、インストール実施前にアンインストールを実行する必要がある
<li>インストール実行時のUACでの通知画面が表示された場合の確認と実施に関して、ユーザーに周知する必要あり
<li>余計なUACの通知を回避するため、通常実行でプログラムがスタートすることを想定<br>`#ffffff`インストール実行時のみ管理者権限に動的に昇格
 
<br>
<br>

## Install_Check.bat

