# Huntress CTF 2024

This was my first CTF I participated since starting out in Cybersecurity. Was pretty fun to solve what I could . I still need heaps of practice, and much more to learn , but was exciting. 
I was also attempting the Deadface CTF , but I wish i attempted more of the challenges.

This is to document the challenges I solved (beginning of my writeup journey)

### Typo
I was given ssh credentials to login to a server provided. When logging in , a train moves across the terminal/screen and animation is finished,the session is ended. To bypass this I looked up a ssh cheat sheet or commands , and used the quotes after  ' 'ssh command
eg: ssh user@ipaddress 'ls' .This gave me a response of listing files/folders and I saw a flag.txt  file , and re-entered command and adding cat the file eg: ssh user@ipaddress 'cat flag.txt' this gave me the flag. 
I have sinced saw a more efficient way(from another CTF writeup) to obtain the flag and this is to add -T so a pty terminal is not created.You can then cat the flag.

### Mystery
The enigma code was given with the enigma machines configuration.I solved this problem ,by using an online tool such as CyberChef .I entered the cipher code with the configurations and also altering the configs around. I was able to obtain the deciphered code.

Still in progress....
