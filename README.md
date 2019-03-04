# **Here are all the requirements for the hosted WebApp**:

* i- [IP Address] (http://http://18.184.167.28//)
     [SSH port] (2200)

* ii- http://18.184.167.28

* iii- In this task **software installed** mod_wsgi(a tool that allows Apache to serve flask apps) applications as vagrant, git, pip, virtualenv, httplib2, Python, Requests, oauth2client, SQLAlchemy, Flask, libpq-dev and psycopg2.

# Configurations
- Change ssh port to 2200
- Force UFW to allow only ports: 2200, 80, 123
- nuevoMexico.conf is added to sites-available directory
- nuevoMexico.wsgi is added to the rep to map apache with flask

# Resources that helped me

* iv- Amazon Lightsail, Udacity Videos, YouTube Tutorials and some github issues. Also some answered questions on stachexchange and stackoverflow

1. https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
2. https://www.godaddy.com/help/changing-the-ssh-port-for-your-linux-server-7306
3. https://www.thomas-krenn.com/en/wiki/Perl_warning_Setting_locale_failed_in_Debian
4. https://stackoverflow.com/questions/23870808/oserror-errno-13-permission-denied


* the password for any user : 123zizO
* 'grader' SSH passphrase: 123zizO


# To login from terminal:
`ssh -i $private_key -p 2200 grader@18.185.106.233`





