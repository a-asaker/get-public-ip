#!/usr/bin/env python3
# Coded By : A_Asaker

from urllib.request import urlopen
try:
	print(" [#] Your IP :",urlopen('http://ip.42.pl/ip').read().decode('UTF-8'))
except Exception as e:
	from json import loads
	print(" [#] Your IP :",loads(urlopen('http://httpbin.org/ip').read().decode("UTF-8"))['origin'])
