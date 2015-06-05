# Servers

####1
The page list all backend servers.
![backend_server_list](../images/backend_server_list.png)

---
####2.1
![backend_server_add_1](../images/backend_server_add_1.png)
* **Name** : Backend Server Name.
* **Address** : Backend Server Address.
* **Port** : Backend Server Port.
* **Weight** : Used to adjust the server's weight relative to
other servers.
* **Maximum Connections** : Fix the maximum number of concurrent connections.

---
####2.2
![backend_server_add_2](../images/backend_server_add_2.png)
* **Check** : This option enables health checks on the server.
* **Check Interval** : Sets the interval between two consecutive health checks.
* **Check Fall** : States that a server will be considered as dead after
<count> consecutive unsuccessful health checks.
* **Cookie Value** : Sets the cookie value assigned to the server.
