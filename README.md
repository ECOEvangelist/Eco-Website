#Eco Website
Changing the world one line of code at a time

#Installing Composer on Linux environment

###Updating your system
~~~
sudo apt update
sudo apt upgrade
~~~
###Install Apache, Php, MySql
~~~
sudo apt-get install apache2
sudo apt-get install php
sudo apt-get install mysql-client

sudo apt-get install -y libapache2-mod php-cli php-zip php-xml php-mysql php-mbstring
sudo apt-get install curl
~~~
#####Get composer and install it globally so it can be accessed from every folder with just typing: composer
~~~
curl -sS https://getcomposer.org/installer | sudo php -- --install -dir=/usr/local/bin --filename=composer 
~~~
######Start working in our project
~~~
git clone https://github.com/EcoAfrica/Eco-Website <optional directory path>
cd <to the directory you saved the cloned project>
composer install
~~~
##Installing Dev-environments
######Go to google and search phpstorm student and register for the products
~~~
sudo snap install phpstorm --classic
sudo apt-get install mysql-workbench
~~~
#Please follow the instructions to configure your dev environment. More instructions later
###For any problems use the chat apps

##Configuring Phpstorm


