## To RUN the module
- First **make**
	> make
- To check what is using **usb_storage**
	> lsmod | grep usb_storage
- To unload usb_storage along with the module currently using it. (*here* **uas**)
	> sudo modprobe -r uas **usb_storage**
- To insert the module
	> sudo insmod usbStickChk.ko
- To view messages
	> dmesg
- To remove the module
	> sudo rmmod usbStickChk.ko