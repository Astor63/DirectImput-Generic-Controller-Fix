## Generic Controller Not Detected Fix

Fix the __DirectImput Controller issue__ wich appears when you unable to play with the *Steam Controller API* by Valve (the main reason is because you are Offline).

### What to this fix?

Since *XInput* is the new standard game controller input on Windows, *DirectInput* can no longer be used with Universal Windows Platform software.

This fix convert *DirectInput* into *XInput*. *DirectInput* data is read and sent to a virtual *XInput* (Xbox 360 Controller) device.

### Supported Game Controllers:

- Any branded controllers others than *Microsoft Xbox 360/One controller*, (like *Sony PS4 Dualshock controller*, *Logitech Controller* or from any another brand which use *DirectInput*) 
- Older branded gamepad (like Sony PS2 controller which use *DirectInput*, etc...) 
- ... or generally any USB Generic (unbranded) controller which use *DirectInput*. 

### Installation:

1. Download the __[ControllerXImputFix.rar](https://github.com/Astor63/DirectImput-Generic-Controller-Fix/blob/master/ControllerXImputFix%20v1.0.0.rar)__ and open it on your PC.
2. Install the official *Xbox 360 Controller driver*.
2. Run ScpDriver.exe, and wait until it finishes to close it
4. Copy *X360ce 64* in the same repertory from the [NameOfYourGame].exe 
5. Run *X360ce 64* setup as Administrator.
4. Run *XOutput* and set up your controller mappings identical to *X360ce 64*

That's all, installation process done!

__Note:__ If you need any other language than English or French for the official *Xbox 360 Controller driver*, simply download it on the __[Official Microsoft website](http://www.microsoft.com/hardware/en-us/d/xbox-360-controller-for-windows).
	
### How to use this Fix:

1. Open *XOutput* and click *Start*
2. In your game controller menu, toggle __*OFF*__ the feature *Steam Controller Support* 
3. Start your game
4. Enjoy playing with your controller.

### Changelog:

- v1.0.0, November 26, 2018
  - Initial public release.
 
### Compatibility:

- Prey - 2017 (since patch 1.05)
- Prey: DLC Mooncrash
- Shadow Of The Tomb Raider 

### Known Issues:

There are currently no known issues with using the fix.

### To do:

- [ ] Well... it seems to work correctly, so nothing I guess?

### Disclaimer:

All files and content provided here were written by me (Astor), unless stated otherwise.

- They are free for personal use. You may use this mod in any other way, as long as you give me proper credit. I would appreciate that you'll letting me know about it, and at least, provide a link to [Github.com/Astor63/DirectImput-Generic-Controller-Fix](https://github.com/Astor63/DirectImput-Generic-Controller-Fix).

- Ask me for permission first if you wish to use larger portions of this code, make a modified/improved version, and don't forget to provide credit.

- Do not re-upload this mod or any of my mods anywhere without my explicit permission... ANYWHERE!

* * * * *



