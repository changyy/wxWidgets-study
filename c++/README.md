## Study at OSX via MacPorts

### wxWidgets 2.9.5 C++11 supported

```
$ sudo port install wxWidgets30
$ sudo port uninstall wxWidgets30
$ sudo port install -s wxWidgets30 configure.cc=clang configure.cxx="clang++ -std=c++11 -stdlib=libc++" configure.cxxflags="-std=c++11 -stdlib=libc++ -O2" configure.objcxxflags="-std=c++11 -stdlib=libc++ -O2"
```

### Boost 1.54.0 C++11 supported

```
$ sudo port install boost
$ sudo port uninstall boost
$ sudo port install -s boost configure.cc=clang configure.cxx="clang++ -std=c++11 -stdlib=libc++" configure.cxxflags="-std=c++11 -stdlib=libc++ -O2" configure.objcxxflags="-std=c++11 -stdlib=libc++ -O2"
```

### Simple Hello World

http://www.wxwidgets.org/docs/tutorials/hello.htm

```
$ clang++ -std=c++11 -stdlib=libc++ main.cpp `wx-config --libs` `wx-config --cxxflags` -o helloworld
```
