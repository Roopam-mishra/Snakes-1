# Snakes

A simple game of snakes implemented in OpenCV and C++.

##  How to start

These instructions will get you a copy of the project up and running on your local machine for development purposes.  
More information can be found in the README-developers.txt file.

### Requirements
* OpenCV needs to be installed on the System. For installing OpenCV 2
1. Open Terminal on Ubuntu
2. Type following codes
```
sudo apt update
sudo apt install libopencv-dev python-opencv
```  
or follow the [guide](http://www.codebind.com/cpp-tutorial/install-opencv-ubuntu-cpp/)
* Install C++ (GCC recommended).

### Compilation
To compile the program use 
1. Open terminal on Ubuntu
2. Type following code
```
cd {snakes.cpp path}
g++ snakes.cpp -o output `pkg-config --cflags --libs opencv`
```
### Execution
To execute the compiled file type following code after compilation 
```
./output
```  
Or it can be run from /src file in these files

>I have added comments and walls in this code.if any comment is left out/wrong feel free to change it.

