# Diinki Aero

Fork of the <https://github.com/B00merang-Project/Windows-Vista> gtk theme, check it out!
The changes are mainly done to some UI elements in order to better fit in the more modernized design language
for 'diinki aero'

# Updates

I'm likely going to update the GTK theme more as time goes on.

# GTK4 / libadwaita

The `gtk-4.0` folder was rewritten for GTK 4.16+ and libadwaita 1.6+ (tested on GTK 4.24 / libadwaita 1.10).
It is meant to be copied to `~/.config/gtk-4.0`, where it is layered on top of libadwaita's own stylesheet:

- `aero.css`: the theme (colors, glass header bars, Aero buttons, Explorer-style selection, checks, menus…)
- `blur.css`: optional see-through header bars and sidebars for the Blur my Shell extension
- `gtk.css`: imports the two files above
