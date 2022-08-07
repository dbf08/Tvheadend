# Tvheadend
Tvheadend script URL and file "not python"

Copy tv_grab_url and tv_grab_file (with the .txt) into docker tv /config folder.

Shell access whilst the container is running: docker exec -it tvheadend /bin/bash


To monitor the logs of the container in realtime: docker logs -f tvheadend




open condsole on protainer

cd /config

chmod +x tv_grab_url
chmod +x tv_grab_file

cp tv_grab_url /usr/bin/tv_grab_url
cp tv_grab_file /usr/bin/tv_grab_file

reboot tvheadend

Under EPG Grabber modules

tv_grab_url - under Extra argument "-u Url for xml"


![chrome_hYQHg5Afsz](https://user-images.githubusercontent.com/64939197/159654934-c5c7f9b3-79c7-44dd-8988-578b5fd94fbf.png)
