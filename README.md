# bashbox
Bashbox is a set of helpful bash script.

As for March 24, only the update.sh script is there.

__update.sh__
This script simply handle the entire process of the daily (or more) routien of updating an Ubuntu Linux desktop.
It handle snap and it shows what need to be updated, so you can kill the process to let it updates since snap do not handle the update of running application.
Thete is several opinionated choice here, check if it fit your need.
It handle parallel run of system update and automatic check with lock management. In other words, it can wait for the GUI or the background apt update to finish.

It doesn't handle firmware update.


__The initial design__
Add sublevel folders to handle specific distribution element, like the lsb_release -a which is Ubuntu specific.
Lack of time or lazyness, you'll chose, but this is not there yet.
