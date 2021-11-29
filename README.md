# pinn-pi400-systems

Tested with pi400 and sd card setup. To use you must change repo_list or specify alt_image_source in your recovery.commandline or alternatively manjaro, kali, retropie and openwrt can be installed to the sd card from another storage device offline if put into a folder named os with additional sourceforge tar.xz files.

fixes: kali - before booting change rootfstype from ext3 to ext4 in commandline.txt
       batocera dev - is recommended to disable splash in batocera.conf
       retropie - known hdmi audio bug fixed by installing pulse audio

The testing folder contains some personal customizations, the repo_list.json there is my current 512gb sd card partitioning layout so dont use that one most likely,
The repo_list_34px.json , repo_list_40px.json , or repo_list_original.json can be used to change icons. 34px is slightly smaller in size allowing 9 os to show at once on the main screen. You may need to delete the icons in your icons cache folder in settings partition for the images to refresh.

Main Pinn Os and wikis found here https://github.com/procount/pinn
Script I used to convert new images here https://github.com/sakaki-/pinnify
Website to help change partition sizes https://pinn.mjh.nz/
