# minar

#  Minar Criptominedas 

# Instalar xmrig, en Linux con CPU x64 bit

Instalar binario del respositorio oficial.:  
https://github.com/xmrig/xmrig/releases

cd / && mkdir /xmrig/

wget https://github.com/xmrig/xmrig/releases/download/v6.18.1/xmrig-6.18.1-linux-x64.tar.gz

tar xvzf xmrig-6.18.1-linux-x64.tar.gz

cd xmrig-6.18.1

./xmrig

# Condiguracion xmrig 

vim config.json

# Instalar xmrig, en Linux con CPU x32 bit

sudo apt update && sudo apt full-upgrade

sudo apt-get clean

sudo shutdown -r now (system will reboot)

sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev

git clone https://github.com/xmrig/xmrig.git

cd xmrig

mkdir build

cd build

cmake ..

make










