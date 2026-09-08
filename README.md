# acovia-fcitx5-theme

![example](

A minimal Fcitx5 theme implemented via SVG, featuring a rounded, GNOME-like style.

## Installation

```bash
git clone https://github.com/fovlin/acovia-fcitx5-theme.git
cd acovia-fcitx5-theme
mkdir -p ~/.local/share/fcitx5/themes/
cp -r ./* ~/.local/share/fcitx5/themes/
```

Then open `fcitx5-configtool`, go to the Classic UI settings, and select the Acovia theme.

## Customization

The theme's appearance is implemented via SVG files. Edit the SVG files and modify the fill and stroke values to change colors.

You can also adjust specific parameters in `fcitx5-configtool`, which essentially edits the `theme.conf` file through the GUI.