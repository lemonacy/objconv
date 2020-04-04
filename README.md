# objconv
在MacOS下编译grub2.05需要objconv，brew下没有这个package，需要自行编译：
```shell
./build.sh
```
编程完成后会在当前目录生成objconv可执行文件。

复制objconv到PATH：
```shell
cp objconv /usr/local/bin
```
然后就可以开始编译grub了。
