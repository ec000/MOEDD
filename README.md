#萌咖大佬LinuxDD脚本备份  

Vicer脚本目前不支持重装为CentOS 7系统，支持CentOS 6.9以下版本。  
重装的系统源自官方发行版。  
安装过程全自动进行，无需VNC操作，无需进入救援模式。  
系统安装完成后的默认用户名为root，默认密码为:MoeClub.org  
  
准备条件  
Debian/Ubuntu  
apt-get update  
apt-get install -y xz-utils openssl gawk file  

RedHat/CentOS:  
yum install -y xz openssl gawk file  

重装为CentOS 6.9：  
以下命令中的 -c 后面为CentOS版本号，-v 后面为64位/32位，可根据需求进行替换。  
CentOS 6.9 64位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -c 6.9 -v 64 -a  

CentOS 6.9 32位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -c 6.9 -v 32 -a  

重装为Debian：  
以下命令中的 -d 后面为Debian版本号，-v 后面为64位/32位，可根据需求进行替换。  
Debian 8 64位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -d 8 -v 64 -a  

Debian 9 64位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -d 9 -v 64 -a  

重装为Ubuntu：  
以下命令中的 -u 后面为Ubuntu版本号，-v 后面为64位/32位，可根据需求进行替换。  

Ubuntu 12.04 64位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -u 12.04 -v 64 -a  

Ubuntu 14.04 64位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -u 14.04 -v 64 -a  

Ubuntu 16.04 64位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -u 16.04 -v 64 -a  

Ubuntu 18.04 64位：  
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -u 18.04 -v 64 -a  

#   
脚本地址失效备份  
直接git clone后运行脚本  
git clone https://github.com/ec000/MOEDD.git  
bash InstallNET.sh -d 9 -v 64 -a  



