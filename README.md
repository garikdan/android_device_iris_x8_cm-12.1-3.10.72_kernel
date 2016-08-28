Fly IQ4511 Tornado One
Infinix Zero X506
==============

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.4GHz Octa-Core MT6592
GPU     | Mali-450MP2
Memory  | 1GB RAM
Shipped Android Version | 5.1 
Storage | 8GB
Battery | 1920 mAh
Display | 5" 1280 x 720 px
Camera  | 13MPx + 5MPx, LED Flash

==============

* Compilation

	# repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1
        
	# repo sync
        
	# mkdir kernel && cd kernel

	# git clone https://github.com/hyperion70/j608_kernel
        
	# cd ..

	# cd device/fly/IQ4511/patches

	# . apply.sh

	#. build/envsetup.sh && lunch cm_IQ4511-userdebug && mka bacon
