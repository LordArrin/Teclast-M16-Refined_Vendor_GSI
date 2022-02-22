# Teclast M16 Refined Vendor GSI
# Backported from Alldocube M8. TEST

Modded and tweaked vendor for GSI ROMs.

*Disabled useless mediatek's trash   
*Disabled camera's fps drop   
*Disabled encryption by default   
*Disabled many perf daemons   
*Added optimised settings from the other devices.    
*So much else that I've forgot)   

To fix camera add script to autorun: 


#!/system/bin/sh   
sleep 60    
killall camerahalserver   
killall cameraserver   
done    

He is also in /vendor/data as camerafix.sh

For better batterysaving turn on wq_power_saving throw the any kernel manager app. I recommend EX Kernel Manager.
    
Works on stock ROM, but I recommend GSI A11, especially this one by eremitein.
https://sourceforge.net/projects/treblerom/files/crDRom11/

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Deca-core                                                                                                                      |
| Chipset                 | Mediatek Helio X27 (MT6797X)                                                                                                   |
| GPU                     | Mali-T880 MP4                                                                                                                  |
| Memory                  | 4 GB LPDDR3 RAM Dual-channel                                                                                                   |
| Shipped Android Version | 8.0 x64                                                                                                                        |
| Storage                 | 128 GB EMMC5.1                                                                                                                 |
| Battery                 | Non-removable 7500 mAh battery                                                                                                 |
| Display                 | 11.6" IPS LCD1920 x 1080 pixels                                                                                                |
| Camera                  | 8MP + 2MP withot LED and legacy Camera2Api support                                                                             | 

## Device picture
<img src="https://github.com/LordArrin/different_trash/blob/main/pixlr-bg-result.png"/>
