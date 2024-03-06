# Raspberry Pi Kiosk Mode

This script facilitates the setup of a Kiosk Mode on Raspberry Pi devices with a streamlined 1-line installation process. It configures a headless Chromium Browser to automatically launch upon boot, loading a predefined URL.

## Installation

1. Begin with a clean installation of **RaspianOS Lite** (ensure it's not the full version).
2. Upon the first boot, establish an SSH connection to your Raspberry Pi using a terminal.
3. Copy the provided installation script and execute it in your terminal.

```
cd; bash <(wget -qO- https://raw.githubusercontent.com/pabera/raspberry-pi-kiosk-mode/main/install.sh)
```
