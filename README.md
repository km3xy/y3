# y3

Termux 高级终端安装使用配置教程

画入新雪


pkg search <query>              搜索包

pkg install <package>           安装包

pkg uninstall <package>         卸载包

pkg reinstall <package>         重新安装包

pkg update                      更新源

pkg upgrade                     升级软件包

pkg list-all                    列出可供安装的所有包

pkg list-installed              列出已经安装的包

pkg shoe <package>              显示某个包的详细信息

pkg files <package>             显示某个包的相关文件夹路径


目录环境结构

~ > echo $HOME
/data/data/com.termux/files/home

 ~ > echo $PREFIX
/data/data/com.termux/files/usr

 ~ > echo $TMPPREFIX

/data/data/com.termux/files/usr/tmp/zsh
长期使用Linux的朋友可能会发现，

这个HOME路径看上去可能不太一样,为了方便,
Termux 提供了一个特殊的环境变量:PREFIX




