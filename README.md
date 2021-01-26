###Watchdog.py

###Description
A simple script to automate the cleaning of my local systems

###requirements
The script requires python3 to run. Tested on  `5.9.0-kali5-amd64` which is basically a debian system.
You need to install a few modules using pip 

```
pip3 install watchdog

```
###Setting up
Simply clone or download this repository and navigate your download location

```
git clone https://github.com/peter-macharia/watchdog.git

cd watchdog

cp watchdog.py ~/Downloads

python3 watchdog.py 

```
By default the script will clean the directory from which it is run from and store all those files under your **~/Stored/** basically a directory inside your home folder.

To change the location where the files should be moved to , edit the file watchdog.py and change the value of the variable **HOME** eg. 

`HOME = /home/media/WORK`

###ISSUES
Create a pull request , if you  have some ideas
Dm me on twitter [cephas](https://twitter.com/macharia_cephas) incase of any issues 

