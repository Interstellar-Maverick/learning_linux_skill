# ubuntu-install-or-something

安装程序的过程
  '1' jdk-11 install
  
  wget https://mirrors.huaweicloud.com/java/jdk/11+28/jdk-11_linux-x64_bin.tar.gz
  
tar -zxvf jdk-11_linux-x64_bin.tar.gz


#添加下载源安装neo4j

wget -O - https://debian.neo4j.org/neotechnology.gpg.key | sudo apt-key add -

echo 'deb https://debian.neo4j.org/repo stable/' | sudo tee /etc/apt/sources.list.d/neo4j.list

sudo apt-get update

sudo apt-get install neo4j

## pip 加国内源

-i http://pypi.douban.com/simple/ --trusted-host pypi.douban.com
