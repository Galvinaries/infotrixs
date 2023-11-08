# infotrixs

                                                                  INFOTRIX TASKS WEEK-1

Cloud(AWS) Week 1 Task:
❖ Prerequisites:
- Create your free-tier AWS account
❖ Task: Deploy application in monolithic and microservices architecture
❖ Description:
- For monolithic : 1 EC2 instance, deploy wordpress and MYSQL on the same instances
- For microservices: 2 EC2 instance, 1 for wordpress and 1 for MYSQL
- Configure the necessary security group for the instances
- EC2 instance type: t2-micro, AMI: ubuntu-*
❖ Create a welcome page in wordpress that will be the homepage


For Monolithic
1.Created EC2 Instance
 

 


Edited DB authentication:
 

History:
ubuntu@ip-172-31-36-121:/var/www/html$ history
    1  sudo apt update
    2  suod apt install mysql-server
    3  sudo apt install mysql_server
    4  sudo apt install mysql-server 
    5  sudo mysql_secure_installation
    6  sudo apt install apache2 php libapache2-mod-php php-mysql
    7  wget -c http://wordpress.org/latest.tar.gz
    8  tar -xzvf latest.tar.gz
    9  sudo cp -r wordpress/* /var/www/html/
   10  sudo cp -r wordpress/*/var/www/html/
   11  ls
   12  sudo cd -r wordpress/
   13  sudo cp -r wordpress/
   14  ls
   15  sudo cp -r wordpress/* /var/www/html/
   16  ls
   17  ls -a
   18  cd ~
   19  sudo cp -r /home/ubuntu/wordpress/* /var/www/html/
   20  sudo chown -R www-data:www-data /var/www/html/
   21  cd /var/www/html/
   22  cp wp-config-sample.php wp-config.php
   23  nano wp-config.php
   24  ls
   25  cp wp-config-sample.php wp-config.php
   26  sudo cp wp-config-sample.php wp-config.php
   27  sudo nano wp-config.php
   28  history

For microservices:

Created two new instances for MySQL and WP:
 
Installed MySQL in ec2_mysql instance
 

 


Installed WordPress in ec2_wp instance
 

ubuntu@ip-172-31-37-218:~$ history
    1  sudo apt update
    2  sudo apt install apache2 php libapache2-mod-php php-mysql
    5  wget -c http://wordpress.org/latest.tar.gz
    6  tar -xzvf latest.tar.gz
    7  grep wp_version wp-includes/version.php
    8  ls
    9  history

 

 



