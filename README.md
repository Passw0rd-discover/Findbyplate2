# Findbyplate2
Findbyplate2, is an OSINT tool i made to lookup license plates, as it is still a working in progress but still pretty useful.

# Infomation about Findbyplate2
Findbyplate is a license plate tool that will lookup any license plate so long as it is valid given with the right state. It might not pull all the information you might want but it will definatly pull information you need. you might have to lookup the license plate first from the website, `If the license plate does not pop up in the terminal, go to findbyplate.com website to look it up then go back to the terminal to lookup the lisense plate`. All in all the tool works but if the plate is not showing up then you will have to go to the website first then go back to the terminal input the plate and state and there you go!

# Installing and run
```
git clone https://github.com/Passw0rd-discover/Findbyplate2/
cd Findbyplate2
pip install -r requirements.txt
```
If the search part for googling the VIN number doesn't work then here is how you can fix that.
```
cd /usr/lib/python3/dist-packages/
ls | grep google
rm -rf google-2.0.3.egg-info
pip install google
```
Have fun! I am not responsible for you do with this tool.
