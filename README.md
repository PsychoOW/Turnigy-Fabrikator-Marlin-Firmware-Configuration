# Turnigy-Fabrikator-Marlin-Firmware-Configuration
Marlin 2.0.7.2 with Configuration for Hobbyking Turnigy Fabrikator 3D Printer


Hello everyone!

I have been running a very old Marlin Firmware on my Hobbyking Fabrikator which i recently got for free second hand.

Anyways, i wanted to update the firmware so the printer is running with safety features, which the older firmware probably haven't had.
Hobbyking has a dissapointing support for their products, since there is no firmware from them available anymore because they simply removed it from the product pages (also no archives and i also contacted them directly through live chat and they couldnt provide me anything), or to be specific no configuration which could probably be used for building a new Marlin firmware if you know what you are doing. I am not one of these people so i am not able to build my new firmware from scratch because it is simply too much and dificult for me. Unfortunatly Marlin doesnt have example configurations for that printer like it does for others, so i was lost.

Fortunatly i found a relatively current Marlin firmware including the configuration files for that specific printer, but i had to modify a few things because the guy who uploaded it in some rcdevice forums (shoutout to him) had configured a level bed sensor which i dont have and he turned off the standard position laser that come with the printer.

I used the Firmware files he uploaded and modified it with Chatgpt (GPT4) which worked surprisingly good. I also confirmed that the setting are fine and i have made comparison between before and after. It was a real pain for me to accomplish it but it had to be done because the printer didnt work with the firmware from the forums without modifying it and that was the only possible way for me to do so. I verified it working perfectly with the stock version from Hobbyking Fabrikator.

Since i went through so many troubles and headaches i wanted to share the firmware here for people who are in a similar situation like me and lack technical background or simply need correct values for the printer. 

# Credits
Again big shoutout to the stranger in the internet called "CrashingDutchman" who shared his firmware in this forum Thread (Post 1992) and this is the Link:
https://www.rcgroups.com/forums/showthread.php?2392899-HobbyKings-%28Turnigy%29-Fabrikator-3D-Printer-thoughts/page80

And of course big thank you to the creators of marlin firmware!

I really apologize if i had to fork something or choose some kind of licence or anything in that direction, i am no developer and have no idea about that stuff. All i want to do is provide that what i have been struggling with very hard, so noone has to deal with that struggle and can have a new firmware with nice safety features!

# Installation
I use Arduino IDE for installing firmware on printer while it is connected with usb
baudrate: 115200
