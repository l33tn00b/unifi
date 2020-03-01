# unifi
stuff for unifi configuration

## set mac address aging for switch ports (roaming issue between APs)

+ connect to switch, passwort aus der site config 
++	ssh switch8port -l admin

+ connect to admin unterface
++	telnet localhost
	
+ enable config
++	enable
	
+ enter config mode
++	config

+ set new aging time (30s)
++	bridge aging-time 30
