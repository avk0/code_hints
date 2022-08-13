Сheck disks free space in Gb \
`df -h`

View size of folders and files \
`du -h PATH`

Clean Ubuntu journal cash \
`sudo journalctl —vacuum-size=1G`

Set folder permissions recursively \
`sudo chmod -R 777 PATH`

mount remote folder \
`sudo umount -l your_login@your_server_ip:path_to_remote_folder` \
`sudo mount -a`

mount remote folder on startup \
`sudo gedit /etc/fstab` \
add line at the end of a file: \
`sshfs#your_login@your_server_ip:path_to_remote_folder fuse user,uid=1000,gid=1000,port=22001,allow_other 0 0`

**grep**, find in files content \
`grep 'what' where` \
-r: recursive search \
-i: case insensitive

edit text file \
`sudo nano path_to_file` \
`sudo gedit path_to_file`
