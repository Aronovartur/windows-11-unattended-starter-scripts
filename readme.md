This scripts runs any time i have a fresh installation of windows. it installs my usual tech stack and removes windows bloatware. 

before you can run this script you need to enable scripts in windows, this command will allow you to run all scripts, unsigned and otherwise: 
Set-ExecutionPolicy -ExecutionPolicy Unrestricted


you must run this using powershell in admin mode. the script removes windows terminal emulator app as part of cleanup but adds it back on later.

