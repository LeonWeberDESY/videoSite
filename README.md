## videoSite

Anleitung:

Raspberry Pi neu aufsetzen

Terminal öffnen

sudo apt install node

crontab -e

"@reboot sleep 15 && node ~/ssh-web-interface/server.js" einfügen und speichern

Verzeichnis "ssh-web-interface" und alle Dateien darin einfügen

ODER
mkdir ssh-web-interface 

nano server.js (Code einfügen)

mkdir public

nano index.html (code einfügen)

