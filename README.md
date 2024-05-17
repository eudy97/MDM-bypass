# MDM-bypass

curl https://raw.githubusercontent.com/eudy97/MDM-bypass/main/MDM-bypass.sh -o MDM-bypass.sh && chmod +x ./MDM-bypass.sh && ./MDM-bypass.sh

# Prerequisites:

1. The device can't be bios-locked.
2. M-Series only.
3. Freshly installed MacOS Ventura/Sonoma. 

# Installation:

1. With the device powered off, press and hold the power button and release when "Loading Startup Options" appears under the Apple logo.
2. Connect to WiFi and Activate the Mac.
3. Open Safari and go back to this repo. (https://www.github.com/eudy97/mdm-bypass)
4. Copy this command:

   curl https://raw.githubusercontent.com/eudy97/MDM-bypass/main/MDM-bypass.sh -o MDM-bypass.sh && chmod +x ./MDM-bypass.sh && ./MDM-bypass.sh
   
6. Quit Safari. (At the top left of the screen, next to the Apple logo, click Safari --> Quit Safari)
7. Open the Terminal (Tools --> Terminal).
8. Paste the command in the terminal (Command + V) and press enter.
9. Type 1 and press Enter.
10. Type your full name or leave it empty and press enter.
11. Type your username or leave it empty and press enter. (Default username is Apple)
12. Type your password or leave it empty and press enter. (Default password is 1234)
13. Wait for it to complete and reboot. (Type "reboot" and press enter)
14. Profit.

# Troubleshooting 

1. Delete the drive
2. Erase the Mac
3. Reinstall macOS from recovery
4. At the "Select Your Country or Region" screen, press and hold the power button until the screen goes black to shut down.
5. Follow the installation instructions.

# curl: (4) A requested feature, protocol or option was not found built-in in this libcurl due to a build-time decision.

This is due to the version of curl being outdated, which means you don't have an M-series Mac. Therefore, this won't work for you.




