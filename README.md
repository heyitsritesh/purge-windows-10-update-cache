# Clear Windows 10 Update Cache In Just One-Click

Create a **BAT** file and put the code given below. Save it and **Run as administrator**. It will automatically clear all the junk update cache from your Windows 10 system.

```
net stop wuauserv 
CD %Windir% 
CD SoftwareDistribution 
DEL /F /S /Q Download
net start wuauserv
```
Complete tutorial here: **[How To Clear Windows 10 Update Cache In Just One-Click](https://www.digitalkube.com/clear-windows-10-update-cache/)**
