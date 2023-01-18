# README #

* You can run this scrpt

### Requirements ###

* Any linux distribution running bash 
* netcat/nc 
* transmission BOT (If you don't have one, replace the talert in the script by another alert mechanism of your choice)

### How to use? ###
* Update **port_monitor.cfg** with a list of services you would like to monitor
* Keep/Save **port_monitor.cfg** in the same directory as the main script **port_monitor** 
* Update the **talert** script with your Transmission BOT details and keep/save n the same directory as the main script **port_monitor**
* Run the script manually or via cron. Or any other regular to invoke this shell script

### port_monitor.cfg ###
* Column #1: FQDN or IPADDRESS of the target machine
* Column #2: PORT Number of the target machine 
* Column #3: No of times the script will send the alert

### TRACKING and HISTORY ###
* The script maintains an active tracker in /tmp/port_monitor.tracker
* The script maintains an alert history in /tmp/port_monitor.history
* The script maintains a complete UP/DOWN history in /tmp/svc.history
* You can change these settings under the VARIABLES section of the script

### Tested on ###
* Linux: CentOS/RHEL/Ubuntu/Debian

### DISCLAIMER ###
* You are free to use the scripts for your lab/work as it is or modified to suit your needs
* I don't intend to or have the time to work via contributions in this repo at this time (maybe in the future if needed)



