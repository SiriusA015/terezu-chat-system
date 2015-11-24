<p align="center">
    <a href="https://github.com/SiriusA015/terezu-chat-system">
        <img src="https://img.shields.io/github/stars/SiriusA015/socket-io-typescript-chat.svg?style=social&label=Star" alt="GitHub stars">
    </a>
    <a href="https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fluixaviles%2Fsocket-io-typescript-chat&via=luixaviles&text=Take%20a%20look%20this%20%23TypeScript%20chat%20project%20using%20%23Node%20and%20%23Angular%20Material">
        <img src="https://img.shields.io/twitter/url/https/github.com/luixaviles/socket-io-typescript-chat.svg?style=social" alt="Tweet">
    </a>
</p>

A Socket.io Chat Example Using TypeScript
=========================================

This repository contains server & client side code using `TypeScript` language

# Support this project
- Star GitHub repository :star:
- Create pull requests, submit bugs or suggest new features
- Follow updates on [Twitter](https://twitter.com/SiriusA015) or [Github](https://github.com/SiriusA015)

![](https://SiriusA015.com/assets/images/posts/typescript-chat/typescript-chat.gif?raw=true)

# Running Server and Client locally
## Prerequisites

First, ensure you have the following installed:

1. NodeJS - Download and Install latest version of Node: [NodeJS](https://nodejs.org)
2. Git - Download and Install [Git](https://git-scm.com)
3. Angular CLI - Install Command Line Interface for Angular [https://cli.angular.io/](https://cli.angular.io/)

After that, use `Git bash` to run all commands if you are on Windows platform.

## Clone repository

In order to start the project use:

```bash
$ git clone https://github.com/SiriusA015/terezu-chat-system.git
$ cd terezu-chat-system.git
```

## Run Server

To run server locally, just install dependencies and run `gulp` task to create a build:

```bash
$ cd server
$ npm install -g gulp-cli
$ npm install
$ gulp build
$ npm start
```

The `socket.io` server will be running on port `8080`

When you run `npm start`, this folder leverages [nodemon](https://nodemon.io/) which will automatically reload the server after you make a change and save your Typescript file. Along with nodemon, there is also a `gulp watch` task that you can run to reload the files but it's not necessary and is provided merely as a teaching alternative. 

## Run Angular Client

Open other command line window and run following commands:

```bash
$ cd client
$ npm install
$ ng serve
```

Now open your browser in following URL: [http://localhost:4200](http://localhost:4200/)

# Server Deployment

Feel free to update that page and Readme if you add any other platform for deployment!

# Forks
The Open Source community is awesome! If you're working in a fork with other tech stack, please add the reference of your project here:

| Features                                  | Author                        | Status    |
|-------------------------------------------|-------------------------------|-----------|
| [React + TypeScript + Material-UI client]   | [Kvision](https://github.com/SiriusA015)   | In Progress   |


# Contribution
Contributions are greatly appreciated. You can contribute by adding `i18n` support with your language, the testing section or any other feature.

# Contributors
[<img alt="Kvision" src="https://avatars.githubusercontent.com/u/122122450?v=4&s=117" width="117">](https://github.com/SriusA015) | [<img alt="hughanderson4" src="https://avatars2.githubusercontent.com/u/2387520?v=4&s=117" width="117">](https://github.com/hughanderson4) | [<img alt="ultrarunner" src="https://avatars2.githubusercontent.com/u/1048799?v=4&s=117" width="117">](https://github.com/ultrarunner) | [<img alt="theIDinside" src="https://avatars2.githubusercontent.com/u/25328813?v=4&s=117" width="117">](https://github.com/theIDinside) | [<img alt="carmius" src="https://avatars2.githubusercontent.com/u/16904101?v=4&s=117" width="117">](https://github.com/carmius) | [<img alt="Hellmy" src="https://avatars2.githubusercontent.com/u/2045678?v=4&s=117" width="117">](https://github.com/Hellmy) | 
:---: |:---: |:---: |:---: |:---: |:---: |
[Kvision](https://github.com/SiriusA015) |[hughanderson4](https://github.com/hughanderson4) |[ultrarunner](https://github.com/ultrarunner) |[theIDinside](https://github.com/theIDinside) |[carmius](https://github.com/carmius) |[Hellmy](https://github.com/Hellmy) |[headwinds](https://github.com/headwinds) |


## License

MIT
