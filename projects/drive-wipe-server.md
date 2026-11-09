#drive wipe server

##the problem
- Bellingham Junk got two server racks with RAID arrays and a bunch of hard drives that could be sold.

##hardware
- Dell enterprise desktop
-TODO:get more precise info on the PC used and the card i ordered to use the raid array hookups

##software
- NizOS for the server infra
- Nwipe for clearing drives

##how drives are verified
- smartctl verifying reallocated/pending sectors and making sure reported_uncorrect and offline_uncorrectable are 0

##logging
- smartctl logs saved for each drive

##throughput
- 1 drive/day currently
-TODO:come back and update with raid bay throughput once the card arrives

##results
- 10/15 drives wiped as of writing, active time cost ~5 minutes/drive

##what i would do differently
- get a dock station for SATA drives to be able to wipe more at once
-TODO: come back and add more after wiping SAS drives
