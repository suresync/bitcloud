# bitcloud
blocktime 5min<br>
3 MB blocksystem<br>
Algo Quark<br>
Port 8329[<br>
POS3 6h staking minage<br>
Masternode Amount 10,000 BTDX <br>
Staking 40% / Masternodes 60 %<br>
Max Coin in 8 Years ~42 Mio<br>



<code>apt-get update</code><br>
<code>apt-get upgrade -y</code><br>
<code>apt-get --assume-yes install ufw</code></br>
<code>ufw allow OpenSSH</code></br>
<code>ufw allow 8329</code></br>
<code>ufw default deny incoming</code></br>
<code>ufw default allow outgoing</code></br>
<code>ufw --force enable</code></br>
<code>apt-get install software-properties-common -y</code><br>
<code>add-apt-repository ppa:bitcoin/bitcoin -y</code><br>
<code>apt-get update</code><br>
<code>apt-get --assume-yes install nano git unzip libboost-program-options-dev libboost-test-dev libdb4.8-dev libdb4.8++-dev libminiupnpc-dev libevent-dev libzmq3-dev libboost-filesystem1.58.0 libdb4.8++ libevent-2.0-5 libevent-core-2.0-5 libevent-pthreads-2.0-5 libminiupnpc10 libsodium18 libboost-system1.58.0 libboost-thread1.58.0 libevent-2.0-5 libzmq5 libboost-chrono1.58.0</code><br>
<code>wget https://github.com/LIMXTEC/Bitcloud/releases/download/v.2.0.0.3/Linux.2-0-0-3.tar.gz</code><br>
<code>tar -xvzf Linux.2-0-0-3.tar.gz</code><br>

Let's create the initial bitcloud.conf file!</br>

<code>mkdir ~/.bitcloud</code></br>
<code>cd ~/.bitcloud</code></br>

Create your bitcloud.conf file here and replace everything between {}.</br>
<code>nano bitcloud.conf</code></br>
</br>
rpcuser={user}</br>
rpcpassword={some pass}</br>
discover=1</br>
externalip={your external ip}</br>
rpcallowip=127.0.0.1</br>
daemon=1</br>
server=1</br>
listen=1</br>
maxconnections=100</br>
logtimestamps=1</br>
addnode=147.135.233.46:8329</br>
addnode=190.57.229.106:8329</br>
addnode=185.194.142.125:8329</br>
addnode=185.194.140.60:8329</br>
addnode=188.68.39.1:8329</br>
addnode=185.82.23.92:8329</br>
addnode=45.79.175.168:8329</br>
addnode=51.15.221.253:8329</br>
addnode=107.173.222.133:8329</br>
addnode=104.236.219.255:8329</br>
addnode=45.43.21.230:8329</br>
addnode=185.34.71.83:8329</br>
addnode=80.208.229.160:8329</br>
addnode=80.209.225.134:8329</br>
addnode=172.104.147.155:8329</br>
addnode=37.200.122.223:8329</br>
addnode=163.172.171.148:8329</br>
addnode=51.15.212.203:8329</br>
addnode=47.74.144.66:8329</br>
addnode=192.3.213.160:8329</br>
addnode=45.77.129.244:8329</br>
addnode=50.67.60.185:8329</br>
addnode=85.214.139.205:8329</br>
addnode=77.56.153.243:8329</br>
addnode=51.15.74.115:8329</br>
addnode=54.193.85.71:8329</br>
addnode=47.91.41.3:8329</br>
addnode=51.15.142.165:8329</br>
addnode=84.39.96.180:8329</br>
addnode=45.33.83.9:8329</br>
addnode=45.79.149.7:8329</br>
addnode=51.15.46.94:8329</br>
addnode=98.230.78.71:8329</br>
addnode=80.188.83.199:8329</br>
addnode=107.175.49.179:8329</br>
addnode=104.238.182.186:8329</br>
addnode=80.209.225.201:8329</br>
addnode=45.77.145.195:8329</br>
addnode=213.136.86.202:8329</br>
addnode=163.172.169.55:8329</br>
addnode=51.15.75.183:8329</br>
addnode=13.59.72.30:8329</br>
addnode=80.209.225.23:8329</br>
addnode=45.55.195.243:8329</br>
addnode=172.104.131.165:8329</br>
addnode=80.209.225.202:8329</br>
addnode=80.209.228.131:8329</br>
addnode=51.15.68.41:8329</br>
addnode=80.209.228.168:8329</br>
addnode=83.85.130.139:8329</br>
addnode=45.32.255.250:8329</br>
addnode=185.183.158.161:8329</br>
addnode=213.136.86.205:8329</br>
addnode=80.209.227.203:8329</br>
addnode=84.200.92.232:8329</br>
addnode=172.104.155.172:8329</br>
addnode=213.32.18.147:8329</br>
addnode=95.154.201.157:8329</br>
addnode=85.214.228.230:8329</br>
addnode=104.251.219.36:8329</br>
addnode=108.61.190.91:8329</br>
addnode=163.172.187.110:8329</br>
addnode=127.0.0.1:8329</br>
addnode=89.255.71.61:8329</br>
addnode=51.15.204.25:8329</br>
addnode=127.0.0.2:8329</br>
addnode=46.254.64.201:8329</br>
addnode=80.209.226.61:8329</br>
addnode=45.77.130.204:8329</br>
addnode=192.99.139.133:8329</br>
addnode=212.159.69.141:8329</br>
addnode=51.15.57.35:8329</br>
addnode=139.162.166.9:8329</br>
addnode=45.63.65.126:8329</br>
addnode=104.237.144.7:8329</br>
addnode=104.238.158.51:8329</br>
addnode=192.227.227.35:8329</br>
addnode=104.156.225.153:8329</br>
addnode=45.32.234.36:8329</br>
addnode=45.76.75.121:8329</br>
addnode=54.183.236.97:8329</br>
addnode=51.15.223.152:8329</br>
addnode=45.32.154.221:8329</br>
addnode=107.172.168.123:8329</br>
addnode=54.154.128.148:8329</br>
addnode=80.209.226.41:8329</br>
addnode=51.15.74.186:8329</br>
addnode=54.153.115.24:8329</br>
addnode=45.76.83.58:8329</br>
addnode=217.182.209.168:8329</br>
addnode=45.32.211.9:8329</br>
addnode=185.213.210.12:8329</br>
addnode=163.172.135.251:8329</br>
addnode=108.61.170.99:8329</br>
addnode=61.220.97.194:8329</br>
addnode=51.15.198.253:8329</br>
addnode=50.116.58.64:8329</br>
addnode=37.72.28.203:8329</br>
addnode=34.240.3.43:8329</br>
addnode=185.209.20.29:8329</br>
addnode=134.249.122.219:8329</br>
addnode=173.212.243.84:8329</br>
addnode=51.15.214.194:8329</br>
addnode=51.15.60.194:8329</br>
addnode=45.33.66.44:8329</br>
addnode=45.32.174.220:8329</br>
addnode=104.244.76.14:8329</br>
addnode=176.199.49.210:8329</br>
addnode=51.15.94.151:8329</br>
addnode=45.76.23.65:8329</br>
addnode=213.136.86.207:8329</br>
addnode=134.255.220.174:8329</br>
addnode=163.172.153.202:8329</br>
addnode=51.15.202.170:8329</br>
addnode=94.176.238.54:8329</br>
addnode=45.77.137.107:8329</br>
addnode=45.32.41.150:8329</br>
addnode=47.74.149.25:8329</br>
addnode=127.0.0.3:8329</br>
addnode=185.82.22.33:8329</br>
addnode=37.72.28.176:8329</br>
addnode=51.15.219.3:8329</br>
addnode=46.28.108.91:8329</br>
addnode=45.76.91.85:8329</br>
addnode=108.61.247.81:8329</br>
addnode=45.77.138.148:8329</br>
addnode=158.69.48.59:8329</br>
addnode=46.38.242.8:8329</br>
addnode=95.85.25.145:8329</br>
addnode=45.43.21.41:8329</br>
addnode=45.76.76.91:8329</br>
addnode=202.0.37.87:8329</br>
addnode=107.172.197.222:8329</br>
addnode=73.15.33.129:8329</br>
addnode=92.27.223.104:8329</br>
addnode=107.172.196.185:8329</br>
addnode=51.254.212.145:8329</br>
addnode=45.76.19.145:8329</br>
addnode=47.90.202.94:8329</br>
addnode=108.61.164.199:8329</br>
addnode=75.130.162.248:8329</br>
addnode=80.209.225.179:8329</br>
addnode=144.217.229.223:8329</br>
addnode=80.208.227.77:8329</br>
addnode=194.58.69.85:8329</br>
addnode=51.15.89.110:8329</br>
addnode=104.131.183.21:8329</br>
addnode=137.59.252.167:8329</br>
addnode=128.199.177.10:8329</br>
addnode=45.63.64.235:8329</br>
addnode=188.195.106.199:8329</br>
addnode=127.0.0.4:8329</br>
addnode=194.135.88.175:8329</br>
addnode=198.74.60.53:8329</br>
addnode=45.63.101.10:8329</br>
addnode=47.254.129.26:8329</br>
addnode=84.200.7.221:8329</br>
addnode=163.172.176.107:8329</br>
addnode=51.254.212.140:8329</br>
addnode=151.80.147.71:8329</br>
addnode=80.209.225.24:8329</br>
addnode=51.15.89.87:8329</br>
addnode=95.85.13.73:8329</br>
addnode=127.0.0.5:8329</br>
addnode=80.209.227.243:8329</br>
addnode=107.173.250.224:8329</br>
addnode=212.47.246.150:8329</br>
addnode=128.90.20.128:8329</br>
addnode=107.174.61.106:8329</br>
addnode=45.79.73.151:8329</br>
addnode=145.239.91.115:8329</br>
addnode=107.172.95.44:8329</br>
addnode=35.202.196.122:8329</br>
addnode=212.73.150.73:8329</br>
addnode=83.217.206.56:8329</br>
addnode=45.79.87.214:8329</br>
addnode=107.173.222.132:8329</br>
addnode=104.207.138.214:8329</br>
addnode=45.32.123.211:8329</br>
addnode=181.228.246.133:8329</br>
addnode=45.77.138.85:8329</br>
addnode=47.89.183.28:8329</br>
addnode=127.0.0.8:8329</br>
addnode=45.32.239.230:8329</br>
addnode=185.183.158.170:8329</br>
addnode=213.136.80.93:8329</br>
addnode=126.117.205.210:8329</br>
addnode=45.32.76.214:8329</br>
addnode=51.254.212.133:8329</br>
addnode=104.207.130.93:8329</br>
addnode=108.61.167.247:8329</br>
addnode=127.0.0.7:8329</br>
addnode=190.57.229.209:8329</br>
addnode=104.156.232.152:8329</br>
addnode=151.236.63.137:8329</br>
addnode=172.104.13.253:8329</br>
addnode=80.209.225.181:8329</br>
addnode=54.36.70.224:8329</br>
addnode=54.36.71.26:8329</br>
addnode=176.36.60.144:8329</br>
addnode=139.162.168.158:8329</br>
addnode=45.77.143.128:8329</br>
addnode=45.77.204.241:8329</br>
addnode=45.32.79.36:8329</br>
addnode=108.45.164.191:8329</br>
addnode=45.76.197.245:8329</br>
addnode=176.36.217.81:8329</br>
addnode=83.217.206.155:8329</br>
addnode=80.209.230.77:8329</br>
addnode=190.57.229.138:8329</br>
addnode=213.32.53.138:8329</br>
addnode=127.0.0.33:8329</br>
addnode=142.44.194.217:8329</br>
addnode=54.37.117.111:8329</br>
addnode=217.182.209.170:8329</br>
addnode=107.173.222.3:8329</br>
addnode=176.36.89.120:8329</br>
addnode=193.41.78.188:8329</br>
addnode=80.209.234.228:8329</br>
addnode=45.76.83.166:8329</br>
addnode=54.37.117.110:8329</br>
addnode=76.8.60.209:8329</br>
addnode=76.8.60.250:8329</br>
  
<code>cd ~</code></br>
<code>./bitcloudd</code></br>
