# 说明

原项目地址:[http://www.hugovil.com/projet.php?proj=emu8051](http://www.hugovil.com/projet.php?proj=emu8051)。

原README见[README](README)。

# 编译

## debian系操作系统

```bash
#安装编译工具及相应库
sudo apt-get install build-essential  automake autoconf libgtk2.0-dev libreadline-dev zlib*-dev pkg-config
#生成configure
./autogen.sh
#configure
./configure
#make
make
#安装
make install
```

