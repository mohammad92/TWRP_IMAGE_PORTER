TWRP_THEME_PORTER
==================

Informal Update: I have been seeing on XDA and AF that I was mysteriously banished with no explanation. Seems my Port script has taken a big hit so I wanted to inform you all that I willingly chose to be less active on XDA and AF so that I may be with family more often than not. Thanks for understanding.

Please, should you have the time and decide to adjust the codes then I insist you send it my way for review and so I may even possibly merge to my repo. Thanks!

-- Happy Hunting!!

Written by Modding.MyMind/ModdingMyMind

XDA Member ©2015


- To use this Theme Porter, clone or download.

- Place TWRPPORTER to "/system/bin" on your Android device.

- chmod to 755 (rwxr-xr-x)

- Open up your terminal emulator and type then enter, TWRPPORTER, to run the script.

- Enter base device resolution as requested by the script.

- Enter port device resolution as requested by the script.

- Enter root directory to the theme as requested by the script.

- Install GM from the script itself if porting Images.

- Select between the available options given by the script.

- Enjoy!

NOTE: 

- Resizing TTF Fonts automatically is supported.
- Non TTF Font sizes must be handled manually (user discretion). 
- Porting the Keyboard Template is supported.


LOLLIPOP SUPPORT:

- The binary is not compiled as PIE.
- To allow NON-PIE binaries to work on Lollipop a simple hack is applied.
- The hack is a modified linker file which ignores conditional checks against binaries.
- By this method non-pie binaries are able to run on Lollipop.
- When you install GM for Lollipop then the original linker file is renamed to linker.mymind for safe keeping.
- The linker file can be found at /system/bin
- You must select the option to uninstall GM in order to uninstall the hack and restore your original linker file or manually handle them yourselves.
- If GM is already installed on your Lollipop device but the hack is not installed due to prior use before hack was introduced then uninstall and reinstall GM using the option specified for Lollipop users only.
- This hacking method is merely temporary until I or anyone else can compile a stable GM binary with PIE.
- If you use this hack for anything else other than what it is intended for then I take no responsibilities for your failure to follow simple instructions.
- This hack will not mess up your device should this ease your mind.