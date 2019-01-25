### 缩写

**定义一个缩写**

`:ab asap as soon as possible`

`:ab www world wide web`

**使用缩写**

在插入模式下，输入：`asap `，最终会输出：`as soon as possible`

切记，后面紧跟一个空格

比如输入：`www `，最终会出现：`world wide web`

**不同的使用方式**

比如定义了`world wide web`的缩写是`www`

第一种使用方式：`www`和`ESC`

第二种使用方式：`www`和`Ctrl+[`

第三种使用方式：`www`和`Ctrl+]`

第四种使用方式：`www`和`<Space>`即空格

以上四种方式请自行体会

如果在输入时不想被缩写，输入完`www`后，输入`Ctrl+v`

**查看所有的缩写**

`:ab`

**清除所有的缩写**

`:abclear`

**命令模式下的缩写**

定义命令模式下的缩写

`:ca s set nu`
`:ca sn set nonu`

定义好后，在命令模式下，输入：

`:s`相当于输入：`:set nu`

`:sn`相当于输入：`:set none`

world wide web

world wide web

world wide web 
