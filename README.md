# spacefuel-releases

This repository serves **exclusively for release distribution** of the **SpaceFuel** application.  
It does not contain source code and is intended only to host packaged builds and related release artifacts.

---

## Windows Service Configuration

SpaceFuel can be configured to run as a **Windows Service** using the built-in `sc.exe` tool.

Below is an example command for creating the SpaceFuel Windows service:
`
sc.exe create spacefuel binPath= '\"C:\\Users\\Pc\\AppData\\Roaming\\spacefuel\SpaceFuel.exe\" --db \"C:\\Users\\Pc\\AppData\\Roaming\\spacepos\\terminals\\70e8f884-bee3-471e-ae69-432976cbaefd.db\" --config \"C:\\Users\\Pc\\AppData\\Roaming\\spacepos\\terminals\\70e8f884-bee3-471e-ae69-432976cbaefd.posterminal\" --pfcIniFile \"C:\\Users\\Pc\\Desktop\\PFC\\pfc2.INI\" --logPath \"C:\\Users\\Pc\\AppData\\Roaming\\spacepos\\logs\"' start=delayed-auto
`
