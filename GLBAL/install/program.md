[<<< назад](../../README.md)
***
## Инсталяция программ


```bash
#CLion — IDE от JetBrains для С/С++
sudo snap install clion --classic

#Установить базовую поставку компилятора
sudo apt install build-essential
```

## Некоторые команды bash
```bash
#распаковать tar.gz архив
tar xvzf archive.tar.gz
```
```bash
#Установка библиотеки glut в ubuntu
sudo apt-get install freeglut3 freeglut3-dev libglew1.5 libglew1.5-dev libglu1-mesa libglu1-mesa-dev libgl1-mesa-glx libgl1-mesa-dev mesa-common-dev

#При компиляции использовать команду:
g++ -lglut -lGL -lGLU -lGLEW source.cpp
```
```c++
//Подключение заголовочного файла:
#include <GL/freeglut.h>
```
---
[<<< назад](../../README.md)
