# g++

> 编译 C++ 源文件。
> GCC (GNU Compiler Collection) 项目的组件之一。
> 更多信息：<https://gcc.gnu.org>.

- 将一组源文件编译为二进制文件：

`g++ {{源/文件/的路径1.cpp 源/文件/的路径2.cpp ...}} {{[-o|--output]}} {{可执行/文件/的路径}}`

- 打印所有错误和警告：

`g++ {{源/文件/的路径.cpp}} -Wall {{[-o|--output]}} {{output_executable}}`

- 打印普通警告和调试信息, 并在不影响调试的情况下优化：

`g++ {{源/文件/的路径.cpp}} -Wall {{[-g|--debug]}} -Og {{[-o|--output]}} {{可执行/文件/的路径}}`

- 指定 C++ 语言标准 (C++98/C++11/C++14/C++17)：

`g++ {{源/文件/的路径.cpp}} -std={{c++98|c++11|c++14|c++17}} {{[-o|--output]}} {{可执行/文件/的路径}}`

- 包含与源文件不在同一路径下的库：

`g++ {{源/文件/的路径.c}} {{[-o|--output]}} {{可执行/文件/的路径}} -I{{头/文件/的目录}} -L{{库/的目录}} -l{{库的名字}}`

- 将多个源文件编译并链接为可执行文件：

`g++ {{[-c|--compile]}} {{源/文件/的路径1.cpp 源/文件/的路径2.cpp ...}} && g++ {{[-o|--output]}} {{可执行/文件/的路径}} {{目标/文件/的路径1.o 目录/文件/的路径2.o ...}}`

- 优化编译后程序的性能：

`g++ {{源/文件/的路径.cpp}} -O{{1|2|3|fast}} {{[-o|--output]}} {{可执行/文件/的路径}}`

- 打印版本信息：

`g++ --version`
