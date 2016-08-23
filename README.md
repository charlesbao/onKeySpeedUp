# onKeySpeedUp
use for BandwagonHost in centos6 minimal. 64MB ram vps

## Installation
	wget https://github.com/snooda/net-speeder/archive/master.zip
	unzip master.zip
	wget http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
	rpm -ivh epel-release-6-8.noarch.rpm
	yum install -y libnet libpcap libnet-devel libpcap-devel
	cd net-speeder-master
	sh build.sh -DCOOKED
	nohup ./net_speeder venet0 "ip" &

