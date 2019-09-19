[阿里云香港服务器 24元一个月500G](https://s.click.taobao.com/t?e=m%3D2%26s%3DDEJk%2BTTx3N8cQipKwQzePCperVdZeJviEViQ0P1Vf2kguMN8XjClArulokTJULhuNnGHDv9u8g6kiKgHg8sJQGF8NQSYm52K%2BCCWPth0FrLw2PXv%2BKffqxVF%2BG%2F2LD3qKIUZKvQyk4%2FkxFiXT%2FI5kZuVJ2zJE2c0p3fRQ0ORdflbmmsujxxDvKiBJVMc%2BOMFCM7aOFaXltYhhQs2DjqgEA%3D%3Dhttps://s.click.taobao.com/t?e=m%3D2%26s%3DDEJk%2BTTx3N8cQipKwQzePCperVdZeJviEViQ0P1Vf2kguMN8XjClArulokTJULhuNnGHDv9u8g6kiKgHg8sJQGF8NQSYm52K%2BCCWPth0FrLw2PXv%2BKffqxVF%2BG%2F2LD3qKIUZKvQyk4%2FkxFiXT%2FI5kZuVJ2zJE2c0p3fRQ0ORdflbmmsujxxDvKiBJVMc%2BOMFCM7aOFaXltYhhQs2DjqgEA%3D%3D) 
## ShadowsocksR 里面有使用方法

## 使用前记得卸载监控软件
``` bash
su root
service aegis stop 
chkconfig --del aegis
wget http://update.aegis.aliyun.com/download/uninstall.sh
chmod +x uninstall.sh
./uninstall.sh
pkill aliyun-service
rm -fr /etc/init.d/agentwatch /usr/sbin/aliyun-service
rm -rf /usr/local/aegis*
```
