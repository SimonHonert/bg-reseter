# bg-reseter
This system resets your background-image of your pc every time you restart them. So it's perfect for pc-rooms at school. 
## Setup
### Windows
1. Download the Script using Git:
```
git clone https://github.com/SimonBalu/bg-reseter.git
```
2. Run the script:
```
test.bat
```
### Linux
1. Download the Script using Git:
```
git clone https://github.com/SimonBalu/bg-reseter.git
```
2. Add Permissions to the script:
```
chmod +x background.sh
```
3. Add Script to Autostart:
```
crontab -e
```
If a menu pops up, choose nano.
Add this to the end of the file with you file adress and save and close:
```
@reboot  /home/user/test.sh
```
