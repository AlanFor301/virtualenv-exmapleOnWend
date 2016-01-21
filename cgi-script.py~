#!/usr/bin/env python

import os, json, cgi

print 'Content-type: text/html'

print 
print '<HTML><H1>hello world</H1><BODY>'
print "<FORM method='POST'><INPUT name='x'>"
print 
#print  json.dumps(dict(os.environ), indent=4)

form = cgi.FieldStorage()
#escape python
print "<P>X was: "+ cgi.escape(str(form.getvalue('x')))#query ?x=1&x=2


print "<P>" + json.dumps(dict(os.environ), indent=4)
print "</BODY></html>"
print 
print 


