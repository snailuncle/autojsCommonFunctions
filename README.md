# autojsCommonFunctions
# 导入模块
```
 //导入模块
 function 导入常用函数模块(){
  var url='https://raw.githubusercontent.com/snailuncle/autojsCommonFunctions/master/autojsCommonFunctions.js'
  var r = http.get(url)
  log("code = " + r.statusCode);
  var html=r.body.bytes()
  files.writeBytes('./autojsCommonFunctions.js',html)
  var common=require('./autojsCommonFunctions.js')
  return common
}
var common=导入常用函数模块()

```