Open Putty and connect to the Oracle server
IP: 150.136.115.63
Username: opc
Port: 22

To start the server
java -Xmx10240M -Xms10240M -jar server.jar nogui
or
java -Xmx16384M -Xms16384M -jar server.jar nogui
or
java -Xmx16384M -Xms1024M -jar server.jar nogui

To stop the server
/stop
