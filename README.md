networksp
=========

change wifi networks from CLI in os x (when ur too lazy to exit fullscreen terminal..)

usage: 

networksp <SSID> <password>

for this to work you need to create a symlink for airport:

sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport /usr/sbin/airport