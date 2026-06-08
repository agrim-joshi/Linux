# The Bash History

`history`  
→ show command history

---

## Showing the History

`history`  
→ display the list of previously executed commands

---

## Remove a Specific Line from History

`history -d 100`  
→ delete history entry number 100

---

## Clear Entire History

`history -c`  
→ clear all history from memory

---

## History File Size

`echo $HISTFILESIZE`  
→ number of commands saved in the history file (`~/.bash_history`)

---

## History Size in Memory

`echo $HISTSIZE`  
→ number of history commands stored in memory

---

## Rerun Last Command

`!!`  
→ execute the previous command again

---

## Run a Specific Command from History

`!20`  
→ run command number 20 from history

---

## Run the Last Nth Command

`!-10`  
→ run the command executed 10 commands ago

---

## Run Last Command Starting with Text

`!abc`  
→ run the most recent command starting with **abc**

---

## Print Command Without Running

`!abc:p`  
→ print the last command starting with **abc** without executing it

---

## Reverse Search History

`CTRL + R`  
→ search backward through command history interactively

---

## Show Date and Time in History

`HISTTIMEFORMAT="%d/%m/%y %T"`  
→ display date and time for each history command

---

## Make Timestamp Persistent After Reboot

`echo "HISTTIMEFORMAT=\"%d/%m/%y %T\"" >> ~/.bashrc`

or

`echo 'HISTTIMEFORMAT="%d/%m/%y %T"' >> ~/.bashrc`

→ save history timestamps permanently

---

