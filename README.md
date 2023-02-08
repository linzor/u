# u
Simple & responsive Arch Linux update script with notifications (aur / pacman / mlocale database / ntp)

## Options:

 `-h`                                      help message
 
 `-c`                                      opens a config in $EDITOR

 `-s`                                      shutdown the system after update
 
 `-r`                                      reboot the system after update
 
 `-f`                                      allows you to directly call a function from the script (example: ./u.sh -f ntpgetserverlist)
 
## Config:

 `aurh=aurhelper`                          Defines an aur helper
 
 `notifyonstepcomplete=1`                  Sends desktop notifications 
 
 `initimage=2`                             Skips/Asks or Forces an init image generation
 
 `cmdgenimg=sudo mkinitcpio -p linux`      Defines the image generation command
 
 `UpdateNTP=1`                             Disables/Enables ntp time updates
 
 `NTPserver=time.nist.gov`                 Defines an ntp server
 
 `NTPregion="europe"`                      Defines prefered ntp servers region (in case your default doesn't work)
 
  `NTPFindNewServer="1"`                   Defines if you want to look for a new ntp server (in case your default doesn't work)
