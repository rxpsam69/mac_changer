
Features Version 1.1
Python 2
Linux only
 
Instructions
1. Download the repository, you can use the command below if you have git installed:
git clone https://github.com/sameryahya56/mac_changer
2. Make sure that you have python installed, just type python in your terminal and you will see an interpreter if it is installed.
3. Go to the folder where you have the repository cloned, make sure you are in the folder which the repository is and use (of course it must be unziped, if you used git clone it should be already unziped)
cd mac_changer/
4. Now you have to run the program like python mac_changer.py and the arguments (check the section below)
Arguments
You can use the short one with one "-" or you can use the long one with two "--"
Argument
Help
--help
To see more info and options.
-m / --mac
To put the new MAC Address (must be 6 pairs of alphanumerics characters) separated with ":" example 00:11:22:33:44:55
-i / --interface
Put the interface which you wanna change the MAC, to know your interface use ifconfig.


Combination of arguments
(examples only with short version but you can use long too)
--help:
python mac_changer --help
-i:
python3 mac_changer -i (your interface “eth0”)
-m:
python mac_changer -m 00:14:22:91:56:37 
Your line should be like this:
python mac_changer -i (your interface “eth0”) -m (the new mac address “ 00:14:22:91:56:37”)
 
 
 
 

