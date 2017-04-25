This is a device tree for Lava Iris X8 (MT6592) which is based on MT6592 SoC.
Based on Stock Lollipop kernel (3.10.72)


# Specifications:-
   * CPU	1.4GHz Octa-Core MT6592
   * Memory	2GB RAM
   * Android Version 4.4.2 & 5.1.1
   * Storage	16GB
   * Battery	2500 mAh
   * Display	5.0" 720 x 1280 DPI 320
   * Rear Camera	8MP
   * Front Camera	3MP


# Working
  * Dual SIM
  * Wifi
  * VPN
  * Bluetooth
  * Audio
  * Sensors
  * Camera (photo and video recording)
  * GPS
  * Screen Record
  * HD games
  * Tethering (Wifi, Bluetooth and USB)
  
# Not Working
  * All work !
  
# Credits/Thanks to:-
  * Hyperin70
  * Ferhung
  * CyanogenMod Team

# Compilation

	* repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1
        
	* repo sync
        
	* mkdir kernel && cd kernel

	* git clone https://github.com/hyperion70/j608_kernel
        
	* cd ..

	* cd device/Lava/iris_x8/patches

	* . apply.sh

	* . build/envsetup.sh && brunch cm_iris_x8-userdebug 
