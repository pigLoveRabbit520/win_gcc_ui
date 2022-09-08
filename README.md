# Prerequisites
* [MinGW-w64](https://www.mingw-w64.org/)
* [CMake](https://cmake.org/)

# 编译
```bash
cd build
cmake -G "MinGW Makefiles" ..
make
```


# 源码
代码来自[simple_window](http://www.winprog.org/tutorial/simple_window.html)

# gcc优化参数
Flag,Description
-g,Produced debugging information in the operating system’s native format.
-Os,Optimize for size.
-O2,GCC performs nearly all supported optimizations that do not involve a space-speed trade-off.
-O3,Turns on all optimizations specified by -O2 in addition to other various optimization options.
-DNDEBUG,Disables assertions for GCC and Clang.