# pinn-pi400-systems

After not using my pi400 for a couple months I decided to ditch the 6 sd cards thing and research multi-boot options, and pinn os seemed to be the best option.
The selection was very good but rpi4 builds for manjaro did not detect input and kali did not detect wifi on my pi400 originally so set out to fix them.
I also added batocera dev and openwrt the latter I have yet to test much but seems to boot.
For Kali I used ext4 format by mistake on this build so after installing but before booting edit its commandline.txt and change rootfstype=ext3 to ext4
For Batocera disable the splash boot in config.txt as only audio plays on start

Tested only with pi400 and sd card setup. To use you must change repo_list or specify alt_image_source in your recovery.commandline  and reload repos
or alternatively manjaro, kali, and openwrt can be installed to the sd card from another storage device if put into a folder named os with additional sourceforge files.

Main Pinn Os and wikis found here https://github.com/procount/pinn
Script I used to convert new images here https://github.com/sakaki-/pinnify
Website to help change install partition sizes (this repo not added there but may be useful to save on possible gparted times) https://pinn.mjh.nz/
