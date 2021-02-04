#Introduction
This is an exploit written in Python3 that abuses XSS in order to credential harvest via an XHR.

#Getting Started
Download both test.html and xhr_harvester.py.
Change the parameters in the python script as needed in order to target what you are trying to harvest. The script can also be changed from a GET to a POST (see commented section in script).
Use the source code in test.html as a template to poison the victim site/request to be sent to your box running the python script.

#Note
This script is to only be used for security testing purposes and for educational reasons.
