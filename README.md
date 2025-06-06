This is a small AutoHotkey-based utility that remaps Ctrl + Enter to execute the current query in SQLyog, on top of the default F9 key behaviour. It mimics the behaviour of query execution in tools like MySQL Workbench, improving workflow consistency across environments.

#### Features
- Automatically detects active SQLyog window.
- Selects and executes the current query line with Ctrl + Enter.
- Lightweight and requires no installation (standalone .exe file).

#### Usage
- Download and run SQLyog-CtrlEnter-QueryExec-Rebind.exe.
- Open SQLyog and place the cursor on a SQL line.
- Press Ctrl+Enter to execute the current line.

#### Auto Bind
To automatically start the binding process on system startup, place the .exe file in the Windows startup folder.
- Locate the Startup Folder: Press `Win + R`, type `shell:startup`, and press `Enter`.
- Copy your .exe file or a shortcut to it.

#### Compatibility
- Windows only
- Requires SQLyog to be the active window
- Tested with SQLyog Community Edition

#### License
MIT License

![gif](https://github.com/user-attachments/assets/a768d27f-104f-49da-a13e-16cf3cbd8214)
