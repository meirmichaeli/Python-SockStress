
		***Basic Usage***
Usage - ./sock_stress.py [Target-IP] [Port Number] [Threads]
Example - ./sock_stress.py 10.0.0.5 21 20
Example will perform a 20x multi-threaded sock-stress DoS attack
against the FTP (port 21) service on 10.0.0.5

		***NOTE***
Make sure you target a port that responds when a connection is made.
######################################
Do Not Use It In Production!
######################################
This is originaly downloaded from https://github.com/pan0pt1c0n/Python-SockStress

and converted to support Python3

Example of use: 

git clone https://github.com/meirmichaeli/Python-SockStress.git

chmod 777 Python-SockStress

sudo pip3 install scapy

python3 ./sock_stress_v2.py 10.110.24.143 80 10

