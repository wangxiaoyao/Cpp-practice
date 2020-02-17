# Cpp-practice

积累C++的一些练习题目。巩固C++各知识点

## IDE推荐

个人推荐C++语言的IDE分别是：

mac： Xcode

window：VS2019

编译器：clang/llvm

## 使用说明

鉴于每个人的IDE不同，以及上传整个项目文件过大的问题，故经考虑，仅上传练习的一个C++文件。

> 文件以 创立时间+练习题名组成，每一个文件里面均有一个README：题目的问题，解题思路以及重点。另外：main+数字.cpp：表示其他的解题方法。比如文件main1.cpp：表示第二种解题思路；文件main2.cpp：表示第三种解题思路。

1 使用IDE进行编译：

将 XXX.cpp 文件放入创立项目的，已有main函数，先将其改掉,或删除整个文件。将我的XXX.cpp放入，点击运行。

2 使用终端进行编译：

- 1 本电脑需先安装 GCC套件

```
# MAC系统只要安装了 Xcode就有了 clang。

# linux可以在终端输入以下命令进行安装GCC
sudo apt-get  install  build-essential
```

- 2 利用GCC进行编译

对clone的 XXX.c 文件进行如下操作：

```
gcc XXX.cpp -o "可执行程序名称"
```

点击生成的可执行程序，即可运行。