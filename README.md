# Flare5-miui9-patcher

############################################################################################
#### 
#### This Patcher is built for Cherry Mobile Flare 5
#### Chipset: MT6753 64-bit
#### Kernel: 3.18.19
#### 
############################################################################################

 After applying this patch to your ROM, please consider doing the following, specially if you're planning on applying this for a `MT6735` or `MT6737` device

1. Delete all lib files with `.nikel.so` or `.mt6797.so`
2. Delete [firmware] and [mddb] folders in `system/etc/` and copy the same folders from your Stock ROM
3. Rename the `Flare_5.xml` file inside `system/etc/device_features` folder to your device's model name and adjust the settings inside the file to match your phone's hardware/software.
4. After doing the above steps, proceed with the porting method for your device (MT6735/53/37)
