# GamesoftACS
This is the Anti Cheat System for Knight Online Gamesoft version
Build the application on Debugx84

The folder has three libraries inside:
 - DetourAPI
 - Virtualizer
 - Windows SDK June 2010 (This library was deprecated and cannot be installed on modern systems like Windows 10, Windows 8, Windows 11, I have found a Legacy version which installation is problematic but we only need the `Lib` and `Include` folders. I have added those folders to project to make it easy to build for everyone)

The Project has relative paths to DetoursAPI, Virtualizer, WindowsSDK `include` and `lib` folders, so you dont need to change anything.

![image](https://user-images.githubusercontent.com/25039923/165550690-d9d0c82c-de8e-456e-a005-ef515f835db2.png)



**Note:**
When building, don't forget to change the IP addres on lines 394 and 410 from `Pearl Engine.cpp` file by your Server IP address.
You need to build in `Release x86` in order to get the `gamesoft.xasm` file with your own IP build in it.
You put the output `gamesoft.xasm` into the Client Files.
