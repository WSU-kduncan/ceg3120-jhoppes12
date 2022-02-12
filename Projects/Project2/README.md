# Part 1 

1. ![Screenshot1](/Projects/Project2/Images/p2ss1.PNG) 
	* Creating my vpc with the tag Hoppes-VPC and a 10.0.0.0/24 private range of IPs.	

2. ![Screenshot2](/Projects/Project2/Images/p2ss2.PNG)
	* Created a subnet with 10.0.0.0/28 range of private IPs.
 
3. ![Screenshot3](/Projects/Project2/Images/p2ss3.PNG)
	* Created a internetgateway and attached it to my VPC.

4. ![Screenshot4](/Projects/Project2/Images/p2ss4.PNG)
	* Created a route table and attached it to my VPC. Asscociated it with my subnet and added a rule that sends all traffic to internetgateway.

5. ![Screenshot5](/Projects/Project2/Images/p2ss5.PNG)
	* Created secruity groups (firewall). Allowing http acess from any IPv4. It also allows SSH access from Home addresses, WSU addresses, and instance addresses.





# Part 2
