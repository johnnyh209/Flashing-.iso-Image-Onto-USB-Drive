# Flashing .iso Image Onto USB Drive

Microsoft provides their own media creation tool for both Windows 10 and Windows 11 free of charge. This guide will not apply to Windows. Regardless, you will need to have an empty flash drive.

1. Obtain the .iso file for the operating system that you want to install onto your computer. For this guide, Fedora will be used. You can get .iso file for Fedora [here](https://fedoraproject.org/workstation/download).

2. Download your choice of software utility to create a bootable USB drive that will contain the .iso file. [Rufus](https://rufus.ie/en/) and [Balena Etcher](https://github.com/balena-io/etcher) are generally recommended. This guide will be using Balena Etcher.

3. Insert your flash drive into your computer.

4. Run Balena Etcher. You will see three symbols from left to right: a hexagon with a plus sign inside, a drive, and a thunderbolt.

<img src="https://github.com/johnnyh209/Flashing-.iso-Image-Onto-USB-Drive/assets/33064730/319f6bc0-b242-40c0-a733-af1e8107d197" Width="700" />

The program requires you start with the hexagon. Select `Flash from file`, and you will be prompted to select the .iso file for the operating system that you want to install. 

<img src="https://github.com/johnnyh209/Flashing-.iso-Image-Onto-USB-Drive/assets/33064730/db3619fe-cde7-4d49-9d46-e4842ec22c58" Width="700" />

5. After choosing your .iso file, the `Select target` button should become available for you to press (should have a light blue background rather than the dark gray background). Click on the `Select target` button, opening up a new window that lists the available drives connected to your system that you can choose to flash the .iso onto. It is important that you select the correct drive. Choosing a wrong drive will cause all of the files on that drive to be lost forever.
<img src="https://github.com/johnnyh209/Flashing-.iso-Image-Onto-USB-Drive/assets/33064730/3a2a1151-e0ae-4050-b236-ec6527bb18b9" Width="700" />

6. After selecting the drive, the `Flash!` button should now be in the same light-blue color, indicating that it is now active. Click on the `Flash!` button to start the process. There will be a progress bar that progressively becomes purple (from left to right) along with an ETA timer, indicating the progress of the process.
<img src="https://github.com/johnnyh209/Flashing-.iso-Image-Onto-USB-Drive/assets/33064730/fdd4c201-7dc0-49cc-9074-983a074648d4" Width="500" />
<img src="https://github.com/johnnyh209/Flashing-.iso-Image-Onto-USB-Drive/assets/33064730/743b307c-b7cf-417b-b595-ae672cf4dc68" Width="500" />

7. Once the process is complete, you will see the text `Flash Completed!`. At this point, you can close the program, safely remove the USB drive, and can now use it to install the operating system on that drive.
<img src="https://github.com/johnnyh209/Flashing-.iso-Image-Onto-USB-Drive/assets/33064730/7a766094-95ea-4795-b3de-c240424f0476" Width="700" />
