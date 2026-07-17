# linux-befehle
Linux Befehle
### Examples

Hier der Update befehl.
```
Sudo apt update
```
Installiert neuere Versionen aller aktuell installierten Softwarepakete, für die ein Update verfügbar ist..
```
Sudo apt upgrade -y
```
Hier Update, Upgrade, Autoremove und Autoclean. Mein Favorit.
```
Sudo apt update && sudo apt upgrade -y && sudo apt autoremove -y && sudo apt autoclean -y
```
Hier Update, Dist-Upgrade, Autoremove und Autoclean.
```
Sudo apt update && sudo apt dist-upgrade -y && sudo apt autoremove -y && sudo apt autoclean -y
```
