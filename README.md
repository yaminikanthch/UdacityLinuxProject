# Linux Server Configuration

### Project Overview
> A baseline installation of a Linux server and preparing it to host our web applications, 
securing it from a number of attack vectors, installing and configuring a database server, and deploying our one of your existing web applications onto it.

#### Link to Project: [ItemCatalog](http://35.174.240.109)

* **Public IP Address:** 35.174.240.109
* **Accessible SSH port:** 2200

#### 2. Access VM using SSH
  * Download the private key from Udacity to your local machine.
  * use the below command to connect.
  * ssh -i Privatesshkey grader@35.174.240.109 -p 2200  

#### 3. Restart Apache if required to launch the app

   ```
    $ sudo service apache2 restart
   ```
#### 4. Below is the list of software installed on the VM
	* sudo apt-get update
	* sudo apt-get upgrade
	* sudo dpkg-reconfigure tzdata
	* sudo apt-get install apache2 libapache2-mod-wsgi git
	* sudo apt-get install libpq-dev python-dev
	* sudo apt-get install postgresql postgresql-contrib
	* sudo apt-get install python python-pip python-all-dev -y
	* sudo pip install SQLAlchemy
	* sudo pip install flask
	* sudo pip install oauth2client
	* sudo pip install requests










