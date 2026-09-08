# acovia-fcitx5-theme

一个通过 svg 实现的最小 fcitx5 主题，风格为圆角，类 gnome 主题。

![](http://hub.acovia.net/pictures/acovia-fcitx5-theme.png)

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