# purity-dashboard-react-pro-issues

1. download / clone ```purity-dashboard-react-pro``` version ```2.0.1```
2. run ```npm i```
3. run ```npm start```

got this:

```log
> purity-dashboard-react-pro@2.0.1 start
> react-scripts start

i ｢wds｣: Project is running at http://192.168.1.39/
i ｢wds｣: webpack output is served from /purity-ui-dashboard-pro
i ｢wds｣: Content not from webpack is served from C:\dev\purity-ui-dashboard-pro-main\public
i ｢wds｣: 404s will fallback to /purity-ui-dashboard-pro/
Starting the development server...

Error: error:0308010C:digital envelope routines::unsupported
    at new Hash (node:internal/crypto/hash:71:19)
    at Object.createHash (node:crypto:133:10)
    at module.exports (C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\util\createHash.js:135:53)
    at NormalModule._initBuildHash (C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\NormalModule.js:417:16)
    at handleParseError (C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\NormalModule.js:471:10)
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\NormalModule.js:503:5
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\NormalModule.js:358:12
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\loader-runner\lib\LoaderRunner.js:373:3
    at iterateNormalLoaders (C:\dev\purity-ui-dashboard-pro-main\node_modules\loader-runner\lib\LoaderRunner.js:214:10)
    at iterateNormalLoaders (C:\dev\purity-ui-dashboard-pro-main\node_modules\loader-runner\lib\LoaderRunner.js:221:10)
C:\dev\purity-ui-dashboard-pro-main\node_modules\react-scripts\scripts\start.js:19
  throw err;
  ^

Error: error:0308010C:digital envelope routines::unsupported
    at new Hash (node:internal/crypto/hash:71:19)
    at Object.createHash (node:crypto:133:10)
    at module.exports (C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\util\createHash.js:135:53)
    at NormalModule._initBuildHash (C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\NormalModule.js:417:16)
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\NormalModule.js:452:10
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\webpack\lib\NormalModule.js:323:13
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\loader-runner\lib\LoaderRunner.js:367:11
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\loader-runner\lib\LoaderRunner.js:233:18
    at context.callback (C:\dev\purity-ui-dashboard-pro-main\node_modules\loader-runner\lib\LoaderRunner.js:111:13)
    at C:\dev\purity-ui-dashboard-pro-main\node_modules\babel-loader\lib\index.js:59:103 {
  opensslErrorStack: [ 'error:03000086:digital envelope routines::initialization error' ],
  library: 'digital envelope routines',
  reason: 'unsupported',
  code: 'ERR_OSSL_EVP_UNSUPPORTED'
}

Node.js v18.16.0

```