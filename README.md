# AwayNickIsCool
AwayNickIsCool is just a redistributed version of the origin awaynick by ZNC. ZNC has retired this module as they find that it impolite and can cause a lot of problems. If you're like me and you still want to use this module follow the instructions below.

Copy or clone the awaynickiscool.cpp file compile the file with this command:
```znc-buildmod awaynickiscool.cpp```

Note that this will only work on a system that has ZNC installed. If this is not the case but you still want to build the module, I suggest that you take a look at the [ZNC wiki](http://wiki.znc.in/Compiling_modules) for compiling ZNC modules.

If everything worked fine a file called ```awaynickiscool.so``` should have been created in the same folder. Copy this file to the ```/.znc/modules folder```.

When the file is installed go into your irc client and type ```/znc loadmod awaynickiscool``` or ```/msg *status loadmod awaynickiscool```. The status will confirm if the module is installed and you will be able to see an awaynickiscool module in your webadmin.

Give the module in the webadmin the nick you want to have when you are away and everything should be setup.

If you want to disable the simple_away (the lame replacement of simple_away by ZNC) you type ```/znc unloadmod simple_away``` or ```/msg *status unloadmod awaynickiscool``` and the module will be unloaded.

Note: The awaynickiscool module will have to be rebuild everytime you update your ZNC version. You do this the same way as the first time, so you can just follow the steps from above again.
