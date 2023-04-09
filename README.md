# linux

## 终端常用命令
    
```
sudo apt-get install g++
```   
安装 g++
```
ll
```
显示所在位置全部文件

## c++
```
g++ helloSLAM.cpp -c 
```
生成helloSLAM.o文件
```
g++ helloSLAM.o -o helloSLAM 
```
生成可执行程序
```
./helloSLAM  
```
运行
```    
g++ *.cpp  helloSLAM.cpp -o helloSLAM 
```
直接生成可执行文件

## CMake
```
cmake .
```
生成makefile
```
make
```
生成可执行文件
