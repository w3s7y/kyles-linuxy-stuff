# Exercises 

Some random ideas for kinda "How would you do this" in Linux.


## Basic day to day admin

* Create an automated job that checks for files in `/tmp` every 15 mins and cleans down files older than 7 days.
* find an old HDD and format it with the `zfs` filesystem and mount it to `/mnt/backup_drive`
* Add an automount rule so this drive mounts on system boot 


### Text mutatuion 

#### Easy text manipulation 

Create a commandline which will take this input: 

```text
This chapter is a comprehensive reference of all CVS commands, with a brief
summary of what each does. It is intended to be useful as a quick reference, not as
a tutorial.

This chapter covers the following topics:
* Conceptual overview
* Command-line syntax and options
* CVS dot files
* Environment variables
* Keywords and keyword modes
* Dates
* CVSROOT variables
* Alphabetical summary of commands
```

and turn it into the following output: 

Output:
```text
This chapter is a cbmprehensive reference bf all VS cbmmands, with a brief
summary bf what each dbes. It is intended tb be useful as a quick reference, nbt as
a tutbrial.

This chapter cbvers the fbllbwing tbpics:
* bnceptual bverview
* bmmand-line syntax and bptibns
* VS dbt files
* Envirbnment variables
* Keywbrds and keywbrd mbdes
* Dates
* VSROOT variables
* Alphabetical summary bf cbmmands
```

I did it with `echo` and `tr` but there are loads more! 

### Finding information about the current system

* How many cores does the machine have?
* How much memory is currently being used? 
* How much free space is on all the attached disks? 
* What other machines is it connected to?
* 
