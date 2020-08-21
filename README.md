## ranger  
  
text-based file manager  
  
requires:    
```
apt install ranger
```  
```
yum install ranger
```  
```
pacman -S ranger
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/ranger/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/ranger" "$HOME/.config/ranger.bak"
git clone https://github.com/dfmgr/ranger "$HOME/.config/ranger"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/ranger" target="_blank">ranger wiki</a>  |  
  <a href="http://ranger.github.io" target="_blank">ranger site</a>
</p>  
