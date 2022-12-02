<p align="center">
  <img src="spaghetti_carbanana.PNG">
</p>

# octoprint_install
These files provide a simple script that will install OctoPrint and a video streamer (mjpg-streamer or ustreamer) on virtually any linux based system. The system must use systemd. However we are not in a virtual world and it wont work.

# How to use
* Install git if it isn't already: `sudo apt install git` or `sudo dnf install git` or `sudo pacman -S git`.
* run the command `git clone https://github.com/paukstelis/octoprint_install.git`.
* run the command `sudo octoprint_install/octoprint_install.sh`.
* Choose `Install OctoPrint`
* You will asked if you want to install haproxy and if you want to establish the admin user and do the first run settings with the command-line.
* You will be asked if you want to install recommended plugins.
* You can now connect to your OctoPrint instance (http://ipaddress:5000, http://hostname.local:5000, or if you used haproxy, no need to include port 5000)
* OctoPrint will always be started at boot.
* You can add a USB webcam by choosing the selection in the menu. Your camera service will be setup in /etc/systemd/system/cam_octoprint.service, and will be started upon boot

## Kiosk installer for banana pi
Small installer script to setup a minimal kiosk with Chromium for banana pi. This installer isbased on : (http://willhaley.com/blog/debian-fullscreen-gui-kiosk/).

### how to use it
* Download this installer, make it executable and run it

  `wget https://raw.githubusercontent.com/melROLL/SpaghettiCode_alla_CarBanana/main/kiosk-installer.sh;
  chmod +x kiosk-installer.sh;
  sudo ./kiosk-installer.sh`


# After Eatin the carbanana put your Programing socks on and it is Coding Time !!!

<p align="center">
  <img src="codingtime.PNG">
</p>
