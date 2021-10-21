>> To adjust brightness-

You can try changing the brightness level in the Kali Linux terminal using brightnessctl package. First, you may have to install the package using the following command

	>> sudo apt-get install brightnessctl
 
After installation, you can increase the brightness using,

	>> brightnessctl -q s +10% 

And decrease the brightness using the below command.

	>> brightnessctl -q s 10%- 
	
	
	
>> To enable bluetooth adapter-

	>> /etc/init.d/bluetooth start
	
>> To enable bluetooth service permanently-
	
	>> systemctl enable bluetooth.service


>> To synchronize the package index files from their sources again. You need to perform an update before you upgrade or dist-upgrade.

	>> apt-get update
	
>> To install the latest versions of the packages currently installed on the user’s system from the sources enumerated in /etc/apt/sources.list. 

	>> apt-get upgrade
	


	