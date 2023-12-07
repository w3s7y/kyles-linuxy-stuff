# The main components and tools of linux


## CLI Tools you NEED TO KNOW

And know _well_ e.g. `ps -ef` <-- what do the `-e` and `-f` options do to the `ps` command and how is it different
on MAC vs Linux?

`ps -ef | grep java | awk '{x+=$1} END {print x*8192/1024/1024"Mb"}'` <-- what does this do? 

### Messing with text in files

* vi - Text editor
* sed - Regex matching (find and replace for text in files)
* awk - Similar to sed but for working with much more complex data structures (it's basically its own language)
* grep - regex search in files or streams of data. 

### General OS commands 

* ps - list processes on machine
* df - Disk free (show free space in mounts)
* dd - disk destroyer (superfast, bit for bit copy) 
* top - nicer ps
* getopts - get options from cli (used when writing shell scripts to take user input) 
* cd - change dir
* ls - list dirs

### Storage related commands 

* mkfs - Make new filesystems (format partitions)
* fdisk - Make partitions on drives
* mount - manage mounts of disks to the filesystem