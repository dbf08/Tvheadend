# Tvheadend
Tvheadend script URL and file "not python"

Copy tv_grab_url and tv_grab_file (with the .txt) into docker tv /config folder.

open condsole on protainer

cd /config

chmod +x tv_grab_url
chmod +x tv_grab_file

cp tv_grab_url /usr/bin/tv_grab_url
cp tv_grab_file /usr/bin/tv_grab_file

reboot tvheadend
