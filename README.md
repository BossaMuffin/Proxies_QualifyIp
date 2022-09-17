# QualifyProxiesIp
Qualify and sort a csv list of proxies ip addresses, by an asynchronous method :

The script testes the IP addresses list of proxies to sort it.
An example of inner csv file : proxies_lis.csv

It get your own IP address in order to control the tested proxies.
Then, it uses a thread pool executor in order to accelerate the process on the long Ip list to be tested.
At the end, it generates a new csv file with good IP proxies.
The outer generated file will takes the same format than inner : good_proxies_list.csv
