# HP EliteDesk 800 G2
HP EliteDesk 800 G2 DM Repository

As hardware is now sold, there can be no further updates. 

OpenCore .99 with MacOS 14.4.1 fully tested and working

EliteDesk G2 800 DeskMini with firmware 2.62 (latest as of 4.24.2024)

iGPU.  2 DVI output.  I'm using WD Black SN770 500GB SSD to boot.  32GB RAM - fully working.

Integrated Intel Wifi/BT does not work / is not reliable (endless prompting for a known-good password which is never accepted); sleep doesn't work due to this machine's iGPU; shutdown in MacOS doesn't actually kill power (but the OS does shut down; the fan keeps running).  

Action required on your part: regenerate serials and such; keep SMBIOS the same.  Works great.

Big credit to [randyzhong](https://github.com/randyzhong) for his work on this.  

I5-6500: 



![Screenshot 2024-04-24 at 11 11 42 AM](https://private-user-images.githubusercontent.com/4536776/325298777-879ad2b5-ef42-4cfc-8ed4-0ae23fe7ab7e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU1ODY5MTIsIm5iZiI6MTcyNTU4NjYxMiwicGF0aCI6Ii80NTM2Nzc2LzMyNTI5ODc3Ny04NzlhZDJiNS1lZjQyLTRjZmMtOGVkNC0wYWUyM2ZlN2FiN2UucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDkwNiUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDA5MDZUMDEzNjUyWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NDNmNDEyZTBiMjY1YzQ0MDNlM2Y2MzQ0NTAwZmRjOWE1M2I2NjU5MDNiOWVjOGVlM2RjMjA3MjRmOWFkNTQxNyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.xQzfxeMva2flo9N878G_GyUGRwx1uNXEufzrHB1C3Zc)
