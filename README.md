# US keyboard layout with Norwegian characters

This is a keyboard layout for using a US keyboard layout, and still have a way to enter ÆØÅ without switching back to a Norwegian keyboard layout.

## Install

On Ubuntu:
```
$ sudo cp no_custom /usr/share/X11/xkb/symbols/
$ setxkbmap no_custom
```

Other distros might use the above path, or `/etc/X11/symbols`.

This will reset it back to your default keyboard layout when you reboot. To make it persistent see: 

[https://wiki.archlinux.org/index.php/Keyboard_configuration_in_Xorg#Using_X_configuration_files](https://wiki.archlinux.org/index.php/Keyboard_configuration_in_Xorg#Using_X_configuration_files)

## Usage

```
(Left) ALT + ' = æ
       ALT + : = ø
       ALT + [ = å
       ALT + SHIFT + ' = Æ
       ALT + SHIFT + : = Ø
       ALT + SHIFT + [ = Å
```

