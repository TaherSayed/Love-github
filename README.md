#VPN

Create a VPS from here, Server Required : Centos 7 x86_64 -v2.5.

Login As root and Run it:

cd /tmp/ && yum install git -y && git clone https://github.com/TaherSayed/2022.git && cd OPEN-VPN-ACCESS-SERVER/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh

ADD USER

useradd yourusername passwd yourpassword