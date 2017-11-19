# DApp

[![Join the chat at https://gitter.im/DAppHackathon/Lobby](https://badges.gitter.im/DAppHackathon/Lobby.svg)](https://gitter.im/DAppHackathon/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Before starting the project, we have to prepare platforms and dependencies as the below.
## Prerequisites
- MetaMask (Chrome Extension)
- NodeJS 8+
- Git
- IDE (Sublime, Visual Studio, Vim ...)

## Installing MetaMask Extension
To install Metamask, you just need to open your Chrome Browser and go to link: MetaMask
And click Add To Chrome button
##Installing Git, NodeJS 8+
### Windows
We use Chocolaty to install NodeJS and Git. For installing Choco, please see: https://chocolatey.org/install#install-with-cmdexe 
Install NodeJs:
```
$ choco install nodejs
```


Install Git
```
$ choco install git
```


### OSX
Install NodeJs:
```
$ brew install node
```

Install Git:
```
$ brew install git
```


### Linux (Debian/Ubuntu)
Install NodeJs:
$ curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
$ apt-get install -y nodejs
$ npm install -g npm@latest


Install Git:
```
$ apt-get install git
```
## Setup the project
As you know, Ethereum Smart Contract use Solidity programing language. So we have to install the compiler called Solc.
Open your terminal, and install Solc via NPM:
```
$ npm install -g solc
```


We need a Ethereum Node for the deployment and test. So we can use TestRPC to emulate Ethereum.
```
$ npm install -g ethereumjs-testrpc
```


We use truffle to build/deploy the project. So we Install Truffle via NPM: 
```
$ npm install -g truffle
```

## Init Project
Run command:
```
truffle unbox webpack
```

## Deploy Smart Contract
Run command
```
truffle deploy --reset
```

## Run project
```
npm run dev
```

## Test
localhost:8080

