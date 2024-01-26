# Turnigy-Fabrikator-Marlin-Firmware-Configuration
Marlin 2.0.7.2 with Configuration for Hobbyking Turnigy Fabrikator 3D Printer
Scroll down for description! Bitte runterscrollen für Beschreibung!

![Image of the firmware on my printer](https://github.com/PsychoOW/Turnigy-Fabrikator-Marlin-Firmware-Configuration/blob/dceccebcfb65cfd73bf5b9d5f1598f8bca9b0bf3/20240126_224422.jpg)

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

Happy printing! :)

# Deutsch

Hallo zusammen!

Ich habe auf meinem gebraucht erhaltenen Hobbyking Fabrikator eine sehr alte Marlin-Firmware verwendet. Kürzlich habe ich diesen Drucker gebraucht und kostenlos bekommen. Wie dem auch sei, ich wollte die Firmware aktualisieren, damit der Drucker Sicherheitsfunktionen hat, die in der älteren Firmware wahrscheinlich fehlten. Hobbyking bietet leider nur begrenzten Support für ihre Produkte, da keine Firmware mehr auf den Produktseiten verfügbar ist (auch keine Archive), und ich habe sie auch direkt über den Live-Chat kontaktiert, aber sie konnten mir nichts zur Verfügung stellen. Genauer gesagt, es gab auch keine Konfigurationsdatei, die verwendet werden könnte, um eine neue Marlin-Firmware zu erstellen, wenn man weiß, was man tut. Ich gehöre nicht zu diesen Personen, also bin ich nicht in der Lage, meine neue Firmware von Grund auf zu erstellen, weil es einfach zu umfangreich und schwierig für mich ist. Leider bietet Marlin keine Beispielkonfigurationen für diesen Drucker in deren Rep wie für andere Modelle, also war ich ratlos.

Glücklicherweise habe ich eine relativ aktuelle Marlin-Firmware gefunden, einschließlich der Konfigurationsdateien für diesen speziellen Drucker. Ich musste jedoch einige Änderungen vornehmen, da derjenige, der es in einem RC-Geräte-Foren hochgeladen hat (ein Dankeschön an ihn), einen automatischen Bettlevel-Sensor und andere Dinge konfiguriert hatte, den ich nicht besitze, und er hatte den Standardpositions-Laser ausgeschaltet, der normalerweise mit dem Drucker geliefert wird.

Ich habe die von ihm hochgeladenen Firmware-Dateien verwendet und sie mit Chatgpt (GPT4) modifiziert, was überraschend gut funktioniert hat. Ich habe auch überprüft, dass die Einstellungen in Ordnung sind und Vergleiche vor und nach der Modifikation durchgeführt. Es war für mich eine echte Herausforderung, es zu schaffen, aber es musste getan werden, da der Drucker ohne Anpassung der Firmware aus dem RC-Forum nicht funktioniert hat, und das war die einzige Möglichkeit für mich, den Drucker wieder zum laufen zu bekommen. Ich habe überprüft, dass es einwandfrei mit der Originalversion vom Hobbyking Fabrikator funktioniert (so wie man es damals gekauft hat ohne Modifikationen).

Da ich so viele Schwierigkeiten und Kopfschmerzen damit hatte, wollte ich die Firmware hier teilen, für Leute, die sich in einer ähnlichen Situation wie ich befinden und wenig technische Vorkenntnisse haben oder einfach nur die richtigen Werte für ihren Drucker benötigen.

# Anerkennung

Ein großes Dankeschön geht erneut an den Unbekannten im Internet namens "CrashingDutchman", der seine Firmware in diesem Forenbeitrag (Post 1992) geteilt hat. Hier ist der Link dazu:
https://www.rcgroups.com/forums/showthread.php?2392899-HobbyKings-%28Turnigy%29-Fabrikator-3D-Printer-thoughts/page80

Und natürlich ein herzliches Dankeschön an die Entwickler der Marlin-Firmware!

Es tut mir wirklich leid, wenn ich etwas forken oder eine bestimmte Lizenz wählen musste oder in diese Richtung gehen musste. Ich bin kein Entwickler und habe keine Ahnung von solchen Dingen. Alles, was ich tun möchte, ist das bereitzustellen, womit ich sehr hart gekämpft habe, damit niemand mit diesen Schwierigkeiten zu kämpfen hat und eine neue Firmware mit guten Sicherheitsfunktionen haben kann!

# Installation

Ich verwende die Arduino-IDE, um die Firmware auf den Drucker zu installieren, während er über USB verbunden ist.
Baudrate: 115200
Falls ihr das Menü vom Drucker gern auf deutsch hättet dann müsst ihr es in einer der beiden Konfigurationsdateien von "en" auf "de" ändern bevor ihr es kompiliert. das ist die zeile 1691 in Configuration.h (#define LCD_LANGUAGE en). Hier ist es gerade standardmäßig auf en gesetzt wenn ihr es runter ladet.

Viel Spaß beim drucken! :)
