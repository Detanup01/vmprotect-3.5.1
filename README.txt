Debug Compilable version

need to install Qt5.12.12 to C:\Qt\Qt5_12_12\5.12.12\ dir and the installed version must be in C:\Qt\5.12.12\

you may need to install with mingw73_64 amd mingw73_32 (we using 64 to build regardless)

using windows SDK 10.0.19041.0 instead of 7.0

alo from v140_xp or v141 updated to v143 (win10 latest PlatfromToolset)

--------------

Select Debug and Mixed platform, and compile. (Not tested on other one)

You might need to copy files from your QT installed folder (_d.dll) to work.


--------------

Compiled version can be seen in Debug.7z
IF you have QT error just press ignore! it will continue to work!