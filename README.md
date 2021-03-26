INTRODUCTION
------------

The Simple Weather Service will fetch the the weather report from wttr.in and output the result to the motd file located in /ect.

The location is set to vancouver by default.


REQUIREMENTS
------------

Working internet connection is required.


Installation
------------

Download the the files. 

Move the files wttr.service and wttr.timer to your /etc/systemd/system/ folder.

Move the file wttr.sh to your bin folder ($HOME/bin/).


CONFIGURATION
-------------

Open the wttr.service file with a text editor and change the directory in line 6. Change "michael" to your user name.

Make sure all files have executable permission.




