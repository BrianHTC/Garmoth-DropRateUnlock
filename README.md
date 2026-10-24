# Garmoth-DropRateUnlock
A tampermonkey script to unlock Droprate adjustment function in Garmoth

# How it works

I assume we all know that the loot drop data in Garmoth Global Grind-tracker is 0%-based, linear. If you wanna know a certain drop rate, you can do the math yourself:
  100% is 2 * Drop count of 0%
  200% is 3 * Drop count of 0%
  300% is 4 * Drop count of 0%
  370% is 4.7 * Drop count of 0%
  
This script simply does this for you and displays it in the UI. 
Load the page, click the droprate icon, and type in a number. 

##Caution
This only works on the first time you open up the droprate icon. Refresh the page if you close the input tab.

#Disclaimer
This does not unlock paid function for you. Use at your own risk. 
