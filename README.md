### 🩸  Contents 🩸

<a><img src="https://i.pinimg.com/originals/72/34/77/723477bacaf41ad309f87d410037fa9f.gif" width="30%" height="40%" title="🙂" align="right"></a>
<br/><br/>

- <b>[🖥️ GRUB Themes](#previews)</b>
   - [Ver. 1](#1.)

Working on more... so I'll add them :)

- <b>[🔧 Installation](#installation)</b>
  - [First method](#1.)
  - [Second method (wip script, soon)](#2)


## Installation
##1.
<a><img src="https://i.pinimg.com/originals/04/15/cf/0415cfd2c29540261c950ed839829e63.gif" width="30%" height="30%" title="🙂" align="right"></a>
- Open your terminal
- Copy the repository and unzip

```
    git clone https://github.com/Zerabalus/Boodborne-GRUB
```


- Example:

- cd to where you copied it, on your terminal:
```
 sudo cp -r BBGrub /usr/share/grub/themes
```

- Or like in my case (DEBIAN-ARCH)

>Arch/Debian `sudo cp -r BBGrub /boot/grub/themes`

- Then edit the name of the grub theme you want:
```
sudo nano /etc/default/grub
```
```
GRUB_THEME="/boot/grub/themes/BBGrub/theme.txt"
```
- Update the grub
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

- Reboot
