# The main components and tools of linux


## CLI Commands

The core ones I use most of the time and know most of the common options for.

### Messing with text in files

* vi - Text editor
* sed - Regex matching (find and replace for text in files)
* awk - Similar to sed but for working with much more complex data structures (it's basically its own language)
* grep - regex search in files or streams of data. 

### General OS commands

* | - The pipe (chain output from one command into another) 
* ps - list processes on machine
* df - Disk free (show free space in mounts)
* dd - disk destroyer (superfast, bit for bit copy) 
* top - nicer ps
* getopts - get options from cli (used when writing shell scripts to take user input) 
* cd - change dir
* ls - list dirs
* pwd - print working (current) directory.

### Storage related commands 

* mkfs - Make new filesystems (format partitions)
* fdisk - Make partitions on drives
* mount - manage mounts of disks to the filesystem

### Server / network commands

* openssl - all things TLS are within
* netstat - network sockets (unix, tcp and udp)
* curl - HTTP getter / poster (file downloader, general good http debugging tool)
* ping - ICMP pinger
* ifconfig - local network interface configuration 
* ip - configure network interfaces (similar to ifconfig, present when ifconfig is absent in some distros)

## GUI Tools

* [Zenmap](https://nmap.org/zenmap/) Network analysis / packet crafter.
* 