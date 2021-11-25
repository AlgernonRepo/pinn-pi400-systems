# pinn-pi400-systems

After not using my pi400 for a couple months I decided to ditch the 6 sd cards thing and research multi-boot options, and pinn os seemed to be the best option.

Tested only with pi400 and sd card setup. To use you must change repo_list or specify alt_image_source in your recovery.commandline  and reload repos
or alternatively manjaro, kali, retropie and openwrt can be installed to the sd card from another storage device if put into a folder named os with additional sourceforge files.

fixes: kali - before booting change rootfstype from ext3 to ext4 in commandline.txt
       batocera - is recommended to disable splash in batocera.conf
       retropie - hdmi audio bug fixed by installing pulse audio

Main Pinn Os and wikis found here https://github.com/procount/pinn
Script I used to convert new images here https://github.com/sakaki-/pinnify
Website to help change install partition sizes (this repo not added there but may be useful to save on possible gparted times) https://pinn.mjh.nz/
