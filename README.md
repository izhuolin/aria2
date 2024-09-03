系统要求

CentOS 6+ / Debian 6+ / Ubuntu 14.04+

安装脚本

wget -N https://mirror.ghproxy.com/https://raw.githubusercontent.com/P3TERX/aria2.sh/master/aria2.sh && chmod +x aria2.sh

运行脚本

./aria2.sh

其他操作

启动：/etc/init.d/aria2 start | service aria2 start
停止：/etc/init.d/aria2 stop | service aria2 stop
重启：/etc/init.d/aria2 restart | service aria2 restart
查看状态：/etc/init.d/aria2 status | service aria2 status
配置文件路径：/root/.aria2c/aria2.conf （配置文件有中文注释，若语言设置有问题会导致中文乱码）
默认下载目录：/root/downloads
RPC 密钥：随机生成，可使用选项7. 修改 配置文件自定义
