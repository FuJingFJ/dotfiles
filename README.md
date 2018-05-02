
#### 1.拷贝配置文件到HOME目录下

```bash
cp vimrc ~/.vimrc
cp vimrc.plugins ~/.vimrc.plugins
```

#### 2.下载Vundle

```bash
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.Vim
```

#### 3.安装插件

```bash
vim -e -c BundleUpdate -c qa! 2>/dev/null
```
