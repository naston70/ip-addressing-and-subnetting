# FLSM

- Fixed-length means every subnet in your network will have the same mask

- Request: create 4 subnets, where 3 subnets should have 5 IP addresses each and 1 subnet needs 11 addresses

subnet 		hosts	  mask 		Network ID 		Range

1			11		  /28		192.168.1.0		192.168.1.1 - 192.168.1.14
2			5		  /28		192.168.1.16	192.168.1.17 - 192.168.1.30
3			5		  /28		192.168.1.32	192.168.1.33 - 192.168.1.46
4			5		  /28		192.168.1.48	192.168.1.49 - 192.168.1.62
