# Flashing .iso Image Onto USB Drive

Microsoft provides their own media creation tool for both Windows 10 and Windows 11 free of charge. This guide will not apply to Windows. Regardless, you will need to have an empty flash drive.

1. Obtain the .iso file for the operating system that you want to install onto your computer. For this guide, Fedora will be used. You can get .iso file for Fedora [here](https://fedoraproject.org/workstation/download).

2. Download your choice of software utility to create a bootable USB drive that will contain the .iso file. [Rufus](https://rufus.ie/en/) and [Balena Etcher](https://github.com/balena-io/etcher) are generally recommended. This guide will be using Balena Etcher.

3. Insert your flash drive into your computer.

4. Run Balena Etcher. You will see three symbols from left to right: a hexagon with a plus sign inside, a drive, and a thunderbolt.
![balenaEtcher_17eeokaXxl](https://github.com/johnnyh209/Flashing-.iso-Image-Onto-USB-Drive/assets/33064730/319f6bc0-b242-40c0-a733-af1e8107d197)
The program requires you start with the hexagon. Select `Flash from file`, and you will be prompted to select the .iso file for the operating system that you want to install.
