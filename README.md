# ChromeOS Installation Script
Recovery images available here:</br>
https://cros.tech</br></br>
**rammus** >= 4th generation Intel</br>
**samus** <= 3rd generation Intel</br>
**zork** = AMD Ryzen 3xxx</br>
**grunt** = AMD Stoney Ridge</br></br>
Download the Brunch framework:</br>
https://github.com/sebanc/brunch/releases</br></br>
Copy the script, recovery bin file and Bruch framework files into a single folder. These files need to be available from within a Linux environment running from USB. I used a CIFS share and mounted it as /media/chromeos.</br></br>
Linux Mint Cinnamon is a good choice for live environment because the script works.</br>
https://www.linuxmint.com/download.php</br></br>
lsblk to determine which drive ChromeOS will be installed to. If different than sda modify the script to match. **Be sure the script matches the architecture and hard drive before proceeding.**</br></br>
Computer needs to boot in UEFI mode.</br></br>
Open a terminal from the folder:</br></br>
```chmod +x brunch_script``` </br></br>
```sudo bash brunch_script```
