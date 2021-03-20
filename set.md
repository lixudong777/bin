## 做一些设置
* 在Linux 或 Mac 操作系统中，编辑文件 ~/.bashrc 或  ~/.zshrc
添加如下内容
```shell
export PS1="\[\e[32m\][\[\e[m\]\[\e[31m\]\u\[\e[m\]\[\e[33m\]@\[\e[m\]\[\e[32m\]\h\[\e[m\]:\[\e[36m\]\w\[\e[m\]\[\e[32m\]]\[\e[m\]$ "
export PATH="$HOME/Documents/code/bin":$PATH
alias la='ls -lAh --color=auto'
alias lb='ls -AHShlb --color=auto'
```
然后执行
```shell
. ~/.bashrc
```