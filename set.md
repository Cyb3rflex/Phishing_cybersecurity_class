## Social Engineering Toolkit

you can install and run the Social-Engineer Toolkit (SET) on Ubuntu. Best practice: use the upstream TrustedSec repo (works on any Debian-based distro), or if you prefer a packaged route on Kali you can apt install set. Below are copy-paste commands and short troubleshooting notes.

Quick install (recommended: GitHub / upstream)

Run these in a terminal on your Ubuntu PC:

# 1) update and install deps
sudo apt update && sudo apt upgrade -y
sudo apt install -y git python3-pip python3-dev build-essential libssl-dev libffi-dev

# 2) clone upstream repo
git clone https://github.com/trustedsec/social-engineer-toolkit.git setoolkit
cd setoolkit


# 3)
install Python deps and install/set up SET
pip3 install --user -r requirements.txt   # installs into ~/.local by default
# run directly from repo (no global install required)
python3 setoolkit
# or, to install system-wide:
# sudo python3 setup.py install

TrustedSec’s GitHub README and the vendor page show the same approach. 
