# Grub Bootloader

Grub merken lassen, dass er die letzte Auswahl vorauswählen soll:

1. `/etc/default/grub` öffnen (Root-Rechte notwendig!)
2. `GRUB_DEFAULT=saved` + `GRUB_SAVEDEFAULT=true`
3. `sudo update-grub` ausführen

> Source: https://www.gnu.org/software/grub/manual/grub/grub.html#Simple-configuration