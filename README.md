# cmake-visualstudio-quickstart
[https://github.com/hailiang-wang/cmake-visualstudio-quickstart](https://github.com/hailiang-wang/cmake-visualstudio-quickstart)


## Deps

* Windows11 OR Windows10
* Visual Studio 2022 Community
* Desktop Development with C++ Workload

![](./assets/screenshot_20250113083609.png)

![](./assets/screenshot_20250113083708.png)

## Configure

Set `Path`

```
CMAKE_HOME=C:\devel\Microsoft\VisualStudio\ide2022community\Common7\IDE\CommonExtensions\Microsoft\CMake\CMake
Path=%CMAKE_HOME%\bin ...
```

![](./assets/screenshot_20250113083418.png)

## Build with CLI

```
git clone git@github.com:hailiang-wang/cmake-visualstudio-quickstart.git
cd cmake-visualstudio-quickstart
mkdir out
cd out
cmake ..
cmake build
```