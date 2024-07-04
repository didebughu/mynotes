https://ftp.gnu.org/gnu/gcc/

./contrib/download_prerequisites

./configure --prefix=/root --enable-checking=release --enable-languages=c,c++ --disable-multilib
make -j8 && make install


参考
https://cloud.tencent.com/developer/article/2091112
https://blog.csdn.net/weixin_43354152/article/details/129247408