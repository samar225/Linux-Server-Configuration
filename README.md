# Linux-Server-Configuration
##Description
To install a linux on virtual machine and make it host your web applications.
IP address: 35.229.92.124
Accessible SSH port: 2200

----------------------------
## requirements 
* The Linux distribution is ubuntu/trusty64.
* The virtual private server is Googke Cloud platform.
The web application is my Item Catalog project created earlier in this Nanodegree program.
The database server is PostgreSQL.

# Summry of steps has been done 
1. create an account in google cloud  and create linux image then create an vm inctanct.
2. generate pair of keys and put the public key in the sitting of ssh keys in google cloud vm instance.
3. connect from local vagrant to the new server we have created in step 1 and add grader user with sudo permition
4. set the firewall.
5. change the port number fromm 22 to 2200 and add other ports to the firewall.
6. update packges.
7. set the time zone.
8. install mod_wsgi and apache.
9. install bleach httplib2 request oauth2client sqlalchemy python-psycopg2
10. install PostgreSQL
11. install virtual environment, Flask and the project's dependencies
12. create cotalog.wsgi file 
13. create catalog as a user of the databse the create the database
14. configure and enable a new virtual host
15. create OAuth client_ID by and install the json file 
16. install git and clone catalog project.
17. rename the project file from `project.py` to `__init__.py`
18. edit calling json file in project code  
19. edit `databse_setup.py` file 
# Run the application 
http://35.229.92.124.xip.io
