# Linux Navigation Commands

## Special Directory Symbols

` . `  
→ current working directory  

` .. `  
→ parent directory  

` ~ `  
→ user's home directory  


---

## Directory Navigation

`cd`  
→ change current directory to the user's home directory  

`cd ~`  
→ change current directory to the user's home directory  

`cd -`  
→ switch to the last visited directory  
→ toggle between last two directories

`cd /path_to_dir`  
→ change current directory to a specific path  


---

## Current Directory

`pwd`  
→ print the current working directory  


---

# Tree Command

## Install tree

`sudo apt install tree`


## Usage

`tree directory/`  
→ display directory structure  
example: `tree .`  

`tree -d .`  
→ show **directories only**  

`tree -f .`  
→ show **absolute paths**
