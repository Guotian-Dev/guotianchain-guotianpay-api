# guotianchain-guotianpay-api

简介：
国天支付钱包API接口，与基于fabric的区块链网络


开发前准备
1、hyperledger-fabric开发环境
2、node.js开发环境，本项目开发时 node v8.11.1 npm 5.6.0
3、安装express

npm install express -g
npm install express-generator -g

开发过程
1. 采用 express 架构开发REST API程序，所以必须安装node.js和express，使用 express自动生成项目代码结构。

express guotianpay-api 

至此生成了项目基于express app的结构， 

guotianpay-api
├── README.md
├── app.js
├── bin
│   └── www
├── fabric
│   └── chaincode
├── package.json
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets
│       └── style.css
├── routes
│   ├── index.js
│   └── users.js
└── views
    ├── error.jade
    ├── index.jade
    └── layout.jade


2. 打开 package.json 添加 fabric-ca-client 和 fabric-client 依赖模块

"fabric-ca-client": "^1.0.0",
"fabric-client": "^1.0.0",

3. 在guotianpay-api目录安装依赖模块
npm install 安装依赖模块

npm start  启动程序

4. 创建fabric目录 该目录用于存放区块链网络相关文件







