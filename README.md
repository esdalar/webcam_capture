# Homework 1.2 # 

**CMake**

1- Download and install OpenCV for windows -I am still installing Ubuntu- [OpenCV for Windows](https://docs.opencv.org/master/d3/d52/tutorial_windows_install.html)

2- Do a fork and clone the repository [**"webcam_capture"**](https://github.com/esdalar/webcam_capture)

3- Download and install CMake -also for windows-[CMake for Windows](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)

4- Using CMake GUI select the repository folder as the source code folder because the CMakeList.txt is there.
   Create a new folder called "build" inside the repository folder and select it as the building directory.
   Click on "Configure" button twice and then "Generate" button.
   Finally, if everything is OK, click on the "Open project" button to open the Visual Studio -VS- solution of the source code.
   
5- On the "Solution Explorer" tap left click on "webcam_capture" and select "Build". After that VS should compile the program.

6- Go to the folder "build\Debug" and it should find the executable of the program that can be run with the "cmd".

gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica$ git clone https://github.com/esdalar/webcam_capture.git
Cloning into 'webcam_capture'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 65 (delta 0), reused 2 (delta 0), pack-reused 62
Unpacking objects: 100% (65/65), done.
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica$ cd /webcam_capture
bash: cd: /webcam_capture: No such file or directory
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica$ cd webcam_capture
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture$ git show  cmakelists
fatal: ambiguous argument 'cmakelists': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture$ cd  cmakelists
bash: cd: cmakelists: No such file or directory
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture$ git show CMakeLists.txt
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
-- Detecting CXX compile features - done
-- Found OpenCV: /usr (found version "3.2.0") 
-- Configuring done
-- Generating done
-- Build files have been written to: /home/gengiro/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture/build
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture/build$ make
Scanning dependencies of target webcam_capture
[ 50%] Building CXX object CMakeFiles/webcam_capture.dir/src/webcam_capture.cpp.o
[100%] Linking CXX executable webcam_capture
[100%] Built target webcam_capture
gengiro@gengiro-GL552VW:~/Desktop/Master Robotica/GitHub/Integracion robotica/webcam_capture/build$ ./webcam_capture
Opening video device 0
