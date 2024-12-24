# mini
##### *Debian based OS - Beare Bones Desktop-Environment*



### Installation
1. Clone Repositoy
2. Run **install.sh*

``` sh
git clone https://github.com/batann/mini.git
sudo chmod a+x /home/batan/mini/install.sh
sudo bash /home/batan/mini/install.sh
```
### To Consider

|Header 1| Header 2|
|---|---|
|Default backup directory  |   /home/lc-backup|
|Default user configuration|   /home/config|
|In Development            |  - [ ] Seperate ext4 partition of 4GB mounted on boot |
|*fstab*                   |  UUID="" /home/config ext4 defaults,rw,(uid=1000),umask=0011,dmask=0000 0 0|

|ENVIRONMENT_VARIABLES $-----------------------------------------------------------------------------$  | 
||
||
||
|REMOVED                     anything gnome,xfce4 or desktop otherwise|
|                            any other bloat|
|                            possible decors such as entire directories /usr/share/{backgrounds,fonts,themes,ect}|
|                            and if mandatory replaced with smaller alternatives|
|                            complete user configuration directory and its content and replaced with sym-links|

