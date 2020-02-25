# Firmware Analysis Toolkit 

FAT is a toolkit built in order to help security researchers analyze and identify vulnerabilities in IoT and embedded device firmware. This is built in order to use for the "*[Offensive IoT Exploitation](http://offensiveiotexploitation.com/)*" training conducted by [Attify](https://attify.com). 

这是 Firmware-Analysis-Toolkit 的 2020 年更新以前的版本，虽然新版本的 FAT 安装更加简单，但是很多网址对国内网友并不友好，故在此更新一版。使用方法：https://blog.csdn.net/song_lee/article/details/104393933
 
本次更新，添加了难以下载的 binaries 文件，待所有文件下载完成之后，请用根目录下的 binaries 覆盖 Firmadyne/binaries

### Example Run

```
$ python fat.py DIR850LB1_FW210WWb03.bin 

                               __           _   
                              / _|         | |  
                             | |_    __ _  | |_ 
                             |  _|  / _` | | __|
                             | |   | (_| | | |_ 
                             |_|    \__,_|  \__|                    
                    
                Welcome to the Firmware Analysis Toolkit - v0.2
    Offensive IoT Exploitation Training  - http://offensiveiotexploitation.com
                  By Attify - https://attify.com  | @attifyme
    
[?] Enter the name or absolute path of the firmware you want to analyse : DIR850LB1_FW210WWb03.bin
[?] Enter the brand of the firmware : dlink
[+] Now going to extract the firmware. Hold on..
[+] Firmware : DIR850LB1_FW210WWb03.bin
[+] Brand : dlink
[+] Database image ID : 1
[+] Identifying architecture
[+] Architecture : mipseb
[+] Storing filesystem in database
[!] Filesystem already exists
[+] Building QEMU disk image
[+] Setting up the network connection, please standby
[+] Network interfaces : [('br0', '192.168.0.1'), ('br1', '192.168.7.1')]
[+] Running the firmware finally
[+] command line : sudo /home/ec/firmadyne/scratch/1/run.sh
[*] Press ENTER to run the firmware...
```
