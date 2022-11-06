# Windows

### cleanmgr.exe
```bash
cleanmgr.exe /SAGESET:1
```

### cleanmgr.exe preset
```bash
cleanmgr /sageset:1
```

### mpv data location
```bash
%APPDATA%/mpv/
```

### Plex data location
```bash
%LOCALAPPDATA%\Plex Media Server
```

### Python SimpleHTTPServer
```bash
py -m http.server 80
```

### Recent Items and Frequent Places
```bash
gpedit.msc
Under “User Configuration > Administrative Templates”, click “Start Menu and Taskbar”.
```

### Remove OneDrive in Navigation Pane of File Explorer
```bash
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace
```

### Remove Removable Drives From Navigation Pane
```bash
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\DelegateFolders
```

### Remove Windows 11 watermark
```bash
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
```

### Taskbar Setting
```bash
HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3
```

### Themes Setting
```bash
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize
```
