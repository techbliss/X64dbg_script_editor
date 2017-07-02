[![](https://img.shields.io/badge/Twitter--blue.svg?maxAge=2592000)](https://twitter.com/zadow28) ![Python version](https://img.shields.io/badge/python-2.7-brightgreen.svg?maxAge=2592000) ![PyQ5t](https://img.shields.io/badge/PyQt5-5.6-orange.svg) [![](https://img.shields.io/badge/Donate-Paypal-blue.svg?maxAge=2592000)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8KXM6W2JVRUWL) [![](https://img.shields.io/badge/Latest-Release-red.svg?maxAge=2592000)](https://github.com/techbliss/X64dbg_script_editor/releases/latest)


x64dbg Script editor/ide

Python script runner and editor, for x64dbg python module.

[![](https://img.shields.io/badge/Xdbgpy-Link-blue.svg?maxAge=2592000)](https://github.com/x64dbg/x64dbg-python)


dependencies

[![](https://img.shields.io/badge/x64dbg_PyQt5-Link-blue.svg?maxAge=2592000)](https://github.com/x64dbg/PyQt5)

py2.7 Qt version 5.+ x86/64 machine


**v.2.0 changelog**

Fixed editor cant open twize( cant find editor). 

Added font box Getting.

ready for debugger(added breakpoint boxes in editor).

Fix for GUI None Responsive while debugging.

    import x64dbgpy 
    from x64dbgpy.pluginsdk.x64dbg import *
    x64dbgpy.pluginsdk.debug.Run()

fix 4k displays

Minor code fixes.

**v.2.0 changelog Releaser 02.07.2017**

Fix Qt app Crash ( Resolved buy [@bruce30262](https://github.com/bruce30262))

[on the latest release x64dbg ，lost response](https://github.com/techbliss/X64dbg_script_editor/issues/4)

Fix Reopen not found


**Build** the plugin was build with my x64py template

[![](https://img.shields.io/badge/x64dbgpy_Plugin-Template_Link-green.svg?maxAge=2592000)](https://github.com/techbliss/x64dbgpy-Plugin-Template)


This is made spesific for x64dbg python.
if you wanna run it strict from windows unquote the last few lines in Editor_x64dbg.py


```
 ###################################################
 #              Author Storm Shadow                #
 #                   Hotkeys                       #
 #         NewFile:            Ctrl+N              #
 #         OpenFile:           Ctrl+O              #
 #         SaveFile:           Ctrl+S              #
 #         RunScript:          Ctrl+E              #
 #         Undo:               Ctrl+Z              #
 #         Redo:               Ctrl+Y              #
 #         SelectALL:          Ctrl+A              #
 #         Paste:              Ctrl+V              #
 #         ResetFolding:       Ctrl+R              #
 #         CircleFolding:      Ctrl+C              #
 #         PlainFolding:       Ctrl+P              #
 #         x64dbg homepage:    Ctrl+W              #
 #         X64dbg Irc          Ctrl+I              #
 #         PythonGit:          Ctrl+G              #
 #         Author:             Ctrl+B              #
 #         Enable Reg:         Alt+E               #
 #         Disable Reg:        Alt+D               #
 #         Zoom +:             CTRL+SHIFT++        #
 #         Zoom -:             CTRL+SHIFT+-        #
 #         Profile Code        Ctrl+Shift+ E       #
 #         Font Box            Ctrl+F              #
 ###################################################
 #              X64dbg  python Editor              #
 ###################################################
```

**Without stylesheets**

![zkl62pf](https://cloud.githubusercontent.com/assets/3592375/8758623/7b971de4-2ce6-11e5-9662-171677651499.png)

**Here with custom stylesheets**

**Open in plugin menu**
![1](https://cloud.githubusercontent.com/assets/3592375/20305540/501913c8-ab36-11e6-8e9d-b07aa9ea19b6.png)

**Font box**
![2](https://cloud.githubusercontent.com/assets/3592375/20305539/5018cac6-ab36-11e6-9e75-b5e1c037ae27.png)

**Breakpoint boxes**
![bp](https://cloud.githubusercontent.com/assets/3592375/20305541/5019441a-ab36-11e6-9394-970447859d51.png)


**Donaters**

Many thanks to [![](https://img.shields.io/badge/Jetbrains-Company-blue.svg?maxAge=2592000)](https://www.jetbrains.com/) for donating a opensource licence.


![icon_upsource](https://cloud.githubusercontent.com/assets/3592375/20355736/9f4a6842-ac22-11e6-9901-9055ae8f1a69.png)![icon_pycharm](https://cloud.githubusercontent.com/assets/3592375/20355738/9f4f9bfa-ac22-11e6-8e1b-e49ba71b672c.png)

