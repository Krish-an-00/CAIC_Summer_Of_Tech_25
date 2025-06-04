scavenger_hunt : downloaded the file using wget and used tar -xf for extracting and then navigated through its contents using cd , ls -a for hidden files and folders and got .flag file which leads to the flag
CTF challenges 
(a)Try it Out : just copy paste for pattern of flag
(b)welcome agent : connected using ssh and given format
(c)Hidden in the crowd : connect via ssh and found hidden file .flag which contained flag
(d)Process hunter : connect via ssh and read readme.txt and they seen running process usin ps aux and grep flag 
(e)Locked Vault :After extracting  proceeded to various steps.sh decoded base64 passwords for next steps too , giving appropriate permissions using chmod
(f)Log Explore: used curl to get file and renamed it while using curl made it executable but was not opening the reason i found   later was that i had aarch64 linux on my mac utm so was not opening binary x86 file so it took my lot time in ctf similar with dumpster diver also noopening but later after ctf completed i browsed help and then completed this and got file log.txt that led me to flag using gimp.
  and for practice i used try hack me , pico ctf and some tutorials .
