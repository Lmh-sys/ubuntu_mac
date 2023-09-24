## 一 安装工具：TweakTool，并安装其扩展，配置扩展

```bash
# TweakTool
sudo apt-get update
sudo apt-get install gnome-tweak-tool
# 安装扩展
sudo apt-get install gnome-shell-extensions
# 安装浏览器扩展，方便通过浏览器安装软件扩展（主要配置dock,若不配置则忽略）
sudo apt install chrome-gnome-shell
# 重启系统
reboot
```
- 打开Tweaks（中文名 优化）并打开 User themes
## 二 配置主题
- 步骤一、安装 macOS GTK 主题
```bash
mkdir ~/.themes
xz -d Mojave-Dark.tar.xz
tar xvf Sierra-light.tar
sudo cp -r Sierra-light /usr/share/themes/Sierra-light

```
- 步骤二、安装MacOS图标
```bash
mkdir ~/.icons
xz -d 01-McMojave-circle.tar.xz
tar xvf Cupertino.tar
sudo cp -r Cupertino /usr/share/icons/Cupertino

```
- 步骤3：为系统添加类似MacOS的Dock面板
```bash
#Dash to Dock 是 GNOME 扩展。 到目前为止，您已经熟悉GNOME扩展。 只需转到此链接，然后单击切换按钮进行安装。 您的本机扩展坞将自动替换为“ dash-to-dock”。
sudo apt-get install gnome-shell-extensions
```
- 步骤 4、 设置MacOS壁纸
```
11-0-Color-Day-thumbnails.jpg
11-0-Day-thumbnail.jpg
11-0-Color-Night-thumbnails.jpg
11-0-Night-thumbnail.jpg
```