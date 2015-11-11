# Rescan
Redis Unauthorized Scan
##Lib
	https://github.com/google/ipaddr-py
	```shell
	git clone https://github.com/google/ipaddr-py.git
	cd ipaddr-py
	sudo python setup.py install
	```
	https://pypi.python.org/pypi/futures
	```shell
	pip install futures
	```
	
##Usage
	python rescan.py -f  inputfile.txt 
	inputfile.txt Format:
		 10.14.40.194:6379
		 10.14.40.194
	python rescan.py -i  192.168.1.1/24 -p 6379
