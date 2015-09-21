# wmr100-launcher-script

I was using software to pull sensor data from the Oregon Scientific wireless weather station. 
I downloaded the wmr100 monitor software from the internet, and it works well but crashes occasionally. 
I wrote this script to launch the wmr100 software, and automatically relaunch the software if it crashes. 
My script keeps track of how many times the software was restarted and stores this in a file called 
wmr100-restart-count, for later reference.
