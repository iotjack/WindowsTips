I have two big 4K monitors. But sometime I use only one monitor for extended amount of time. It makes no sense to leave the 2nd monitor on,  global warming, lifetime of the monitor etc. I was looking for a quick way to turn on/off the 2nd monitor. I think i have a good idea (should patent it :-), but it's not immediately available. 

Here's a simple way you can do it today -

(I was looking to write a litle program, but the program already exists in windows - it's displayswitch.exe.)

* To turn on 2nd monitor: %windir%\System32\DisplaySwitch.exe /extend 
* To turn off 2nd monitor: %windir%\System32\DisplaySwitch.exe /internal

You can make two shortcuts and ping them to taskbar. 

I'll probably make one small program to toggle between on/off, so use only one shortcut (with WindowStyle = ProcessWindowStyle.Hidden)
