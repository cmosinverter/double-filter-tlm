## Double Filter Using TLM P2P


This is the project that implements ee6470 homework 2, (40 pt) Median and mean filters with TLM interface

## Block Diagram
![image](https://i.imgur.com/TBIDn08.jpg)

## Usage
1. Clone the file to ./ee6470 folder (Git Bash)
```properties
git clone https://github.com/cmosinverter/ee6470_hw2_q1.git
```
2. Open Windows Powershell
```properties
docker run -h ubuntu --rm --cap-add SYS_ADMIN -it -v "C:\\Users\\<Your Username>:/home/user" ee6470/ubuntu-ee6470:latest
```
3. Login
```properties
/usr/local/bin/entrypoint.sh
```
4. Move to build directory
```properties
cd ~/ee6470/ee6470_hw2_q1/build
```
5. Run the program using Cmake
```properties
make run
```