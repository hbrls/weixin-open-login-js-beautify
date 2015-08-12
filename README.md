# weixin-open-login-js-beautify

人肉反编译 http://res.wx.qq.com/connect/zh_CN/htmledition/js/wxLogin.js

# last update

2015.JUN.23

# how to

1. 运行 `npm run keepup`，会同步最新的 sdk 文件
2. 然后执行 `git diff jsbeautifier.org.js`，即可查看这期间微信偷偷摸摸改了些什么
3. 然后到 `wxLogin.js` 把这些 `diff` 更新进去；如果尚未反编译，则直接覆盖；如果已经反编译，则需人肉升级

# MIT License
