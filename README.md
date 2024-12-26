# Classic 7's FAQ
First, let me get out: Classic 7 0.5 will be in February. That's the only ETA for now

Links:
- [Official website](https://classic7.lol)
- [Official Discord](https://discord.com/invite/Hr7tC837ZW)
- [Archive.org mirror (has up to 0.3)](https://archive.org/details/classic7-0.1)

---
- "can i use classic 7 as a base for my project??"
   - Sure, as long as you credit me and all the other people in README on the desktop.
- "what version is classic 7 based on??"
   - Classic 7 is based on Windows 10 21H2, specifically IoT Enterprise LTSC.
- "does classic 7 work on windows xx?"
   - Classic 7 is an ISO, not something like a transformation pack. 
- "the setup failed to validate the product key!! what can i do??"
   - You're not supposed to use setup.exe on a pre-existing install. You are ment to flash the ISO to a USB drive using something like [Rufus](https://rufus.ie/en/) or if you prefer [Ventoy](https://www.ventoy.net/en/index.html) but do **NOT** use unetbootin or balenaEtcher, you will fail with a "No drives found" error in setup.
- "can i use an ms account???"
   - No, you cannot. You can use it for apps only but not as a user as the logon screen does not like it.
- "i need the ms store!!!"
   - You can use this [tool](https://github.com/kkkgo/LTSC-Add-MicrosoftStore). You can also try in PowerShell `wsreset -i` but support isn't guaranteed for both methods.
- "when im done with oobe i get other user!!!"
   - This is a known issue which the fix to is unknown. You can login normally using the username and password boxes shown on that screen and it should never show again.
- "when i open (link / app / file name here) i get the open with dialog and when i press ok it keeps reopening!!"
   - You will need to set the file type in settings, soon you can in Control Panel in 0.5
- "my start menu has a sad smile!!!"
   - Sign out.
- "i cant change my kb layout!!!"
   - That option isn't available for now. It will be added sooner or later.
- "my network folder doesn't work when i try to connect to my server!!"
   - The fix for this is [here](https://discord.com/channels/1208574240136233030/1300805238248443984/1300825643658776688) (you need to be in the discord server!)
- "i cant add a kb layout!!!"
   - Use `control 7nput.cpl` then select a keyboard layout there, the settings version is broken
- "the openwith window keeps spamming it's self!!!"
   - Known issue, fixed in 0.5 because of the new bug fixes in [OpenWithEx](https://github.com/aubymori/OpenWithEx)
- "the drivers don't auto install!"
  - Use [SDIO](https://www.glenn.delahoy.com/snappy-driver-installer-origin/) to get your drivers for you, Windows Update isn't included so that's why it doesn't auto install.
- "how do i get the 7 boot screen??"
   - Use [Boot8Plus](https://github.com/teknixstuff/misc-files/releases/download/Boot8Plus-v1.5.2/Boot8Plus.v1.5.2.zip) (you will need to disable secure boot!)
