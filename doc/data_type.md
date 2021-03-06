# Python3 数据类型

## 整数
1.常规整数也就是十进制的,例如:`1`, `100`, `-100`, `0`, 等等  
2.十六进制,十六进制用`0x`前缀和0-9,a-f表示,例如:`0xff00`，`0xa5b4c3d2`，等等  
3.Python的整数没有大小限制  

## 浮点数
1.小数,例如:`1.23`, `3.14`, `-9.01`, 等等  
2.科学计数法,10用e替代,例如:1.23x10^9就是`1.23e9`,或者`12.3e8`,0.000012可以写成`1.2e-5`,等等  
3.Python的浮点数也没有大小限制，但是超出一定范围就直接表示为`inf`（无限大）  

## 字符串
1.字符串是以单引号`'`或双引号`"`括起来的任意文本,比如`'abc'`,`"xyz"`等等  
2.用`r''`表示`''`内部的字符串默认不转义  
3.用`'''...'''`的格式表示多行内容  
4.用`r'''...'''`的格式表示多行不转义内容  

### 字符串格式化
`%`运算符就是用来格式化字符串的。在字符串内部，`%s`表示用字符串替换，`%d`表示用整数替换，有几个`%?`占位符，后面就跟几个变量或者值，顺序要对应好。如果只有一个`%?`，括号可以省略  
常见的占位符有：  
|占位符|替换内容|
|----|----|
|%d|整数|
|%f|浮点数|
|%s|字符串|
|%x|十六进制整数|

## 布尔值
1.一个布尔值只有`True`、`False`两种值（请注意大小写）  
2.`and`运算是与运算，只有所有都为`True`，`and`运算结果才是`True`  
3.`or`运算是或运算，只要其中有一个为`True`，`or`运算结果就是`True`  
4.`not`运算是非运算，它是一个单目运算符，把`True`变成`False`，`False`变成`True`  
5.布尔值经常用在条件判断中  

## 空值  
1.空值是Python里一个特殊的值，用`None`表示。`None`不能理解为`0`，因为`0`是有意义的，而`None`是一个特殊的空值  

## 