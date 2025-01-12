# VirtualboxCommunication
## *Communication between two virtual machine*
- #### Check the host name and  ip address of second virtual machine 
![image](https://user-images.githubusercontent.com/103022040/162429024-4c1c460e-f3fb-4ef7-bdb6-d40e4a436156.png)
- #### Communicate between two virtual machine using ssh command with host name and ip address
![image](https://user-images.githubusercontent.com/103022040/162430076-e8fcf692-bc2a-478a-9856-5bcc28faecd0.png)
## *Import Export and backup of Virtual Machine*
- #### Create backup using export option from file menu
![image](https://user-images.githubusercontent.com/103022040/162432926-25f9f3f8-92b4-4f07-90d8-bda50296c176.png)
- #### Export Virtual appliance and provide a path
![image](https://user-images.githubusercontent.com/103022040/162433248-4291672d-3519-420b-a68f-ab6f5b36f6f4.png)
## *Linux File System Command*
- #### using  df -Th command to check file system disk space usage , show the amount of free disk space in linux
![image](https://user-images.githubusercontent.com/103022040/162564982-1e6592c8-6881-493f-9a29-61a81809bc0a.png)
- #### fsck (file system consistency check) is used to check and optionally repair Linux file systems. . 
![image](https://user-images.githubusercontent.com/103022040/162565276-3ea52dc6-e20c-40cc-b081-f1ba4905c470.png)
- #### lsblk displays block devices, when used with the -f option, it prints file system type on partitions as well:
-![image](https://user-images.githubusercontent.com/103022040/162565442-5bba3b27-a283-4dcc-af1c-f7a3b45acb8f.png)
 - #### mount command is used to mount a file system in Linux, it can also be used to mount an ISO image, mount remote Linux filesystem and so much more.
![image](https://user-images.githubusercontent.com/103022040/162565667-2bd667df-16b8-40bb-bd07-ff3b67a58572.png)
- #### blkid command is used to find or print block device properties, simply specify the disk partition as an argument like so
![image](https://user-images.githubusercontent.com/103022040/162566109-11d632e0-1f73-4dd8-8ddd-bf241ca826d5.png)
- #### file command identifies file type, the -s flag enables reading of block or character files and -L enables following of symlinks:
![image](https://user-images.githubusercontent.com/103022040/162566464-e6684740-275e-4ebc-9e21-692e92336282.png)
- #### The /etc/fstab is a static file system info (such as mount point, file system type, mount options etc) file:
![image](https://user-images.githubusercontent.com/103022040/162566564-16213754-f256-41e2-b130-847d91205438.png)
##  *Huge Page Command*
- #### command to check current huge pages details.This huge page size can be increased from 2MB to max 1GB.
![image](https://user-images.githubusercontent.com/103022040/162566921-c4331df1-6764-4ab2-a009-38b48584d388.png)
## *Swap Space Command*
- #### Type the following cat command to see total and used swap size:
![image](https://user-images.githubusercontent.com/103022040/162568340-dbca96e8-fea0-43d8-b097-8a179e3b5aa6.png)
- #### another way using grep command
![image](https://user-images.githubusercontent.com/103022040/162568407-abd85f6d-90eb-4ccc-a0f6-135317a32ed2.png)
- #### swapson -s command to show swap usage summary by device
![image](https://user-images.githubusercontent.com/103022040/162568554-9ab2402d-7eb5-47bb-8567-f8f4de318731.png)
- #### Use free command to monitor swap space usage
![image](https://user-images.githubusercontent.com/103022040/162568603-193df89a-e964-4abd-9a0b-8a8a5cf2f882.png)
- #### See swap size in Linux using vmstat command
![image](https://user-images.githubusercontent.com/103022040/162568683-6290b5bd-b0cd-44a1-9b8a-9abfbe2e3ce1.png)
## *GREP COMMAND*
- #### consider a file make using cat command
![image](https://user-images.githubusercontent.com/103022040/162569437-f1834f64-2886-4d00-bb4e-f0717b532998.png)
- #### The -i option enables to search for a string case insensitively in the given file. It matches the words like “UNIX”, “Unix”, “unix”. 
![image](https://user-images.githubusercontent.com/103022040/162569481-ba1ccfb4-9077-4d0e-b6ef-e285ec0a007d.png)
- #### We can find the number of lines that matches the given string/pattern 
![image](https://user-images.githubusercontent.com/103022040/162569621-072bbfe2-f2a7-4ab2-a116-0c4bb66457d4.png)
- #### Checking for the whole words in a file.The -w option to grep makes it match only the whole words. 
![image](https://user-images.githubusercontent.com/103022040/162569705-057dfb04-fdd7-4f88-bcc8-739bc11231ec.png)
- #### By default, grep displays the entire line which has the matched string. We can make the grep to display only the matched string by using the -o option. 
![image](https://user-images.githubusercontent.com/103022040/162569757-9844917d-854d-4fc8-b508-04b8a21e2e77.png)
- ####  display the lines that are not matched with the specified search string pattern using the -v option. 
![image](https://user-images.githubusercontent.com/103022040/162569811-06167018-edea-4d1c-a5a4-9321da3a6a90.png)
- #### Replacement of new word with old word using sed command 
![image](https://user-images.githubusercontent.com/103022040/162572573-e9a5ffb0-f92f-4101-8a81-ad7920604369.png)


