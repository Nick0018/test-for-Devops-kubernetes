create 6 VMs and 1 LoadBalancer in GCE. 
3 kubernetes master node
Private IP    	Public IP 
10.128.0.48   	35.222.36.249 
10.128.0.49   	35.222.36.250 
10.128.0.50	35.194.39.253  

3 kubernetes node
Private IP    	Public IP 
10.128.0.51   	35.193.77.99 
10.128.0.52   	104.155.130.254  
10.128.0.53	35.188.147.97  

LoadBalancer just for internal network. 
IP 10.128.0.47

Add firewall rule to allow the related port can be accessed.
