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
# .vimrc的内容就是此仓库里面的vimrc-v1等文件里的内容
$ cp -f vimrc-v1 ~/.vimrc

# vim配置文件.vimrc编辑结束之后
# 打开vim
# 执行命令——:PluginInstall
# 等待插件下载完成
```

vim configuration

### 键盘映射工具

使用vim的话，保不齐哪里就用到了键盘映射，比如将CapsLock键和ESC键互换。

这里我是使用了一个键盘映射工具——KeybMap，是从互联网上下载的一个工具

z了便于以后使用，就直接打包在这个仓库里面了。
