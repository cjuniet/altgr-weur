A western european keyboard layout for Windows, with AltGr dead keys and precomposed diacritics, inspired by https://choam.eu/altgr-intl and https://github.com/thomasfaingnaert/win-us-intl-altgr, made by means of https://github.com/39aldo39/klfc after importing https://choam.eu/altgr-intl into my /usr/share/X11/xkb/symbols/us.  As klfc didn't do OEM_102 I changed the line starting with 56 OEM_5 into 56 OEM_102.

I had to change the name of this keyboard into an 8 character string altgrweu and changed the filename from us-altgr-weur.klc to altgr-weur.klc.  unix2dos was used as well as the Microsoft Keyboard Layout Creator cannot handle files with lf's only.

Dead_greek doesn't work, so that is why altgr OEM_5 and altgr OEM_102 show up as empty.

This is version v19 by Adriaan.

![AltGrg](AltGr.jpg)

![Shift+AltGr](ShiftAltGr.jpg)
