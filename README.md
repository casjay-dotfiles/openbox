## openbox  
  
Openbox is a highly configurable, next generation window manager  
  
requires:

```shell
apt install openbox scrot htop
```  

```shell
yum install openbox scrot htop
```  

```shell
pacman -S openbox scrot htop
```  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/openbox/raw/master/install.sh)"
```

Manual install:

```shell
mv -fv "$HOME/.config/openbox" "$HOME/.config/openbox.bak"
git clone https://github.com/dfmgr/openbox "$HOME/.config/openbox"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/openbox" target="_blank">openbox wiki</a>  |  
  <a href="http://openbox.org/wiki/Main_Page" target="_blank">openbox site</a>
</p>  
