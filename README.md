# port_scanner
Essential reconnaissance tool, identifies open ports and services using the [sockets](https://docs.python.org/3/library/socket.html) module.
```
/***
*                      _                                           
*     _ __   ___  _ __| |_     ___  ___ __ _ _ __  _ __   ___ _ __ 
*    | '_ \ / _ \| '__| __|   / __|/ __/ _` | '_ \| '_ \ / _ \ '__|
*    | |_) | (_) | |  | |_    \__ \ (_| (_| | | | | | | |  __/ |   
*    | .__/ \___/|_|   \__|___|___/\___\__,_|_| |_|_| |_|\___|_|   
*    |_|                 |_____|                                   
*
*	@Author: prodseanb
*	@GitHub: https://github.com/prodseanb 
*
*/
[*] Scanning: {host}
[*] Please wait...
```
### Faster, more efficient
Using [threads](https://docs.python.org/3/library/threading.html) to maximize scanning efficiency.
```
Ports = 1000
Initial commit (before threads):
Time taken: 0:00:05.455632
This commit (with threads):
[*] Time taken: 0:00:00.199262
```
### Identifies open/listening ports and services
```
[Hit] 172.16.101.134:53 = Open        [*] SERVICE: domain
[Hit] 172.16.101.134:80 = Open        [*] SERVICE: http
[Hit] 172.16.101.134:443 = Open        [*] SERVICE: https
```
### Let's work...
As an open-source advocate, I invite you to work with me on this project. Send me a pull request. 🤘 Want to conduct other business? Send me a message on [LinkedIn](https://www.linkedin.com/in/sean-bachiller-40b63417b/). 
