# Windows

### Change taskbar
```bash
HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3
```

### Change theme
```bash
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize
```

### cleanmgr.exe
```bash
cleanmgr.exe /SAGESET:1
```

### Create cleanmgr.exe preset
```bash
cleanmgr /sageset:1
```

### Hide Removable Drives From Navigation Pane
```bash
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\DelegateFolders
```

### mpv
```bash
%APPDATA%/mpv/
```

### Plex
```bash
%LOCALAPPDATA%\Plex Media Server
```

### Python SimpleHTTPServer
```bash
py -m http.server 80
```

### Remove OneDrive in Navigation Pane of File Explorer
```bash
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace
```

### Turn Off Recent Items and Frequent Places
```bash
gpedit.msc
Under “User Configuration > Administrative Templates”, click “Start Menu and Taskbar”.
```
