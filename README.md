# Ubports Redmi7 / Redmi y3
Ubuntu touch v2.0.0                                                      
Halium 9 Based                                                            
Status: Stable, unficial                                      
Password is "phablet"                             
Bugs: Fingerprint                                            
Author: Telegram: @supirlelik96, 4pda: supirlelik86    
Thank you:                                            
Telegram:  @Flydiscohuebr                                                                   
Telegram:  @erfanabdi                               


installation:                     
0.1 Unlock Bootloader               
0.5 Install TWRP          
0.9 Reboot in TWRP
1. Wipe system,art-cache,vendor,data or yes,
2. Run shell command (bash): 
    
    FILES=($(ls -l *.zip | awk '{print $9}')); for d in "${FILES[@]}"; do adb push $d /sdcard/$d; done

3. Install UBports-vendor.zip
   ubports-gsi-xx.zip
   halium-boot.zip
   halium-ramdisk.zip
   apparmor.zip
4. Reboot to system!
5. Fix camera

Fix camera:                                                         
    Password is "phablet"
    To connect to shell use ssh phablet@10.15.19.82
    In order to get camera working need to run commands blew in terminal:
wget https://static.peat-network.xyz/junk/ubports/com.ubuntu.camera_3.1.2+gstdroid3_armhf.click

ChangeLog:                                                          
-Update vendor                                 
-FIX flickering on the screen                 
-Improved system speed                        
-FIX for viewing videos on YouTube in 720p    
-Minor changes

Bugs:                                   
Fingerprint

Warning:                                                           
Charging your smartphone you may not see the charging icon                           
but the smartphone is charging and the battery charge percentage increases                      

Download:                                                                                         
Halium-boot: https://drive.google.com/file/d/1PrO0lrx6ihIpW0c0d4SWQN2Z46SEaRzi/view?usp=sharing                                        
Ubports gsi: https://build.lolinet.com/file/halium/GSI/ubports_GSI_installer_v9.zip                                              
Halium-ramdisk: https://build.lolinet.com/file/halium/GSI/tools/halium-ramdisk.zip                                      
Apparmor: https://build.lolinet.com/file/halium/GSI/tools/apparmor_enabler.zip                                       
UBports-vendor: https://drive.google.com/file/d/1_FRPq4cr88-Kx6aTud_l7lmCMsRw4Kkp/view?usp=sharing                                                     
