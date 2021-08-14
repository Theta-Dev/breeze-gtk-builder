# Gnome-breeze

Build a GTK theme that matches your custom KDE breeze colors.

This is a fork of https://github.com/KDE/breeze-gtk

# Requirements

- Ruby-Sass
- Python with the ``pycairo`` package installed

# How to build

Add your KDE color schemes to the folder ``color-schemes`` and build the theme

```
./build_theme -c ThetaDev
./build_theme -c ThetaDevDark
```

The built themes are located in the ``build`` folder.

Copy them to ``~/.themes`` or ``/usr/share/themes`` for system-wide installation. Then you can choose the theme via System settings > Application style > Configure GNOME/GTK Application style.
