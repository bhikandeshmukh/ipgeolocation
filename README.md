<p align="center"><a><img title="Built With Love" src="https://forthebadge.com/images/badges/built-with-love.svg"> </a>

<p align="center">
	<img src="res/ipgeolocation.png" width="600px" hight="100px">
</p>

# <p align="center">IP Geolocation

<p align="center">
<a href="https://github.com/bhikandeshmukh"><img title="Open Source" src="https://img.shields.io/badge/Open%20Source-%E2%99%A5-red" ></a>
 <a href="https://github.com/bhikandeshmukh/Termux-Keys"><img title="GitHub version" src="https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6&v=1.0.0&x2=0" ></a>
 <a href="https://github.com/bhikandeshmukh"><img title="Stars" src="https://img.shields.io/github/stars/bhikandeshmukh/saycheese?style=social" ></a>
</p>

# IPGeoLocation
====
* A tool to retrieve IP Geolocation information
* Powered by [ip-api](http://ip-api.com/docs/)


Requirements
=====
* Python 3.x
* termcolor
* colorama


Download/Installation
====
,,,
* git clone https://github.com/bhikandeshmukh/IPGeoLocation
* pip3 install -r requirements.txt
* cd ipgeocoation
* python3 ipgeolocation.py -t x.x.x.x
,,,

if pip3 is missing:
,,,
* apt-get install python3-setuptools
* easy_install3 pip
* pip3 install -r requirements.txt
,,,


Features
====
* Retrieve IP or Domain Geolocation.
* Retrieve your own IP Geolocation.
* Retrieve Geolocation for IPs or Domains loaded from file. Each target in new line.
* Define your own custom User Agent string.
* Select random User-Agent strings from file. Each User Agent string in new line.
* Proxy support.
* Select random proxy from file. Each proxy URL in new line.
* Open IP geolocation in Google Maps using the default browser.
* Export results to csv, xml and txt format.


Geolocation Information
====
* ASN
* City
* Country
* Country Code
* ISP
* Latitude
* Longtitude
* Organization
* Region Code
* Region Name
* Timezone
* Zip Code


Usage
====
```
$ ./ip2geolocation.py
usage: ipgeolocation.py [-h] [-m] [-t TARGET] [-T file] [-u User-Agent]
                        [-U file] [-g] [--noprint] [-v] [--nolog] [-x PROXY]
                        [-X file] [-e file] [-ec file] [-ex file]

IPGeolocation 2.0.4

--[ Retrieve IP Geolocation information from ip-api.com
--[ Copyright (c) 2020-2021 Mr. Bee (@Mr. Bee)
--[ ip-api.com service will automatically ban any IP addresses doing over 150 requests per minute.

optional arguments:
  -h, --help            show this help message and exit
  -m, --my-ip           Get Geolocation info for my IP address.
  -t TARGET, --target TARGET
                        IP Address or Domain to be analyzed.
  -T file, --tlist file
                        A list of IPs/Domains targets, each target in new line.
  -u User-Agent, --user-agent User-Agent
                        Set the User-Agent request header (default: IP2GeoLocation 2.0.3).
  -U file, --ulist file
                        A list of User-Agent strings, each string in new line.
  -g                    Open IP location in Google maps with default browser.
  --noprint             IPGeolocation will print IP Geolocation info to terminal. It is possible to tell IPGeolocation n
ot to print results to terminal with this option.
  -v, --verbose         Enable verbose output.
  --nolog               IPGeolocation will save a .log file. It is possible to tell IPGeolocation not to save those log
files with this option.
  -x PROXY, --proxy PROXY
                        Setup proxy server (example: http://127.0.0.1:8080)
  -X file, --xlist file
                        A list of proxies, each proxy url in new line.
  -e file, --txt file   Export results.
  -ec file, --csv file  Export results in CSV format.
  -ex file, --xml file  Export results in XML format.
```
  

Examples
====
**Retrieve your IP Geolocation**
* ./ip2geolocation.py -m

**Retrieve IP Geolocation**
* ./ip2geolocation.py -t x.x.x.x

**Retrieve Domain Geolocation**
* ./ip2geolocation.py -t example.com

**Do not save .log files**
* ./ip2geolocation.py -t example.com --nolog

**Custom User Agent string** 
* ./ip2geolocation.py -t x.x.x.x -u "Mozilla/5.0 (Windows NT 6.3; WOW64; Trident/7.0; rv:11.0) like Gecko"

**Using Proxy**
* ./ip2geolocation.py -t x.x.x.x -x http://127.0.0.1:8080

**Using random Proxy**
* ./ip2geolocation.py -t x.x.x.x -X /path/to/proxies/filename.txt

**Pick User-Agent string randomly**
* ./ip2geolocation.py -t x.x.x.x -U /path/to/user/agent/strings/filename.txt

**Retrieve IP geolocation and open location in Google maps with default browser**
* ./ip2geolocation.py -t x.x.x.x -g

**Export results to CSV file**
* ./ip2geolocation.py -t x.x.x.x --csv /path/to/results.csv

**Export results to XML file**
* ./ip2geolocation.py -t x.x.x.x --xml /path/to/results.xml

**Export results to TXT file**
* ./ip2geolocation.py -t x.x.x.x -e /path/to/results.txt

**Retrieve IP Geolocation for many targets**
* ./ip2geolocation.py -T /path/to/targets/targets.txt

**Retrieve IP Geolocation for many targets and export results to xml**
* ./ip2geolocation.py -T /path/to/targets/targets.txt --xml /path/to/results.xml

**Do not print results to terminal**
* ./ip2geolocation.py -m -e /path/to/results.txt --noprint 

```
## Legal Disclaimer:

Usage of the tool for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program


### NOTICE
I'm no longer maintaining this project. 

## Installing (Tested on Kali Linux, Ubuntu, Termux)

<p align="center">
<h4 align="center">♨️ FOLLOW ♨️<h4 align="center">
<a href="https://www.instagram.com/bhikan_deshmukh/"><img title="Instagram" src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="https://wa.me/918600525401"><img title="whatsapp" src="https://img.shields.io/badge/WHATSAPP-%2325D366.svg?&style=for-the-badge&logo=whatsapp&logoColor=white"></a>
<a href="https://www.facebook.com/thebhikandeshmukh"><img title="facebook" src="https://img.shields.io/badge/facebook-%231877F2.svg?&style=for-the-badge&logo=facebook&logoColor=white"></a>
<a href="https://www.twitter.com/bhikan_deshmukh/"><img title="twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white"></a>
<a href="https://t.me/dev_aladdin"><img title="Telegram" src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=Telegram"></a>
<a href="https://rzp.io/l/mrbee"><img title="DONATE" src="https://img.shields.io/badge/DONATE-yellow?style=for-the-badge&logo=google-pay"></a>
<a href="https://blockchain.com/btc/payment_request?address=3FH8UiVVKE5RkCaoaJ9Drr33Dg9L9FtsAq&amount=0.00008703&message=DONATE"><img title="Bitcoin" src="https://img.shields.io/badge/bitcoin-%23000000.svg?&style=for-the-badge&logo=bitcoin&logoColor=white"></a>
</p>
