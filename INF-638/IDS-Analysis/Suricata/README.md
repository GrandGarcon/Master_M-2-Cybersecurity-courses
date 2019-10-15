## Implementing open  source firewalls and  hands on approach to apply them in  handling real time use cases

### 1. lets see using practical examples how suricata works , how its configured and then how we can avoid the attacks of the APT campaigns by using the 
previous stored rules  or trying to  detect the attack by basic clustering and ML techniques.

### Architecture : 
 ```
                                                                                    ML heuristics by sklearn of 
                                                                                    the packet and other data information
                                                                                        |
                                                                                        |
                                                                                        |
                                                                                        |
                                                            pfsense created             V  
   feeding datasets ( network logs from splunk / fluentd) ----------------->  firewall defense by the suricata -------------> getting the  possible filetring and accordingly either the active and passive IDS will be setting the rules 
   
                                                            network 
 
 
 
 
 
 ```
