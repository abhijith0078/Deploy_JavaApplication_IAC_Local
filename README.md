# JavaApplication_IAC_Local
Deploy Java application on multiple virtual machines consisting of Centos 9 and Ubuntu. For this project I am using MYSQL for local storage, MEMCACHED for database caching, RABBITMQ for message queueing, TOMCAT 9 for deploying/building Java application, and  NGINX as a load balancer.

If you want to run the script, then
- Confirm that you have Vagrant and a virtualization provider (e.g., VirtualBox) installed.
- Navigate to the project directory and run ' vagrant up ' to initiate the local development environment. After setup open the private IP 
address in the host machine's browser
   - Website URL: - http://192.168.56.29/login
   - Use login credential: admin_vp/admin_vp

 Output Application would look like this
![vprofile login page](https://github.com/abhijith0078/Deploy_JavaApplication_IAC_Local/assets/56915507/7312f1c2-3de6-45d8-a203-e32350d0e14e)
