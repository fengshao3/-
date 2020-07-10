##  Deepin

## 安装软件

```
sudo dpkg -i XXX.deb
//如果报依赖包的错误，执行下面语句
sudo apt install -f
```



## 添加桌面

```
[Desktop Entry]
Type=Application
Icon=/opt/apps/firefox/icons/firefox.png
Name=火狐
Terminal=false
Hidden=false
Categories=Network
Comment=firefox
Exec=/opt/apps/firefox/firefox
Keywords=firefox
```

## 启动器搜索

添加到下面目录就可以在启动器搜索

 /usr/share/applications/

## Deepin

##  回收站命令

gio trash 