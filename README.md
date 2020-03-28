# jsdom-ava-demo


首先安装 jsdom，这倒是很简单：

$ npm install --save jsdom
接着安装 ava，最好先全局安装一遍：

$ npm install -g ava

$ npm install --save ava
然后为了方便使用 npm test 命令，执行下面的命令：

$ ava --init

##配置  https://segmentfault.com/a/1190000005834279

```bash

$ npm install

# 测试串行
$ ava -v ./serial.js

# 测试并行
$ ava -v ./parallel.js

```
