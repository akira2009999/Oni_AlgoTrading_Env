# Oni_AlgoTrading_Env

操作系统 ubuntu-14.04.5-desktop-amd64

一、虚拟机安装及配置
sudo apt-get -y update
sudo apt-get -y upgrade
echo "安装ssh服务方便xshell连接"
sudo apt-get install openssh-server

二、samba安装及配置 ref https://www.cnblogs.com/lidabo/p/4634047.html
echo "安装samba服务方便window访问"

二、共享文件夹
重新安装vmware_tools,安装过程选择覆盖hgfs
tar -zxvf VMwareTools-10.0.10-4301679.tar.gz 
cd vmware-tools-distrib/
sudo ./vmware-install.pl

三、vim安装配置
sudo apt-get install vim
sudo apt-get install vim-gtk

sudo apt-get install ctags

四、git配置
sudo apt-get install git-core


五、python配置
sudo apt-get install python-pip python-dev python2.7-dev build-essential liblapack-dev libblas-dev
sudo pip install numpy
sudo apt-get install libatlas-base-dev gfortran
sudo pip install scipy
sudo pip install pandas
sudo pip install statsmodels
sudo pip install scikit-learn
sudo apt-get install libpng-dev libjpeg8-dev libfreetype6-dev
sudo apt-get install python-matplotlib
sudo apt-get install ipython
sudo apt-get install libqt4-core libqt4-gui libqt4-dev
sudo apt-get install libzmq-dev
sudo pip install pyzmq
sudo pip install pygments
sudo apt-get install ipython-qtconsole
sudo python setup.py install
sudo pip install requests
sudo pip install beautifulsoup4
sudo pip install mysqlclient


六、ibPy配置
cd ~/
mkdir ibapi
cd ibapi/
git clone https://github.com/blampe/IbPy
cd IbPy/

七、mysql配置
sudo apt-get install mysql-server
sudo apt-get install libmysqlclient-dev

mysql -u root -p1
echo "创建数据库及表项"
mysql> source xxx.sql



