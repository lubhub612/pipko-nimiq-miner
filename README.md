# Pipco Nimiq Miner

This is Pipco Nimiq Miner, using self-designed Nimiq mining protocol. 

## Usage
``` bash
node index.js --address=<address> [--name=<name>] [--thread=<thread>] [--server=<server>] [--percent=<percent>] [--cpu=<cpu>]
```

## Building by Yourself

1. Install [Node.js](https://nodejs.org) v8.0.0 or higher.
2. On Ubuntu and Debian, install `git` and `build-essential`: `sudo apt-get install -y git build-essential`.
    - On other Linux systems, install `git`, `python2.7`, `make`, `gcc` and `gcc-c++`.
    - For MacOS or Windows, [check here for git](https://git-scm.com/downloads) and [here for compilation tools](https://github.com/nodejs/node-gyp#on-mac-os-x).
3. Install `yarn` globally: `sudo npm install -g yarn`.
4. Install `gulp` globally:  `yarn global add gulp`.
5. Clone this repository: `git clone https://github.com/lubhub612/pipco-nimiq-miner`.
6. Build the project: `cd pipco-nimiq-miner && yarn`.
7. Config `config.txt`, Run `node index.js`.
8. Install `pm2` globally: `yarn global add pm2`.
9. Run  `pm2 start index.js'.

---



