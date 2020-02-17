# mac-lockscreen
<del> mac lock-screen app based on kaychain access. Useful when you use your mac "Docked" and do not have access to its own built-in keyboard.
Not mine but shamelessly copied from http://stackoverflow.com/questions/20319245/lock-screen-from-command-line-as-same-as-keychain-access-does-on-os-x and http://apple.stackexchange.com/questions/80058/lock-screen-command-one-liner/123738#123738 
all authors are thanked for the code. I stored it here just for ease of use and with some instructions.
</del>
<del>
The goal is just to be able to lock the screen in os x using hotkeys like in any other OS, say for example like linux + gnome.
To do this, compile the software using clang as follows: clang -framework Foundation -o lockscreen lockscreen.m
then you can create a "service" using automator as shown here: http://postimg.org/image/pwdyf3ti7/
</del>
<del>
save it give it a name and then you can assign to it a hotkey from System Preferences -> Keyboard -> Shortcuts like shown here: http://postimg.org/image/mynbtgn0x/
</del>

This is archived: I believe this is not needed anymore, since on catalina there are already hotkeys to lock the screen. 


Cheers
