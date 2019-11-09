# Homework 1.2 # 

**CMake**

FOR WINDOWS

1- Download and install OpenCV for windows -I am still installing Ubuntu- [OpenCV for Windows](https://docs.opencv.org/master/d3/d52/tutorial_windows_install.html)

2- Do a fork and clone the repository [**"webcam_capture"**](https://github.com/esdalar/webcam_capture)

3- Download and install CMake -also for windows-[CMake for Windows](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)

4- Using CMake GUI select the repository folder as the source code folder because the CMakeList.txt is there.
   Create a new folder called "build" inside the repository folder and select it as the building directory.
   Click on "Configure" button twice and then "Generate" button.
   Finally, if everything is OK, click on the "Open project" button to open the Visual Studio -VS- solution of the source code.
   
5- On the "Solution Explorer" tap left click on "webcam_capture" and select "Build". After that VS should compile the program.

6- Go to the folder "build\Debug" and it should find the executable of the program that can be run with the "cmd".


FOR UBUNTU


1- Install OpenCV for ubuntu: 

´´´
sudo apt-get install libopencv-dev
´´´

2- Do a fork and clone the repository [**"webcam_capture"**](https://github.com/esdalar/webcam_capture)

3- Install CMake:

´´´
sudo apt-get install cmake
´´´


4- Create the project "build" inside the "webcam_capture" folder:

´´´
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture$ mkdir build
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture$ cd build
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture/build$ cmake ..
-- The C compiler identification is GNU 7.4.0
-- The CXX compiler identification is GNU 7.4.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
