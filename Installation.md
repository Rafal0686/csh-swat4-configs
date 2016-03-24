# Introduction #

This will lead you through installing SWAT 4 and configuring it and TortoiseSVN to work with our configs.

# Details #

If you don't own a copy of the game, you'll need to purchase it from [Direct2Drive](http://www.direct2drive.com/347/product/Buy-Swat-4-Gold-Download) or from a shady deal who may or may not be located off-shore.

## SWAT 4 Installation ##

Install SWAT 4 somewhere under your user directory, so that TortoiseSVN doesn't need admin privs to write to it all of the time. Something like `C:\Users\will\SWAT 4` will work perfectly.

  * DO NOT install Gamespy Arcade
  * DO install the expansion

### Windows 7 Notes ###

I needed to disable compositing and disable Aero to get the game to run correctly.

## TortoiseSVN ##

Install TortoiseSVN normally. Install the command line tools.

### Syncing with Google Code repo ###

First, you need to tell TortoiseSVN that your Swat 4 folder has some SVN shit in it.

  1. Right-click in the `SWAT 4` folder, and select `SVN Checkout`
  1. Enter `https://csh-swat4-configs.googlecode.com/svn/trunk/` as the repo URL
  1. Change checkout directory to the top level of the SWAT 4 installation folder
  1. Click OK

Before playing with other CSHers, it's a good idea to manually sync to the Google Code repo. To sync:

  1. Right-click your SWAT 4 folder
  1. Click `SVN Update`
  1. Enjoy!