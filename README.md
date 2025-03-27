This tries to create minimal services to autostart Wayland compositor with correct dbus session.

Reason:
A simple service to autostart startx is introduced at https://vincent.bernat.ch/en/blog/2021-startx-systemd .
It does not need getty, shell, and any display manager.
It is possible for wayland compositor. However, it break dbus session.
