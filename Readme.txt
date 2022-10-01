1, sudo cp 2 files below to /etc/udev/rules.d/:
	99-arduino-101.rules
	avrisp.rules
   with OpenCR board, add this file: wget https://raw.githubusercontent.com/ROBOTIS-GIT/OpenCR/master/99-opencr-cdc.rules
2, sudo udevadm control --reload-rules
3, sudo udevadm trigger
