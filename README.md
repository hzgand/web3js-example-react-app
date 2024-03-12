# Tutorial: Blockchain/Web3

## Table of Contents

Insert table of contents

## Background

Insert background

## Setup

### Install node.js (>= version 14.0) [5]
* Prereq: `sudo apt install curl`
* Install node:
```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\
sudo apt-get install -y nodejs
```

### Install npm [1]
* Install: `sudo apt install npm`
* Check: `npm --version`

### Install yarn [2]
* Install: `sudo npm install --global yarn`
* Check: `yarn --version`

### Install ganache [4]
* Install: `sudo npm install ganache --global`

### Clone Web3 app demo [3]
* Clone: `git clone https://github.com/hzgand/web3js-example-react-app.git`
* Navigate to directory: `cd web3js-example-react-app/`

### Install dependencies
* Within directory: `yarn install`

## Demo

### Run ganache
`ganache`

### Run app
`yarn start`

## References
1. https://monovm.com/blog/install-npm-on-ubuntu/#Install-Node.js-and-npm-from-the-Ubuntu
2. https://classic.yarnpkg.com/lang/en/docs/install/
3. forked from https://github.com/ChainSafe/web3js-example-react-app
4. https://inthediary.medium.com/installing-ganache-5f6a2b22df97
5. https://github.com/nodesource/distributions

[1]: https://monovm.com/blog/install-npm-on-ubuntu/#Install-Node.js-and-npm-from-the-Ubuntu
[2]: https://classic.yarnpkg.com/lang/en/docs/install/
[3]: https://github.com/ChainSafe/web3js-example-react-app
[4]: https://inthediary.medium.com/installing-ganache-5f6a2b22df97
[5]: https://github.com/nodesource/distributions