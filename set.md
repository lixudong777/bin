## 做一些设置
* 在Linux 或 Mac 操作系统中，编辑文件 ~/.bashrc 或  ~/.zshrc
添加如下内容
```shell
export PATH="$HOME/Documents/code/bin":$PATH
alias lb='ls -AHhlLS'
alias subl='/var/lib/flatpak/app/com.sublimetext.three/x86_64/stable/cde62c80719a149869291cc78dd4f86cdfbade8c97c9f5cd0e473a14551d1c7a/files/extra/sublime_text/sublime_text'
```
然后执行
```shell
. ~/.bashrc
```