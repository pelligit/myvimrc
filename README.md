### 相关链接

<ul>
<li><a href="https://vimawesome.com/">vim插件大全</a>  </li>
<li><a href="https://www.vim.org/">vim官方网站</a>  </li>
<li><a href="https://github.com/VundleVim/Vundle.vim">vim插件管理-vundle</a></li>
<li><a href="https://spacevim.org/cn/">space vim</a></li>
</ul>

### myvimrc

我的vim配置文件

### 使用vundle

插件管理工具，我这里使用的是vundle

```bash
# 进入用户的家目录
$ cd ~
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim 

# 如果之前有.vimrc文件，则备份
$ mv .vimrc .vimrc.backup

# 如果没有.vimrc文件，则新建一个
$ touch .vimrc

# 接下来编辑.vimrc文件
# .vimrc的内容就是此仓库里面的vimrc-v1等文件

# vim配置文件.vimrc编辑结束之后
# 打开vim
# 执行命令——:PluginInstall
# 等待插件下载完成
```

vim configuration

### 键盘映射工具

使用vim的话，保不齐哪里就用到了键盘映射，比如将CapsLock键和ESC键互换。

这里我是使用了一个键盘映射工具——KeybMap，是从互联网上下载的一个工具

为了便于以后使用，就直接打包在这个仓库里面了。

### 各版本说明

**vimrc-v1**

初始配置项

使用vundle，安装一些基本插件

* 使用monokai主题
* 使用文件浏览器插件
* 使用Markdown插件
* 使用git提示插件

**vimrc-v2**

* 将空格键映射为":"
* 新增ts插件
* 增加es语法插件
