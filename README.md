# aardio-commonJS
在aardio中，一句话引用JS模块

# 基本用法
```javascript
    import web.script.commonJS;
    var require = web.script.commonJS();

    // 一句话引入JS模块
    var zxcvbn = require("zxcvbn")

    var password = "Kuda123!998&&^e"
    var result = zxcvbn(password)
    win.msgbox(password ++ " 的密码强度为 " ++ result.score);
```

# require的其他用法
```javascript
    // 内嵌代码
    var bigInt = require($"/res/js/BigInteger.min.js")

    // 本地文件
    var locale = require("C:/node/modules/locale.js")

    // 远程URL
    var sm3 = require("https://raw.fastgit.org/jiaxingzheng/JavaScript-SM3/master/sm3.js")

```