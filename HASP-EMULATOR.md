# HASP Dongle emulator

HASP Dongle emulator is a software product for Aladdin HASP, Safe-Net HASP dongle backup and virtualization that allows your software running just like original hardware key is connected to computer. Dongle emulator works with HASP USB dongles or parallel HASP hardware keys.

## Step-by-step instruction 

### Download HASPHL2010

Please download Aladdin HASP SRM, HASP HL and Hardlock FAST E-Y-E dongle dumper from the link below:

https://github.com/etech-software/dongle-emulator/releases/download/1.0/HASPHL2010.zip

*Windows 7,8 and 10 64-bit require special digital signature. You need to press F8 button on bootup and then select Disable digital signature enforcement. Then you can install and use HASPHL2010 with your OS.*

Please note, this procedure is required only once for reading your key. For emulation purposes you can use digitally signed emulator that is fully compatible with Windows 7,8 and 10.



### Install HASPHL2010
![Install HASP dumper](/img/hasp/hasp_emulator_1.jpg)
Unpack HASPHL2010.zip and start HASPHL2010.exe. When you start HASPHL2010.exe for a first time, press "INSTALL" button and wait for driver status changes to "Status : driver is installed"

### Start HASPHL2010
![Start HASP dumper](/img/hasp/hasp_emulator_2.jpg)

Please open "Emulator" tab and click Start Service button.

### Check status and start your software
![Start HASP protected software](/img/hasp/hasp_emulator_3.jpg)

Make sure dongle is connected to computer and original dongle driver is installed. If everything goes well, you will see "Service is running" message in status box. Then launch protected application.

### Reading HASP Key
![Read HASP dongle](/img/hasp/hasp_emulator_4.jpg)

Open "Dumper" tab. HASP/HL Dongles window must contain HASP dongle passwords. Press "Dump" button. Dump files are stored in folder containing HASPHL2010.exe and have ".DMP" or ".BIN" extension.

If there are no HASP passwords press "REFRESH" button. If it doesn't help and "DUMP" button is still disabled please contact us!

### Send us dump file

Please send us dump file by e-mail to contact@dongle-emulator.com

If there are no HASP passwords press "REFRESH" button. If it doesn't help and "DUMP" button is still disabled please contact us!

[Back to main page](README.md)