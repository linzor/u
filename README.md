# u
Simple Arch Linux update script aur/pacman/mlocale database/ntp

## Options:

 `-h`                                      help message
 
 `-c`                                      opens a config in $EDITOR

 `-s`                                      shutdown the system after update
 
 `-r`                                      reboot the system after update

## Config:

 `aurh=aurhelper`                          Defines an aur helper
 
 `notifyonstepcomplete=1`                  Sends desktop notifications 
 
 `initimage=2`                             Skips/Asks or Forces an init image generation
 
 `cmdgenimg=sudo mkinitcpio -p linux`      Defines the image generation command
 
 `UpdateNTP=1`                             Disables/Enables ntp time updates
 
 `NTPserver=time.nist.gov`                 Defines an NTP server
