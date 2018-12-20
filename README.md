# Visual Micro Arduino Project Structure with Compiler Error

This project fails at the compilation:
```
Compiling 'VMProject' for 'Arduino/Genuino Mega w/ ATmega2560 (Mega 2560)'
Build Folder: "file:///C:/Users/User/AppData/Local/Temp/VMBuilds/VMProject/mega_atmega2560/Release"
Summary: Header=1 Prototypes=1 Imports=1
Additional Defines: 
Architecture Tools: "file:///C:/Program%20Files%20(x86)/Arduino/hardware/tools/avr/bin/"
Api: 181209
Sketch Book: "file:///C:/Files/Work/arduino/Marlin"
Sketch Include Paths
Core Include Paths
Include Path "file:///C:/Program%20Files%20(x86)/Arduino/hardware/arduino/avr/cores/arduino"
Include Path "file:///C:/Program%20Files%20(x86)/Arduino/hardware/arduino/avr/variants/mega"
 
Building variant ...
 
  Using previously compiled variant
 
Building core ...
 
Building project code ...
"C:\Program Files (x86)\Arduino\hardware\tools\avr/bin/avr-g++" -c -g -Os -w -std=gnu++11 -fpermissive -fno-exceptions -ffunction-sections -fdata-sections -fno-threadsafe-statics -Wno-error=narrowing -MMD -flto -mmcu=atmega2560 -DF_CPU=16000000L -DARDUINO=10807 -DARDUINO_AVR_MEGA2560 -DARDUINO_ARCH_AVR -I"C:\Files\Work\arduino\vmicro-project-structure-compiler-error\VMProject" -I"C:\Program Files (x86)\Arduino\libraries" -I"c:\program files (x86)\microsoft visual studio\2017\community\common7\ide\extensions\zczdsw33.wxq\Micro Platforms\default\debuggers" -I"C:\Program Files (x86)\Arduino\hardware\arduino\avr\libraries" -I"C:\Files\Work\arduino\Marlin\libraries" -I"C:\Program Files (x86)\Arduino\hardware\arduino\avr\cores\arduino" -I"C:\Program Files (x86)\Arduino\hardware\arduino\avr\variants\mega" "C:\Users\User\AppData\Local\Temp\VMBuilds\VMProject\mega_atmega2560\Release\VMProject.cpp" -o "C:\Users\User\AppData\Local\Temp\VMBuilds\VMProject\mega_atmega2560\Release\VMProject.cpp.o"
Error compiling project sources
Build failed for project 'VMProject'
 
error*: C:\Users\User\AppData\Local\Temp\VMBuilds\VMProject\mega_atmega2560\Release\VMProject.cpp: No such file or directory
 
fatal error*: no input files
   compilation terminated
```
