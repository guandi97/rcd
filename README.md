#recursive cd
just copy to your rc file

examples

back 3 directories
```
~ % rcd  .. 3
/ %
```

move forward 2 directories
```
/ % rcd 2
1:./aux/au:
2:./aux/pedoro:
3:./aux/transmission:
4:./boot/efi:
5:./dev/ati:
4
/boot/efi %
```

move to common
```
~/.steam/steam % rcd common
1:./steamapps/common:
2:./steamapps/common/Counter-Strike Global Offensive/platform/materials/vgui/common:
3:./ubuntu12_32/steam-runtime/amd64/usr/share/doc/libgtk2.0-common:
4:./ubuntu12_32/steam-runtime/i386/usr/share/doc/libgtk2.0-common:
1
~/.steam/steam/steamapps/common % 
```

search for directory, only 2 levels deep
```
/var % rcd 2 obs
1:./at/jobs:

/var/at/jobs %
```
enter will bring to first search term
