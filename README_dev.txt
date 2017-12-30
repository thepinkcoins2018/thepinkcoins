apt install aptitude
aptitude install  miniupnpc libminiupnpc-dev

apt-get install qt5-default qt5-qmake qtbase5-dev-tools qttools5-dev-tools build-essential libboost-dev libboost-system-dev libboost-filesystem-dev libboost-program-options-dev libboost-thread-dev libssl-dev libdb++-dev
cd /home/user/eclipse-workspace/thepinkcoin
cd src
make -f makefile.unix
chmod -R 777 /home/user/eclipse-workspace/thepinkcoin/src


touch .thepinkcoin/thepinkcoin.conf
vim .thepinkcoin/thepinkcoin.conf
added rpcuser & rpcpassword
start wallet
 ./thepinkcoind --daemon -txindex
// check processing
 pidof thepinkcoind
//





