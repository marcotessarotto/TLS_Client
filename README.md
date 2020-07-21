# TLS_Client
TLS_Client is sample code for a basic web client that fetches a web page from url: https://www.random.org/cgi-bin/randbyte?nbytes=32&format=h

this example is taken from https://wiki.openssl.org/index.php/SSL/TLS_Client
but with updated certificates file (2020-07-20) and includes Eclipse project files.

 
show certificates used by a web site:

openssl s_client -connect www.random.org:443 -showcerts
