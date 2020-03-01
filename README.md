# 在/root目录下克隆脚本
git clone https://github.com/webkong/linux-scripts.git scripts
# 初始化shell和node
cd script 
./init
# 安装nginx
nginx install 
# 设置.bashrc
export PATH=/root/scripts:$PATH
