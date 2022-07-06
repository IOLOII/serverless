### 起步：
npm install -g serverless

### win环境
解决
// ERROR: 'NODE_ENV' 不是内部或外部命令
npm install -g cross-env

"dev": "NODE_ENV=development node app.js" 修改为
"dev": "cross-env NODE_ENV=development node app.js"

### 云函数
https://cloud.tencent.com/document/product/583/44753

### 快速创建应用模板
https://cloud.tencent.com/document/product/1154/50933