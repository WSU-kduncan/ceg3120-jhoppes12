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

1. I chose the Amazon Linux 2 AMI. This instance has a default user name of ec2-user. I also chose a t2.micro instance.

2. I attached the instance to my VPC before I launched my instance. I did it during steo 3 of instance configuration. 

3. I will not auto assign an Ip address becasue amazon can sell that address and change my instance address. I want one address to stay with my instance and for it to not change. 

4. i added 16Gb of General purpose SSD. I did this in step 4 of instance configuration before I launched the instance.

5. I added a tag to my instance before deploying it. I did this in step 5 of the instance configuration.

6. I added the secruity group I created. I did this before deploying my instance. I did this in step 6 of the instance configuration by selecting select an exiisting secruity group and selecting the one i created.

7. I went to the menu and selected Elastic Ips and hit allocate Elastic Ip and then we just hit allocate. I then hit the action menu and selected asscoiate Elastic Ip and then selected my instance.

8. ![Screenshot8](/Projects/Project2/Images/p2ss8.PNG) 

9. First I SSH into my instance and than copied /etchostname to /etc/hostname.old. I then checked my current hostname by running the hostname command. Next I then ran sudo hostname Hoppes-AMI to change the host name. 

10. ![Screenshot10](/Projects/Project2/Images/p2ss10.PNG)
