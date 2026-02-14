# Automate-To-Sequence
DaVinci Resolve Lua script: Automate To Sequence

WINDOWS ONLY / ONLY FOR WINDOWS
 Только для Windows
 Faqat Windows uchun
 
Automate To Sequence Download (Latest Release):
https://github.com/automatetosequence/Automate-To-Sequence/releases/latest

YouTube: https://www.youtube.com/@automatetosequence

Telegram: https://t.me/automatetosequence

GitHub: https://github.com/automatetosequence/Automate-To-Sequence

Email: automatetosequence@gmail.com

<img width="1920" height="1080" alt="sequensi00000000" src="https://github.com/user-attachments/assets/867a410e-7be0-430b-a766-67a780804dd2" />
WINDOWS ONLY / ONLY FOR WINDOWS
 Только для Windows
 Faqat Windows uchun
<img width="1918" height="1033" alt="Screenshot 2026-02-14 023341" src="https://github.com/user-attachments/assets/46095856-da66-48dc-b62d-c4ec82d8c47b" />

AUTOMATE TO SEQUENCE — WINDOWS INSTALL GUIDE

PACKAGE OPTIONS (YOU CAN CHOOSE)
1) AutomateToSequence_Manual.zip (MANUAL)
   - You unzip and copy files manually.

2) AutomateToSequence_Auto.zip (RECOMMENDED)
   - Contains installer .exe. Double click the installer.

1) REQUIRED FILES (INSIDE THE PACKAGE)
 Manual ZIP (AutomateToSequence_Manual.zip)
 - AutomateToSequence.lua (main script)
 - bpmread\  (folder, next to the Lua file)

 AutoInstaller ZIP (AutomateToSequence_Auto.zip)
 - installer .exe

BPMREAD.EXE (AI / BEAT DETECTION)
- bpmread.exe is an AI helper EXE.
- The script uses the bpmread folder to write/read temporary helper files while working.
- For AI features, the bpmread folder must be located next to AutomateToSequence.lua.
- If bpmread.exe is missing, the script can still work, but AI markers will not be generated automatically.

PACKAGE STRUCTURE (WHEN YOU UNZIP)
- Manual ZIP: Edit/ folder containing AutomateToSequence.lua + bpmread\ folder.
- AutoInstaller ZIP: installer .exe (and included files inside the ZIP).

2) AUTO INSTALL (RECOMMENDED)
1. Close DaVinci Resolve.
2. Unzip the AutoInstaller ZIP.
3. Run the installer .exe.
4. Files will be copied automatically to the Resolve script folder.
5. Start DaVinci Resolve.

WHERE IT INSTALLS (AUTOMATIC PATHS)
A) Edit Script (Lua)
%APPDATA%\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\Edit\AutomateToSequence.lua

B) bpmread folder (next to Lua)
%APPDATA%\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\Edit\bpmread\

3) MANUAL INSTALL
If the installer does not work or you want to install manually:

1. Close DaVinci Resolve.
2. Open the folders below (in Explorer you can type %APPDATA%).

A) Lua script folder (Edit Scripts)
%APPDATA%\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\Edit\

- Copy into this folder:
  - AutomateToSequence.lua
  - the whole bpmread\ folder (with all files inside)

4) VERIFY
- Check that the script opens and the UI window appears.
- For AI features: bpmread\ must be located next to AutomateToSequence.lua.

5) UPDATE
- Easiest: download the latest release and reinstall (AutoInstaller ZIP).
- Manual: replace files (Lua / bpmread).

6) UNINSTALL
Close DaVinci Resolve and delete:
- %APPDATA%\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\Edit\AutomateToSequence.lua
- %APPDATA%\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\Edit\bpmread\

NOTES
- If folders do not exist, create them manually.
- The paths shown by the installer are the most reliable (for any Resolve version).

SUPPORT
Email: automatetosequence@gmail.com

