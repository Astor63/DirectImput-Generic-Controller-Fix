## Generic Controller Not Detected Fix

Fix the __DirectImput Controller issue__ wich appears when you unable to play with the *Steam Controller API* by Valve (the main reason is because you are Offline).

### What do this fix?

Since *XInput* is the new standard game controller input on Windows, *DirectInput* can no longer be used with Universal Windows Platform software.

This fix convert *DirectInput* into *XInput*. *DirectInput* data is read and sent to a virtual *XInput* (Xbox 360 Controller) device.

### Supported Game Controllers:

- Any recent branded controllers others than *Microsoft Xbox 360/One controller*, (like *Sony PS4/PS3 Dualshock*, *Logitech*... or from any another brand) which use *DirectInput*. 
- Older branded gamepad (like *Sony PS2 Dualshock*, *Logitech Rumblepad*, etc...) which use *DirectInput*. 
- ... or generally any 3rd Party Controller (Unbranded USB Generic controller) which use *DirectInput*. 

### Installation:

1. Download the __[ControllerXImputFix.rar](https://github.com/Astor63/DirectImput-Generic-Controller-Fix/blob/master/ControllerXImputFix%20v1.0.0.rar)__ and open it on your PC.
2. Install the official  __[Xbox 360 Controller driver](http://www.microsoft.com/hardware/en-us/d/xbox-360-controller-for-windows)__.
2. Run ScpDriver.exe, and wait until it finishes to close it.
4. Copy *X360ce_x64* in the __same repertory__ from the [NameOfYourGame].exe 
5. Run *X360ce_x64* setup as Administrator to see how your joypad is mapped.
4. Run *XOutput* and set up your controller mappings identical to *X360ce_x64*.

That's it! You've done it! Congratulations on your effort to finish this journey :wink: 

__Note:__ 

1. If you need any other language than English or French for the official *Xbox 360 Controller driver*, simply download it on the __[Official Microsoft website](http://www.microsoft.com/hardware/en-us/d/xbox-360-controller-for-windows)__.
2. To keep the things easy, I have include __[TocaEdit Xbox 360 Controller Emulator 3.2.9.81](http://www.x360ce.com/)__ in the zip-file, but if you prefer, you can download the latest __[X360ce Digitally Signed Application v3.3.6.0](https://github.com/x360ce/x360ce)__.
	
### How to use this Fix:

1. Open *XOutput* and click *Start*
2. In your game controller menu, toggle __*OFF*__ the feature *Steam Controller Support* (must be done only the first time) 
3. Start your game.
4. Go have fun playing with your controller now!

### Changelog:

- v1.0.0, November 26, 2018
  - Initial public release.
 
### Fixed Games:

The fix solve the *DirectInput* issue , even when using  __[Xbox360ce](http://www.x360ce.com/)__ (Xbox 360 Controller Emulator), on the following 64bits games:

| Title                         | Publisher         | Platform       | Release               | 
| -------------                  | -------------     | -------------  |-------------          |
| Prey (since patch 1.05)        | Arkane Studios    | Steam          | May 2017                      |
| Prey: DLC Mooncrash            | Arkane Studios    | Steam          | June 2018                      |
| ReCore: Definitive Edition     | Microsoft Studios | Windows 10     | August 2017                      |
| ReCore: Definitive Edition     | Microsoft Studios | Steam          | September 2018                      |
| Shadow Of The Tomb Raider      | Square Enix       | Steam          | September 2018        |

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



