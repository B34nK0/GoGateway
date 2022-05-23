# GoGateway

## roadMap
-  [ ]  listen client request to build the long connect，every connect while have tow goroutine to implement  duplex communication
-  [ ]  listen trade/subscribe node to register, and implement workerManagement to manager worker proxy ，worker  has two type that is trade and subscribe
-  [ ]  implement trade worker ,forward request to trade node
-  [ ]  implement subscribe worker , forward request to subscribe node
-  [ ]  the worker has a msg queue to cache forward request