# Hydra Installer for Termux

This script automates the installation process of Hydra on Termux, a powerful tool for performing password attacks.

## Installation

1. Make sure you have Termux installed on your Android device.
2. Open Termux and run the following commands:

```bash
pkg update && pkg upgrade -y
pkg install git -y
git clone https://github.com/trmxvibs/termuxhydra
cd termuxhydra
chmod +x hydra
./hydra
