[![Python3](https://img.shields.io/badge/Python-3-green.svg?style=flat-square)](https://www.python.org/doc/sunset-python-2/) ![OS](https://img.shields.io/badge/Tested%20On-Linux%20|%20OSX-yellowgreen.svg?style=flat-square)
# About the tool

WiFi Crusher. This is like-a LazyScript by @arismelachroinos, but with the feel of the @rapid7 metasploit-framework.
                                                                       
## WARNING
I am not responsible, for any misuse or abuse of this tool(pranks, making trouble for Point-Of-Sale terminals, etc.) 
Since it's GNU, and redistrubited through GitHub(and/or any large repository), it comes with ABSOLUTLEY NO WARRANTY,  
to the extent by the applicable law.                                                                                   

## Technical Info

It uses aircrack-ng and MDK4 as an API to make random hotspots and fuzz your networks. It also allows to troll         
Tech Support scammers(shout-out to Malcolm Merlyn and Jim Browning). It has an user-friendly interface, with
lots, I mean... Lots of easter eggs, so I suggest to poke around, or look at the code, to find some easter             
eggs, or bugs. If you found a bug, please, send over in an "Issue" tab. I'll try to fix bugs as soon as                
possible.                                                                                                              

## Installation
**Clone the tool:** git clone https://github.com/inquisition-musician/wifi_crusher                                         

**Download Python3:** - For Debian-based: sudo apt-get install python3
                  - For MacOS(BSD): sudo brew install python3
                  - For Fedora-based: sudo yum install python3
                  - For others: sudo pacman install python3
                  
**Set permissions:** chmod +x wifi_crusher

**Run the tool:** ./wifi_crusher

### Updates
v.1.2
- Removed unused functions in the menu
- Added auto-monitor mode on menu selections from 1 to 5
- Dependecy check is redone. so, you can run the script without any problem.
- Added new logo. And, like quotes, it's random.
- Changed the way you run shell commands.
- Removed useless tips in help box, since those features are removed.
- If you pick "S" for shell, it will warn you, you should use "os <command>"
- Removed "Reload" debugging feature. It will be completeley random.
- Redone the way menu loads.

v.1.1
- Added root check, since aircrack-ng requiers root.
- Shell is now executed through "/usr/bin/bash/". So, you can use this tool for gaining root access.)
- Added check for KeyboardInterrupt(Ctrl + C). If hit, it exits.
- Corrected mistakes in names(e. g. Arios Mela Chronios is now Aris Mela Chroinos)
- Added disable monitor mode on-exit.
- Removed unused RandomStream variable.
