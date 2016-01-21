#!/usr/bin/env python

import urllib2
import requests
request = requests.get('http://google.com/teapot')
#curl does not go to the door that given in the html
#but python request does.
#print  requests.__version__

#print request.status_code

#print 'header content-type is: '+ request.headers['content-type']

#print request.text
url = "http://google.ca"
req = urllib2.urlopen(url, None, 3)
print req.getcode()
