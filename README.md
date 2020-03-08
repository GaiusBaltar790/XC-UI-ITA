# XC-UI-ITA
THIS IS A FORK OF ORIGINAL XC-UI ADMIN by @GTA https://xtream-ui.com/
Please make a donation and enter in the forum for support: https://xtream-ui.com/forum/

WE aim to add some new features to XC and make italian as main language, but other languages
cane be chosen. At now: ITA, ENG(original), DE, SP and RU.

Please follow Changelog for more details


HOW TO INSTALL (for UBUNTU 18 and above)

This is only ADMIN, please install first XC-UI CORE from https://xtream-ui.com/
Then update with commands below:

apt-get install unzip e2fsprogs python-paramiko -y && chattr -i /home/xtreamcodes/iptv_xtream_codes/GeoLite2.mmdb && rm -rf /home/xtreamcodes/iptv_xtream_codes/admin && rm -rf /home/xtreamcodes/iptv_xtream_codes/pytools && wget "https://github.com/GaiusBaltar790/XC-UI-ITA/archive/master.zip" -O /tmp/update.zip -o /dev/null && unzip /tmp/update.zip -d /tmp/update/ && cp -rf /tmp/update/XC-UI-ITA-master/XtreamUI-master/* /home/xtreamcodes/iptv_xtream_codes/ && rm -rf /tmp/update/XC-UI-ITA-master/XtreamUI-master && rm /tmp/update.zip && rm -rf /tmp/update && chown -R xtreamcodes:xtreamcodes /home/xtreamcodes/ && /home/xtreamcodes/iptv_xtream_codes/start_services.sh && chattr +i /home/xtreamcodes/iptv_xtream_codes/GeoLite2.mmdb
