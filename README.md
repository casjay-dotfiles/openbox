## openbox  
  
Openbox is a highly configurable, next generation window manager  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/openbox/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install openbox scrot htop
```  

Fedora Based:

```shell
yum install openbox scrot htop
```  

Arch Based:

```shell
pacman -S openbox scrot htop
```  

MacOS:  

```shell
brew install
```
  
```shell
mv -fv "$HOME/.config/openbox" "$HOME/.config/openbox.bak"
git clone https://github.com/dfmgr/openbox "$HOME/.config/openbox"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/openbox" target="_blank" rel="noopener noreferrer">openbox wiki</a>  |  
  <a href="http://openbox.org/wiki/Main_Page" target="_blank" rel="noopener noreferrer">openbox site</a>
</p>  
