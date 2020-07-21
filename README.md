# TLS_Client
TLS_Client is sample code for a basic web client that fetches a web page from urls https://www.random.org/cgi-bin/randbyte?nbytes=32&format=h or https://www.google.com

this example is taken from https://wiki.openssl.org/index.php/SSL/TLS_Client
but with updated certificates files (2020-07-20) for www.random.org and www.google.com. Eclipse project files are included.

crt files contain X.509 Certificate with chain (PEM). Build on Debian requires package libssl-dev.

 
show certificates used by a web site:

openssl s_client -connect www.random.org:443 -showcerts


see also:

https://github.com/openssl/openssl/blob/master/apps/s_client.c

https://pki.goog/

https://stackoverflow.com/questions/29939204/getting-google-search-ssl-pem-certificate

https://curl.haxx.se/libcurl/c/example.html

https://repl.it/@MarcoTessarotto/httpsget


