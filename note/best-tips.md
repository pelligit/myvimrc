### 最佳vim技巧

https://www.cnblogs.com/napoleon_liu/articles/1988535.html

彩蛋：

:h 42

:h holy-grail

:h!

文件浏览器：

:Sex  
:Ex  

:args 显示当前打开的文件  

切换目录：

:cd %:p:h

:lcd %:p:h

列出跳转的足迹：

:ju
:jumps

列出历史命令记录

:history


键盘映射：

map

缩写：

ab

列出寄存器：

:reg


录制到a：

qa

停止录制：

在录制过程中按`q`键停止录制

使用录制:

执行a中存储的指令

普通模式下按：`@a`


**加密**

输入密码后再确认密码，打开时会提示再次输入密码

:X

**多窗口编辑**

:split

:vsplit

:tabedit

:e

当打开多窗口时(使用split或者vsplit命令)，`Ctrl+w`然后再`_`，会最大化光标所在的窗口

当打开多窗口时(使用split或者vsplit命令)，`Ctrl+w`然后再`=`，会回归原来的样子

**以上两条请看下面的调整窗口尺寸**

* `Ctrl + w + =`: 将所有窗口调整至相同尺寸(平均划分)
* `Ctrl + w + _`: 将当前窗口的高度调整到最大
* `Ctrl + w + |`: 将当前窗口的宽度调整到最大
* `Ctrl + w + -`: 将当前窗口的高度减少，或者`:resize -4`将窗口高度减少4个单位
* `Ctrl + w + +`: 将当前窗口高度增减，或者`:resize +50`将窗口高度增加50个单位
* `Ctrl + w + <`: 将窗口宽度减少,或者`:vertical resize -50`
* `Ctrl + w + >`: 将窗口宽度增加，或者`:vertical resize +20`

* `Ctrl + w + q`: 离开当前窗口
* `Ctrl + w + c`: 关闭当前窗口
* `Ctrl + w + o`: 关闭当前窗口意外的所有窗口

**分页编辑**

* `tabnew filename`，打开分页并编辑新文件
* `tabedit filename`，打开文件
* `tabclose`关闭当前分页
* `tabonly`关闭其他所有分页
* `gt`切换分页
* `gT`切换分页
* `Ctrl + pagedown`
* `Ctrl + pageup`
