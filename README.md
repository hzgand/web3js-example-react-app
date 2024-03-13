# Tutorial: Blockchain/Web3

## Table of Contents

Insert table of contents

## Background

### Web 1.0, 2.0, and Web3 [6]

Web 1.0 and Web 2.0 refer to different eras of websites. Web3 is the proposed era of websites that utilize blockchain technology.

#### Web 1.0: read

Web 1.0 describes the earliest form of the internet, known as the "read only web." At the time, the web existed to help people locate information. Users would search for data and could find it on web pages.

Web 1.0 pages are characterized by their static nature, frames and tables, HTML forms, and content served through the server's filesystem rather than a database. Static webpages simply displayed unchanging content and all the user could do is read it. 

#### Web 2.0: read-write

Web 2.0 is considered as the primary form of websites across the internet today. Web 2.0 is known as the "participative social web." These websites allow user interaction and users to create the content that is displayed on web pages.

In contrast to Web 1.0, the content displayed in Web 2.0 sites is often user generated. Forums, discussion boards, comment sections, image sharing, and meme sharing, are all aspects of Web 2.0 technology. This often involves usage of javascript and relational database technologies.

Characteristics of Web 2.0 are free information sorting, dynamic content that responds to user input, employs usage of APIs, and allows for user interaction. 

#### Web3: read-write-own

Web3 is a type of website built on the concepts of decentralization, openness, and user utility. Web3 involves moving away from centralized platforms like Google and towards centralized, anonymous platforms.

Characteristics of Web3 involve letting users interact and exchange information securely and conduct financial transactions without the need for a centralized authority or third party. This means users become owners of their data and they have control over their data.

### Blockchain [7]

A blockchain is a decentralized ledger of all transactions in a peer to peer network. This allows participants in the network to perform transactions between each other without needing a central authority. This technology can be used to facilitate money transfers, voting, and other issues.

#### Cryptocurrency

A cryptocurrency is simply a medium of exchange that is created and stored electronically on a blockchain. Cryptocurrencies employ cryptographic techniques to verify the transfer of funds and algorithms to control the creation of currency.

### Vulnerabilities [8] [9]

#### Web 2.0
Vulnerabilities included with Web 2.0 technologies are due to the fact there is a central trusted authority that facilitates transactions between users on websites. Once this authority is compromised, the data the authority was trusted with becomes leaked to the public.

Data leaks are an example of how Web 2.0 technologies can fail, as databases that store user info can become leaked onto the internet.

Other vulnerabilities of Web 2.0 include Cross site scripting (XSS), Cross site request forgery (CSRF), Phishing, and information leakage.

#### Web3

Web3 vulnerabilities include smart contract hacking. A study conducted in 2019 concluded Ethereum smart contracts put $4 million in Ether at risk.

### Defenses [7] [9]

The problems involved with Web 2.0 regarding a centralized authority are mitigated with Web3. Namely, data leakage, phishing, and information leakage. This is due to the fact Web3 technologies enable users to own their data, so they have control over who they give it out to.

## Setup

### Install node.js (>= version 14.0) [5]

- Prereq: `sudo apt install curl`
- Install node:

```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\
sudo apt-get install -y nodejs
```
- Check: `node --version`

### Install npm [1]

- Install: `sudo apt install npm`
- Check: `npm --version`

### Install yarn [2]

- Install: `sudo npm install --global yarn`
- Check: `yarn --version`

### Install ganache [4]

- Install: `sudo npm install ganache --global`

### Clone Web3 app demo [3]

- Clone: `git clone https://github.com/hzgand/web3js-example-react-app.git`
- Navigate to directory: `cd web3js-example-react-app/`

### Install dependencies

- Within directory: `yarn install`

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
6. https://www.simplilearn.com/what-is-web-1-0-web-2-0-and-web-3-0-with-their-difference-article
7. https://www.pwc.com/us/en/industries/financial-services/fintech/bitcoin-blockchain-cryptocurrency.html
8. https://nsi.org/ReferenceLibrary/766.pdf
9. https://www.cloudflare.com/the-net/web3-security/

[1]: https://monovm.com/blog/install-npm-on-ubuntu/#Install-Node.js-and-npm-from-the-Ubuntu
[2]: https://classic.yarnpkg.com/lang/en/docs/install/
[3]: https://github.com/ChainSafe/web3js-example-react-app
[4]: https://inthediary.medium.com/installing-ganache-5f6a2b22df97
[5]: https://github.com/nodesource/distributions
[6]: https://www.simplilearn.com/what-is-web-1-0-web-2-0-and-web-3-0-with-their-difference-article
[7]: https://www.pwc.com/us/en/industries/financial-services/fintech/bitcoin-blockchain-cryptocurrency.html
[8]: https://nsi.org/ReferenceLibrary/766.pdf
[9]: https://www.cloudflare.com/the-net/web3-security/