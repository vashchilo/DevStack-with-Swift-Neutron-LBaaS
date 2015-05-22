# DevStack-with-Swift-Neutron-LBaaS
Preconfigured DevStack stable/Juno (Snapshot from jennkis 21/05/2015) with Swift, Neutron &amp; LBaaSv2

##Pre-installation
Please check that you distro is updated

sudo apt-get update
sudo apt-get -y upgrade 
sudo apt-get -y dist-upgrade 
sudo apt-get update

##Getting DevStack

git clone https://github.com/Pankov404/DevStack-with-Swift-Neutron-LBaaS

##Installation & Running 
chmod 755 -R DevStack-with-Swift-Neutron-LBaaS
cd DevStack-with-Swift-Neutron-LBaaS
./stack.sh

It takes some time, so be patient

##Finish
Go and check the installed DevStack