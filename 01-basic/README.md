## Steps

```
(base) ➜  01-basic git:(main) mkdir build && cd build
(base) ➜  build git:(main) cmake ..
-- The C compiler identification is GNU 9.3.0
-- The CXX compiler identification is GNU 9.3.0
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Check for working C compiler: /usr/bin/cc - skipped
-- Detecting C compile features
-- Detecting C compile features - done
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Check for working CXX compiler: /usr/bin/c++ - skipped
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Configuring done
-- Generating done
-- Build files have been written to: /home/abhishek/Desktop/cmake-basics/01-basic/build
(base) ➜  build git:(main) make
[ 50%] Building CXX object CMakeFiles/01_basic.dir/main.cpp.o
[100%] Linking CXX executable 01_basic
[100%] Built target 01_basic
(base) ➜  build git:(main) ./01_basic
Hello, from CMake!
```
