# Part 1 

On template 


# Part 2 

1. I created a .ssh/config file. In the file you have the Host so if I was on the Proxy I would want my host to be webserv1 and webserv2. 
Going down the file you have the hostname which is the ip of the system that you want to ssh into. Then you have the user which in this case would be ubuntu. 
Next you have port so in this case it would be port 22 because that is the port ssh uses. Last you have the identityfile which is the path to your key. 


2. To ssh inbetween systems with private ips you need the private key and the private so it would look like ssh -i /home/ubuntu/3120aws.pem ubuntu@10.0.1.10



3. To set up the haproxy load balancer we must modify the config file. 
	* The config file was modified and its locastion is under /etc/haproxy.
	* The configurations that were set was the frontend and backend 
	* To restart the service after the config we ran sudo systemctl restart haproxy
	* The resource I used was https://www.haproxy.com/blog/the-four-essential-sections-of-an-haproxy-configuration/


4. To set up the websever I edited the index,html file. 
	* I modified the index.html file located under /var/www/html I edited this html file to display the contents I want shown on my site. 
	* I did not set any configurations
	* The site contents are located under the public IP address because I am telling apache to host my site and sense there is no domain name the public ip will be adress of the contents
	* After a configuration change to restart you would run sudo systemctl restart apache2 
	* The resource I used was the recorded lectures. 
		
		
5. ![Site1](/Projects/Project4/Images/site1.PNG)

   ![Site2](/Projects/Project4/Images/site2.PNG)	
