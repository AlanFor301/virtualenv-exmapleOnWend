#!/usr/bin/env python

import requests
request = requests.get('http://google.com/teapot')
#curl does not go to the door that given in the html
#but python request does.
#print '\n version is: ' + requests.__version__

print request.status_code

print 'header content-type is: '+ request.headers['content-type']

print request.text
