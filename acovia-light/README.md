# acovia-fcitx5-theme

![example](https://private-user-images.githubusercontent.com/233514576/647789107-06fa8848-af9d-46e7-85fc-8fa736b1eafe.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODg4NjE5ODUsIm5iZiI6MTc4ODg2MTY4NSwicGF0aCI6Ii8yMzM1MTQ1NzYvNjQ3Nzg5MTA3LTA2ZmE4ODQ4LWFmOWQtNDZlNy04NWZjLThmYTczNmIxZWFmZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwOTA4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDkwOFQxMDAxMjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00YjUzNDRmOGYwMDYxNGEwM2M2ZTViYmFiMWQ2ZjE2ZjJlM2NjOWNlYzVlNmMwYmU3OWJkNTMwMzEyYjFkZGJkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.nyVoyxtFJ-9NUW_VkFp5tmnZUSNp3dkwI5ovGXcTGc0)

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