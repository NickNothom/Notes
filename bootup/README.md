# Bootup stuff

In rc.local

. /home/pi/companion/.companion.rc


In the script: 


sudo -H -u pi screen -dm -S survey python /home/pi/ping-python/depthGPSSurvey.py -d /dev/ttyUSB0


