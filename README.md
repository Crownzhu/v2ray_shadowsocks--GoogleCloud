# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本

安装或卸载
要求：Ubuntu 14+ / Debian 7+ / CentOS 7+ 系统的小鸡鸡
推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。
1. 使用命令sudo -i取得root权限
2. 使用 root 用户输入下面命令安装或卸载
    git clone https://github.com/Crownzhu/v2ray--shadowsocks
    cd v2ray
    chmod +x install.sh
    ./install.sh local

如果提示 git 命令不可用
则使用 root 用户输入下面命令安装或卸载
bash <(curl -s -L https://233blog.com/v2ray.sh)
