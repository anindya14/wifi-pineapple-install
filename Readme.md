#!/bin/bash
git clone https://github.com/P0cL4bs/WiFi-Pumpkin.git
chmod +x install.sh
sudo ./install.sh --install
pip install --upgrade google-auth-oauthlib   ## To remove the service_identity error at start
