# Brief #

This is a simple C++ application built with CMake and NDK.

## Buid ##

For x86 (also works for arm) building from command line:

``` bash
cmake -DCMAKE_TOOLCHAIN_FILE=$ANDROID_NDK/build/cmake/android.toolchain.cmake -DANDROID_ABI=x86
```

## Deploy ##

``` bash
adb push HelloWorld /data/local/tmp
adb shell /data/local/tmp/HelloWorld
```

## License ##

MIT
