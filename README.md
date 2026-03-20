sjgam m20 pro config
SJGAM M20 Pro DTB  Device Tree Blob (DTB) for the SJGAM M20 Pro handheld (RK3566).  
## What this is
This DTB is here in case anyone wants to experiment with alternative firmware. I personally am too much of a coward to flash it myself.  
## Status Experimental.
May boot, may not. Expect issues.  
## Usage -
Place the DTB in the /boot/ partition of your test SD - Update extlinux.conf to point to this DTB - Flash and test at your own risk  
## Notes -
Without correct DTB: black screen / boot failure - With DTB: partial compatibility only (drivers may still break)  
## Warning
You can brick your device. Backup your SD card before testing.  
Credits -
Community findings from SBCGaming subreddit
