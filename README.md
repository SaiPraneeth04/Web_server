# Developing a Simple Webserver

# AIM:

Name:Korivi Sai Praneeth
Reference number:22005263

# DESIGN STEPS:

## Step 1:

HTML content creation is done

## Step 2:

Design of webserver workflow

## Step 3:

Implementation using Python code

## Step 4:

Serving the HTML pages.

## Step 5:

Testing the webserver

# PROGRAM:
<<<<<<< HEAD
```python
from http.server import HTTPserver,BASEHTTPRequestHandler
content = ""
<html>
</head>
<body>
<h1>Welcome</h1>
<h1>K Sai Praneeth</h1>
<h>22005263</h1>
"""

class HelloHandler(BaseHTTPRequestHandler):
    def do_GET(self):
        self.send_response(200)
        self.send_header('Content-type','text/html: char=utf-8')
        self.end_headers()
        self.wfile.write(content.encode())
        
server_adderss =('',80)
httpd= HTTPserver(server_address,HelloHandler)
httpd.serve_forever()
```

=======

>>>>>>> 81fe7cbb3e256778b03293089b1e78a26946fc53
# OUTPUT:
![model](/webserveroutput.png)

# RESULT:

The program is executed succesfully
