# This repo is for the automation of billing out of Cloudbolt.
It contains a couple of file
Process is a recurring task that uploads a CSV to FTP File Name = 
After the FTP upload there's a script that runs on the linux FTP server that cleans it up file name = 
After cleanup, there a script that runs that emails it out. File name = 
The idea is to have the CB task run once a month, and the scripts on the linux FTP server every 5 mins via Cronjob

