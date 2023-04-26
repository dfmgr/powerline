## 👋 Welcome to powerline 🚀  

Description  
  
  
### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf "https://github.com/dfmgr/installer/raw/main/install.sh")" && sudo dfmgr install installer
```

OR

### Automatic install/update  

```shell
dfmgr update powerline
```
  
### requirements  
  
#### Debian based

```shell
apt install powerline
```  

#### Fedora Based

```shell
yum install powerline
```  

#### Arch Based

```shell
pacman -S powerline
```  

#### MacOS  

```shell
brew install powerline
```
  
#### Manual install  

```shell
APPDIR="$HOME/.local/share/CasjaysDev/dfmgr/powerline"
mv -fv "$HOME/.config/powerline" "$HOME/.config/powerline.bak"
git clone https://github.com/dfmgr/powerline "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/powerline/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```

## Author  

⛵ dfmgr: [Github](https://github.com/dfmgr) ⛵  
🤖 casjay: [Github](https://github.com/casjay) 🤖  

## Links

<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/powerline" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/powerline.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/powerline" target="_blank" rel="noopener noreferrer">powerline wiki</a>  |  
  <a href="powerline" target="_blank" rel="noopener noreferrer">powerline site</a>
</p>  
