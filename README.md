# NoGo不围棋项目说明

本项目两人合作完成，具体可见结题报告。如有意见建议，欢迎批评指正。

## 源码
程序共有两个版本的源代码。
### 终端交互源代码.cpp
顾名思义，主要是欧阳霄宇同学在macOS端编写的，因此Windows端可能运行时会出现bug；比如将代码
```cpp
system("clear");
```
改成
```cpp
system("cls");
```
同时由于emoji在Windows终端可能无法显示，黑棋白棋和禁止点的符号可能需要_用别的符号_替代。
### 图形界面交互源代码.cpp
顾名思义，是鼠标交互界面，主要是李傲骋同学在windows端编写的（负极大值算法和估值函数除外），macOS端运行时因不兼容graphics包无法运行。

## 报告
### **结题报告.pdf**
内含对开发过程和细节的详细介绍。
### 报告源码
含原图及tex。

## 程序
### mac终端交互程序
macOS上用终端打开可直接运行。
