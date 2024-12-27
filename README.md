# Default-Ethos-Nexus
## This will expain the process to create a basic Rotorflight Ethos and FBL setup, the readme.txt file explains the initial setup and presumes the registration and binding of a Frsky Access receiver to your transmitter has been done before these steps.

In this example the file and data is based on a Rotorflight Nexus FBL

1. Download the zip file and save to your desktop, unzip the contents.

2. The files include the following:

   Default Ethos diff-all.txt - This is the file to send to the FBL using the CLI 'load from file' option. This will populate the Nexus with the dafult settings.

   Default Ethos Model.bin - This is the Ethos model file and will be copied to the Transmitter SD Card in the models directory

   Default Ethos Readme.txt - This file explains the default configuration once the two files above have been applied.

   ## Setup

1. Connect the transmitter to the PC and run Ethos Suite, the latest version of Ethos Suite is available [HERE](https://github.com/FrSkyRC/ETHOS-Feedback-Community/releases)

2. On you Windows pc\laptop navigate to the file downloaded above (Default Ethos Model.bin), select and copy this file to the transmitter SD card , models directory.

![image](https://github.com/jimmy6616/Default-Ethos-Nexus/blob/img/default-radio-file.png)

3. Un-plug the USB cable from the transmitter, power down the transmitter and power-up, select the new model from the model select screen

![image](https://github.com/jimmy6616/Default-Ethos-Nexus/blob/img/default-radio-file1.png)


8. and connect to the Nexus fbl, open the Rotorflight configurator, the latest version can be found [HERE](https://github.com/rotorflight/rotorflight-firmware/releases)

9. Once connected to the configurator, click CLI on the left hand side, then click 'Load from File', select the 'Default Ethos diff-all.txt' down loaded from Github earlier,

![image](https://github.com/jimmy6616/Default-Ethos-Nexus/blob/img/default-radio-file2.png)

Click Execute. The file will be applied to your Nexus and will reboot

5. The Nexus FBL and your transmitter have now been configured.

6. Please ensure your transmitter has the test Click the receiver tab on the configurator


   
