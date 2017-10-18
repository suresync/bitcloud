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
<code>apt-get --assume-yes install git unzip libboost-program-options-dev libboost-test-dev libdb4.8-dev libdb4.8++-dev libminiupnpc-dev libevent-dev libzmq3-dev libboost-filesystem1.58.0 libdb4.8++ libevent-2.0-5 libevent-core-2.0-5 libevent-pthreads-2.0-5 libminiupnpc10 libsodium18 libboost-system1.58.0 libboost-thread1.58.0 libevent-2.0-5 libzmq5 libboost-chrono1.58.0</code><br>
<code>wget https://github.com/LIMXTEC/Bitcloud/releases/download/v.2.0.0.3/Linux.2-0-0-3.tar.gz</code><br>
<code>tar -xvzf Linux.2-0-0-3.tar.gz</code><br>

Let's create the initial bitcloud.conf file!</br>

<code>mkdir ~/.bitcloud</code></br>
<code>cd ~/.bitcloud</code></br>

Create your bitcloud.conf file here and replace everything between {}.</br>

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
addnode=199.233.246.209:8329</br>
  
<code>cd ~</code></br>
<code>bitcloudd</code></br>
