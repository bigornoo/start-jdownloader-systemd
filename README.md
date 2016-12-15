# start-jdownloader-systemd
Howto start JDdownloader2 with systemd 

I've not found on the net how to start JDownloader with a systemd unit service file. So I've created my own. It's very simple but it works.
How to make it works : 
 - Download or clone
 - Put jdownloader.service in /etc/systemd/system
 - launch command : systemctl -daemon-reload
 - systemctl start jdownloader.service
 - enable at boot time : systemctl enable jdownloader.service
