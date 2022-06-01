# com.vmware.HorizonClient

This is a flatpak build of VMWare Horizon Client for Linux

Only works with Xorg(X11)

## Installation

```bash
git clone https://github.com/iamxeph/com.vmware.HorizonClient.git #Clone this repo
cd com.vmware.HorizonClient
flatpak install flathub org.flatpak.Builder org.freedesktop.Sdk//21.08 org.freedesktop.Platform//21.08  #Install prerequisites
flatpak run org.flatpak.Builder --user --install --force-clean build-dir com.vmware.HorizonClient.yaml #Build
```
