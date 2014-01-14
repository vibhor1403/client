client
======
The server is running on port number 15000.
As of now this is fixed but can be changed later.

To connect the client with server, we need to provide ip:port as argument to client.
Example: If the executable file is 'client', then client code can be run like this:
./client 127.0.0.1:15000 


Currently, the server hosts an in memory hash based key value store.
to set a value, we need to give command 'set <key> <value>'
to get values from store, 'get <key>'
