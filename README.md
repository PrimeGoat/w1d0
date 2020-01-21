# w1d0


* **_ls_**: is short for list sub directories and files it shows the contents of the folders but it doesn't how hidden files
  * -a : list all files entries including the . & ..
  * -l :  (long list format) A total sum for all the file sizes is output on a line before the long listing 
  
    - Arguments: limitless

* **_'cd'_**: is short for change directory, used to switch between what directories you're working in. when you're in the finder and you want to move to another folder you'd use the 'cd' command.
   - An absolute path can be specified by starting with a "/"
   - You can also go up one directory by using ".."
     - Arguments: one

* **_'pwd'_**: is short for print working directory, basically shows you where you're currently at. 
     - Arguments: none

* **_'mkdir'_** : is short for make directory in other words, make a new folder wherever it currently is
  - can specify a path just like when using "cd". (instead of going there, it creates it)
     - Arguments: multiple  
  
* **_'rm'_**: means Remove but it only removes files, not directories.
  - -r : recursive, pick everything within a directory, including directory itself.
  - -f : forces deletion, without asking.
  - -v : verbose mode, tells you every file that's being deleted.
    - Arguments: multiple 

* **_'touch'_**: creates files but not folders, Update the access and modification times of each FILE to the current time
   - -a : only updates the access time. 
   - -m : only updates the modification time. 
   - -c : does not create a file. updates the time of existing file.
     - Arguments: multiple 

* **_'cp'_** : means to copy, the files and the directories, source and destination location
  - -f : force, overwrites files.
  - -p : preserves the timestamps, permissions and file attributes.
  - -r : recursive, allows for copying over the contents of a specified directory.
  - -v : verbose, will list all files that are being copied over.
     - Arguments: multiple, but last one is destination.
  
* **_'mv'_** : is move and or rename unless moving into another file system, then it copies and deletes original.
   - -f : force, overwrites without asking.
   - -i : interactive, makes sure to ask before overwriting.

![image](https://sd.keepcalms.com/i/a-class-that-cheats-together-graduates-together.png)