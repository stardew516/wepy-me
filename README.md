# wepy-me

# 小程序api: https://mp.weixin.qq.com/debug/wxadoc/dev/api/
# wepy手册: https://tencent.github.io/wepy/document.html#/?id=%e5%be%ae%e4%bf%a1%e5%b0%8f%e7%a8%8b%e5%ba%8f%e7%bb%84%e4%bb
%b6%e5%8c%96%e5%bc%80%e5%8f%91%e6%a1%86%e6%9e%b6wepy%e5%ae%98%e6%96%b9%e6%96%87%e6%a1%a3


1. 安装wepy
npm install wepy-cli -g
2. 初始化项目
wepy init standard wepy-me(项目名不能有大写字母)
3. 安装依赖
npm install
4. 实时监听开发
npm run dev


error:
1. VM283:1 thirdScriptError
    sdk uncaught third Error
    Cannot set property 'Promise' of undefined
    TypeError: Cannot set property 'Promise' of undefined
解决: 微信开发者工具->设置->项目设置->不勾选es6转es5


2. _wepylogs.js:2 CLI报错：Error: 找不到模块: module-a
   被依赖于: /Users/weilu/Desktop/weilu/code/wepy-me/src/pages/index.wpy。
   请尝试手动执行 npm install module-a 进行安装。
       at Error (native)
       at /usr/local/lib/node_modules/wepy-cli/lib/compile-script.js:98:31
       at RegExp.[Symbol.replace] (native)
       at RegExp.[Symbol.replace] (native)
       at String.replace (native)
       at Object.resolveDeps (/usr/local/lib/node_modules/wepy-cli/lib/compile-script.js:46:21)
       at /usr/local/lib/node_modules/wepy-cli/lib/compile-script.js:270:27
       at process._tickCallback (internal/process/next_tick.js:109:7)
   console.error
   (anonymous) @ _wepylogs.js:2
   require @ WAService.js:18
   (anonymous) @ WAService.js:18
   (anonymous) @ app.js:126
   require @ WAService.js:18
   (anonymous) @ appservice:1136

