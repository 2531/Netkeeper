# Netkeeper
湖北E信，登录程序，Python版Simple Netkeeper
# 源码基于 https://github.com/sunflyer/SimpleNetkeeper
代码没有完全转为Python版，运行时，调用了jar文件，执行加密

Python代码中有一部分涉及到long转int，在Python中整型是动态长度的，无法实现long转int，网上搜的很多转32位int方法，结果与Java中的结果不一致，需要手动转换，方法见https://github.com/1941474711/Netkeeper/blob/master/netkeeper/encrypt.py 中int32()方法

**代码已失效**