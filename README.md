GNU Tool 示例

mac 环境下依次执行一下命令，即可自动生成configure脚本

```shell
aclocal
autoconf
automake --add-missing
glibtoolize
automake
./configure
make
./app
```

代码目录

```shell
bar.c
bar.h
foo.c
foo.h
common.h
main.c
```

其中

```
Makefile.am
configure.ac
```

需要编码配置

参考文章：

[http://leolovenet.com/downloads/files/autotools.pdf](http://leolovenet.com/downloads/files/autotools.pdf)

[http://blog.51cto.com/fyxfree/1536587](http://blog.51cto.com/fyxfree/1536587)

[https://geesun.github.io/posts/2015/02/autotool.html](https://geesun.github.io/posts/2015/02/autotool.html)

[https://blog.csdn.net/kevinhwm/article/details/8640762](https://blog.csdn.net/kevinhwm/article/details/8640762)

https://zhuanlan.zhihu.com/p/29910215