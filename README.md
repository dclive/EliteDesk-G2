# HP EliteDesk 800 G2
 HP EliteDesk 800 G2 DM Repository

OpenCore .99 with MacOS 14.4.x fully tested and working

EliteDesk G2 800 DeskMini with firmware 2.60 (latest as of 4.24.2024)

iGPU.  2 DVI output.  I'm using external USBC SSD to boot.  32GB RAM - fully working.

Integrated Intel Wifi/BT does not work / is not reliable (endless prompting for a known-good password which is never accepted); sleep doesn't work; otherwise everything works.  

Note: Sleep doesn't work due to iGPU; there's no solution to this.

Action required on your part: regenerate serials and such; keep SMBIOS the same.  Works great.

Big credit to [randyzhong](https://github.com/randyzhong) for his work on this.  
