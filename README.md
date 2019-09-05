# Megatools-CentOS-install  
yum -y install gcc make glib2-devel libcurl-devel openssl-devel gmp-devel tar automake autoconf libtool wget asciidoc -y  
wget https://megatools.megous.com/builds/experimental/megatools-1.11.0-git-20190608.tar.gz  
tar -xzvf megatools*.tar.gz  
cd megatools*  
./configure  
make  
make install
