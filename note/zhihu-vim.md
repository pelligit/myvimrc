#

* <a href='https://www.zhihu.com/topic/19570193/top-answers'>用 Vim 写 Python 的最佳实践是什么？</a>
* <a href='https://www.zhihu.com/question/19655689/answer/12540976'>用Vim写python的最佳实践是什么？</a>

`Ctrl+[`和`Ctrl+c`和`ESC`是一个意思，都是在插入模式下回到普通模式下

vim关键字补全: `Ctrl+n`和`Ctrl+p`，当第二次输入某个单词时，输入单词的前几个字母，然后按`Ctrl+p`或者`Ctrl+n`就可以补全单词了

替换所有：`:%s/something/hello/g`将缓冲区里的所有的`something`替换成`hello`

替换所有：`:0,$s/something/hello/g`将缓冲区所有`something`替换成`hello`

替换所有：`:1,$s/something/hello/g`将缓冲区所有`something`替换成`hello`

切换目录：`:cd %:p:h`切换到当前编辑的文件所在目录
