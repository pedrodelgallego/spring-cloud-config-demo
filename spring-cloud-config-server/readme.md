this service provide the secret word.

In order to get into the realm find the password here

http://192.168.99.100:8001/lab-3-client/default/

Run the service
---------------

````
 mvn package
 docker build -t demo/config-server .
 docker run -p 8001:8001 -d demo/config-server
````