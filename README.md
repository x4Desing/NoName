# NoName GTK Theme
Gtk Themes creados con [adw-gtk3](https://github.com/lassekongo83/adw-gtk3) y [libadwaita](https://gnome.pages.gitlab.gnome.org/libadwaita/).

Recomiendo usar [Fluent icon theme](https://github.com/vinceliuice/Fluent-icon-theme) by [@vinceliuice](https://github.com/vinceliuice).
| Light theme | Dark theme |
|:-----------:|:----------:|
| ![NoName-light](/Capturas/Captura%20desde%202022-08-10%2000-26-25.png?raw=true) | ![adw-gtk3-dark](preview-dark.png?raw=true) |

# Install
- Copiar las carpetas en `~/.local/share/themes/`.
- Selecciona el tema que te guste en Gnome Tweaks.
- Luego vé a la carpeta del tema que elegiste Ej: `~/.local/share/themes/NoName-Blue-dark/gtk-4.0` y cópia o créa un enlace a la carpeta `assets`, `gtk.css` y `default-dark.css` y los pegas en la carpeta `~/.config/gtk-4.0/`. 

# Edit

Si quieres modificar los colores tienes que modificar los archivos: `/gtk-3.0/gtk.css` y `/gtk-3.0/gtk-dark.css`.
Y en gtk-4.0 `/gtk-4.0/default-light.css` y `/gtk-4.0/default-dark.css`.

Cuando modifiques el tema `Dark` ten en cuenta que el archivo `/gtk-3.0/gtk.css` en realidad es el tema dark.

Si el tema es `Light` el archivo `/gtk-3.0/gtk.css` es el tema `Light` y `/gtk-3.0/gtk-dark.css` es el tema `Dark`.
