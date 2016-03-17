# Node-Red Node for SenecaJS

This library connects [node-red](http://www.nodered.org) to [senecajs](http://www.senecajs.org) microservices by providing a seneca client node.  Command patterns are sent via the message payload so they can be injected using the standard `inject` node or via other input nodes.  Command patterns sent to the payload must be properly formed JSON objects.

### Version
0.1.0

### Installation

```sh
$ npm install node-red-contrib-seneca
```
node-red should automatically detect the new node upon restarting of the server.

License
----

MIT

Copyright
----

&copy; 2016 John O'Connor