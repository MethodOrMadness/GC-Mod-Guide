---
layout: single
title: "PSOLoad"
---
## Required
* Official BBA(BroadBand Adapter)
* PSO Disc (Episode "1&2" only, not 1&2plus, not 3)
* PC([Windows](/files/psoload/PSOLoad_Win.zip), [mac OSX](/files/psoload/PSOLoad_Mac.zip), or [linux](/files/psoload/PSOLoad_Linux.zip)) Running the PSOLoad exploit server

## Running the exploit

1. Launch PSO.
2. Go to options, network option, provider option, click yes and proceed to the network config screen.
3. Choose "manually set IP Adress" and hit next
4. Enter the ip of your computer running PSOLoad, the various commands for this are below(on windows you can run `ipconfig` and look for the IPv4 Adress, on linux you would run `ip a` and look for the IPv4 for your network interface. For mac, if on a wired connection use `Ipconfig getifaddr en1` and for wireless `ipconfig getifaddr en0`)
    * Windows: `ipconfig`
    * MacOSX: if on a wired connection use `Ipconfig getifaddr en1` and for wireless `ipconfig getifaddr en0`
    * Linux: `ip a`
5. for the subnet mask, default gateway, and primary dns, those depend on your network settings. contact your ISP or system admin
6. In a terminal / command promp in the same directory as your PSOLoad application, copy a homebrew dol(for this purpose we will assume you are loading swiss) and launch it using `PSOload.exe swiss.dol`
    * On Mac and Linux you need to set the program to be executable if it isn't already(`chmod +x psoload2`) and run it with this command: `./psoload2 swiss.dol`
7. Now on PSO choose the Online Game option at the title screen. Follow the onscreen directions and create your character. After you have created your character and saved it to the mem card and the game asks if you agree to the user terms say yes. The game will begin to load and you will see a warp hole type screen. At this point the game is initializing the Gamecube BBA for connection and you should pay attention to your command prompt screen to verify you have received the messages that your content is being saved on the memory card.