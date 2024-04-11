# bashpack
Bashbox is a set of helpful bash script.  
  
March 24, only the update.sh script is there.  
  
__update.sh__  
This script simply handle the entire process of the daily (or more) routine of updating an Ubuntu Linux desktop.  
It handle snap and it shows what need to be updated, so you can kill the process to let it updates since snap do not handle the update of running application.  
There are several opinionated choice here, check if it fit your need.  
It handle parallel run due to automatic system update with lock management. In other words, it can wait for the GUI or the background apt update to finish.  
  
It doesn't handle firmware update yet, but this is comming.
