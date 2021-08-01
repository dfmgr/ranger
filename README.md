## ranger  
  
text-based file manager  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/ranger/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install ranger
```  

Fedora Based:

```shell
yum install ranger
```  

Arch Based:

```shell
pacman -S ranger
```  

MacOS:  

```shell
brew install ranger
```
  
```shell
mv -fv "$HOME/.config/ranger" "$HOME/.config/ranger.bak"
git clone https://github.com/dfmgr/ranger "$HOME/.config/ranger"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/ranger" target="_blank" rel="noopener noreferrer">ranger wiki</a>  |  
  <a href="http://ranger.github.io" target="_blank" rel="noopener noreferrer">ranger site</a>
</p>  
