DEMO
===========================
#### Describution

Eg. This repository contains PyTorch implementations of deep reinforcement learning algorithms and environments.
Eg. keras-rl implements some state-of-the art deep reinforcement learning algorithms in Python and seamlessly integrates with the deep learning library Keras.

Furthermore, keras-rl works with OpenAI Gym out of the box. This means that evaluating and playing around with different algorithms is easy.

Of course you can extend keras-rl according to your own needs. You can use built-in Keras callbacks and metrics or define your own. Even more so, it is easy to implement your own environments and even algorithms by simply extending some simple abstract classes. Documentation is available online.

#### Dependency
node v0.10.28+
redIs ~

#### Installation
1. 添加系统环境变量
    export $PORTAL_VERSION="production" // production, test, dev


2. npm install  //安装node运行环境

3. gulp build   //前端编译

4. 启动两个配置(已forever为例)
    eg: forever start app-service.js
        forever start logger-service.js
#### Usage/Example


#### File Tree
├── Readme.md                   // help  
├── app                         // 应用  
├── config                      // 配置  
│   ├── default.json  
│   ├── dev.json                // 开发环境  
│   ├── experiment.json         // 实验  
│   ├── index.js                // 配置控制  
│   ├── local.json              // 本地  
│   ├── production.json         // 生产环境  
│   └── test.json               // 测试环境  
├── data  
├── doc                         // 文档  
├── environment  
├── gulpfile.js  
├── locales   
├── logger-service.js           // 启动日志配置  
├── node_modules  
├── package.json  
├── app-service.js              // 启动应用配置  
├── static                      // web静态资源加载  
│   └── initjson  
│       └── config.js         // 提供给前端的配置  
├── test  
├── test-service.js  
└── tools  



#### V1.0.0 Update log
1. New Func    aaaaaaaaa
2. New Func     bbbbbbbbb
3. New Func     ccccccccc
4. New Func     ddddddddd

#### Reference
#### Contributing
#### Copyright/Licence