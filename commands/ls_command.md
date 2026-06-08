#  The `ls` Command

`ls [OPTIONS] [FILES]`  
→ list files and directories  


---

## Special Directory Symbols

`~`  
→ user's home directory  

`.`  
→ current directory  

`..`  
→ parent directory  


---

## Listing Current Directory

`ls`  
→ list files in the current directory  

`ls .`  
→ list files in the current directory explicitly  


---

## Listing Specific Directories

`ls ~`  
→ list files in the user's home directory  

`ls /var`  
→ list files in `/var` directory  

`ls /`  
→ list files in the root directory  


---

## Listing Multiple Directories

`ls ~ /var /`  
→ list contents of multiple directories  


---

## Long Listing Format

`ls -l ~`  
→ display detailed file information  
→ permissions, owner, group, size, date  


---

## Show Hidden Files

`ls -a ~`  
→ list all files including hidden ones  

`ls -la ~`  
→ list all files with detailed information  


---

## Single Column Output

`ls -1 /etc`  
→ display files in a single column  


---

## Directory Information Only

`ls -ld /etc`  
→ show information about the directory itself  
→ not its contents  


---

## Human Readable Sizes

`ls -lh /etc`  
→ show file sizes in KB, MB, GB  


---

## Sort by Size

`ls -Sh /var/log`  
→ sort files by size (largest first)  


---

## Sort by Extension

`ls -lX /etc`  
→ sort files by file extension  


---

## Hide Specific Files

`ls --hide=*.log`  
→ hide files matching a pattern  


---

## Directory Size

`du -sh ~`  
→ display total size of directory and its contents  

Note: `ls` does not show total directory size. Use `du` instead.
