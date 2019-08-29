# wsp1-mysql
Intro till MYSQL
## Starta Server

Kör igång Ubuntu
Kör
Sudo apt service mysql restart
Sudo apt service apache2 restart

Om Apache2 bråkar pga port 80
Starta tjänster i Windows
Stoppa branchcache och starta apache2

## MYSQL

**setup**
Kör 
    sudo mysql -u root

    grant all privileges on *.* to 'rasmus'@'localhost' identified by 'password';
    
## Apache2
cd /etc/apache2

sudo a2enmod

Sedan går du in på localhost sidan och byter namn till localhost/~ Namn
