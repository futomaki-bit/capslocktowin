# capslocktowin

Remape caps lock to windows key using .reg (regedit)
Click .reg file just like installing any programs then reboot

```
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout]
"Scancode Map"=hex:00,00,00,00,00,00,00,00,02,00,00,00,5B,E0,3A,00,00,00,00,00
```
