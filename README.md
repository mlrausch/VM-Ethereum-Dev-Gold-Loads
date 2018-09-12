# VM-Ethereum-Dev-Gold-Loads

Ubuntu 18.04.1 LTS VM containing the following updates to the base install:

System Configuration:
- Memory: 2gb
- Dynamic HD: 40gb

Login:
- uid: ubuntu
- pwd: ubuntu

repositories:
Ethereum (add-apt-repository ppa:ethereum/ethereum)

packages (apt install):
- build-essential
- cmake
- curl
- ethereum
- gconf2
- gconf-service
- gconf-service-backend
- gconf2-common
- git
- libappindicator1
- libdb-dev
- libgconf-2-4
- libsodium-dev
- libtinfo-dev 
- openssh-server
- python
- python-dev
- solc
- sysvbanner
- unzip
- vim
- zlib1g-dev

Additional installed apps:
- Eth Console (npm install -g ethereum-console)
- Google Chrome
- Mist Browser (https://github.com/ethereum/mist/releases -- v0.11.0)
- Nodejs (https://nodejs.org/dist/v8.12.0/node-v8.12.0-linux-x64.tar.gz -- v8.12.0, includes NPM v6.4.1)
- Remix IDE (npm install -g remix-ide)
- Truffle (npm install -g truffle)
