# Computer Network HW2 Problem 7 Socket Programming with Python3 #

## Overview ##
Lab 5: HTTP Web Proxy Server. \
A small web proxy server which is able to cache web pages.

## Demo ##
![image](https://github.com/tim/Computer-Network-HW2-Problem-7-Socket-Programming-with-Python3/blob/main/get.png)
![image](https://github.com/tim/Computer-Network-HW2-Problem-7-Socket-Programming-with-Python3/blob/main/post.png)

## Feature ##
1. Error handling - Response "404 Not found" response when the link is not applicable. 
2. GET - The simple proxy server proxy_server_get.py supports HTTP GET method.
3. POST - The simple proxy server proxy_server_post.py supports HTTP POST method.

##  Usage Examples ##
1. Execute python3 .\proxy_server_get.py 127.0.0.1\
   Put http://localhost:8888/www.google.com as url on your browser 
2. Execute python3 .\proxy_server_post.py 127.0.0.1\
   Put http://localhost:8888/https://ptsv2.com/t/lztm4-1613635628/post as url on your browser
 
3. Caching: A typical proxy server will cache the web pages each time the client makes a particular
request for the first time. The cache file name is made as url of the website, such as 'www.google.com'
   
## Contributor ##
#### [Tim Kao](https://github.com/tim-kao?fbclid=IwAR0lWAvmWe03EtuderoHdKEpYYG8pnl2ca1bN1b5DBfEMP-wFv4kQupl-Jg) (UNI: sk4920)
