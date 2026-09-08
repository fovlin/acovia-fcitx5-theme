# acovia-fcitx5-theme

一个通过 svg 实现的最小 fcitx5 主题，风格为圆角，类 gnome 主题。

![example](https://private-user-images.githubusercontent.com/233514576/647789107-06fa8848-af9d-46e7-85fc-8fa736b1eafe.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODg4NjE0MDEsIm5iZiI6MTc4ODg2MTEwMSwicGF0aCI6Ii8yMzM1MTQ1NzYvNjQ3Nzg5MTA3LTA2ZmE4ODQ4LWFmOWQtNDZlNy04NWZjLThmYTczNmIxZWFmZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwOTA4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDkwOFQwOTUxNDFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wNWM0MzZiZjNiZjJkMGYyY2E3NzYzMmI2MWNmNDg0MzU3NWNmZmVlNTdkNDQ4MDU2NzEzZmZhMzc3NDBhODU1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.3rSuzU-6kOL4doBTTQC-gp4WdOwqpEuDmLmi6r9M8jc)

## 安装

```bash
git clone https://github.com/fovlin/acovia-fcitx5-theme.git
cd acovia-fcitx5-theme
mkair -p ~/.local/share/fcitx5/themes/
cp -r ./* ~/.local/share/fcitx5/themes/
```

随后在 `fcitx5-configtool` 工具 - 经典用户界面设置内选择 Acovia 主题。

## 定制

主题外观以来 svg 实现，编辑 svg 文件，修改其中 `fill`，`stroke` 的值来更改其颜色。

可选在 `fcitx5-configtool` 工具中调整具体参数，这本质上是通过 gui 工具编辑 `theme.conf` 的值。