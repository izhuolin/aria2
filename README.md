由于原作者脚本国内80%无法正常安装使用 
此版本修改了代理文件下载与到点定时任务不执行？
我机器是如此修改后一切正常使用

系统要求

CentOS 6+（官方停源/无效） / Debian 6+ / Ubuntu 14.04+

安装脚本

wget -N https://ghp.ci/https://raw.githubusercontent.com/izhuolin/aria2/master/aria2.sh && chmod +x aria2.sh

运行脚本

./aria2.sh

其他操作

启动： service aria2 start

停止： service aria2 stop

重启： service aria2 restart

查看状态： service aria2 status

配置文件路径：/root/.aria2c/aria2.conf （配置文件有中文注释，若语言设置有问题会导致中文乱码）

默认下载目录：/root/downloads

RPC 密钥：随机生成，可使用选项7. 修改 配置文件自定义
