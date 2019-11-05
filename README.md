VRRTSLite2

VRRTSLite2

install :

cd ~/domoticz/plugins

mkdir VRRTSLite2

sudo apt-get update

sudo apt-get install git

git clone https://github.com/Erwanweb/VRRTSLite2.git VRRTSLite2

cd VRRTSLite2

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart

Upgrade :

cd ~/domoticz/plugins/VRRTSLite2

git reset --hard

git pull --force

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart
