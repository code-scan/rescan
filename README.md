# rescan
Redis Unauthorized Scan
##Lib:
	https://github.com/google/ipaddr-py
	https://pypi.python.org/pypi/futures
	
##Usage:
	python rescan.py -f  inputfile.txt 
	inputfile.txt Format:
		 10.14.40.194:6379
		 10.14.40.194
	python rescan.py -i  192.168.1.1/24 -p 6379
