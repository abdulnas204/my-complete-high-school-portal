
# Intro

This project was developed by Okokoh (http://ekumaly.com) and Kelvin (https://kelvin.ugbana.com)

WE DEVELOPED HISP (SECONDARY, nursery, creche, school portal while in school learning programming. ) it is a great tool.
UBEB compliant, in fact it has all features, and I mean it. Starting from admission, scratch cards for admission, 
online payments, results, attendance, exam, cbt, graduation.. haha, I mean this portal is just an online school.
it can work for school that have multiple locations, eg. if your school is in many states the students can all be handled here from admission to graduation
parents, teachers, health attendant, principals, students, admins can login. I dont know how to say it again. it has all features a school can think of/
even cctv, parents can even track their kids even in the portal, I dont know how to explain all the features again oo..

# About
HISP Cloud School is school management system with all features a school can think of. Put your school in the cloud. School portal is Equipped with more than 50 Features that covers all sections of a High School. UBEB compliance.

# Version
2.1.8

#Framework
php7 was it built on, no framework. this is raw php work with mysql database

# Installation
We have tested on PHP 7.3.7 Apache web server
1. create your mysql database and import /TOOLS/hisp.sql(with dummy data), fresh_install.sql for fresh school production
2. edit /php.files/classes/pdoDB.php for your database configurations 
2. edit /control/includes/configuration.php for your database configurations again and others in the config files 
2b. edit /php.files/classes/kas-framework.php for some portal url config..
2c. edit /myjs/feccukcontroller.js for the same purpose you edited 2b above in two places.. server_root_dir and one img src there..
you may see some http://localhost/hisp/ change them to your own website url. ::)
3. Edit your webserver and set home.php as directory INdex (google it if you dont know) -- you see we did not have that index.php thing, its home.php here, we already did this .htaccess but just incase
4. edit /home.php for the Tawk.to Script 
5. run the sql in /TOOLS/sql_fix.txt in your database: that is run the code inside it as a fix.
6. SET YOUR SMTP DETAILS FOR MAIL SENDING: /php.files/classes/mailing_list.php
6. set mailHackingReport report email: /php.files/classes/mailing_list.php


I think you can see some of the features here: https://hisp.kastechnet.com/features
BOOM you are done, open the site and visit http://mysite.../control to login to admin as username = admin, password=cejine and start playing around.



# warning
we may have written powered by us. do not remove it.. never on earth should you change it to powered by you
because you did not write this code. unless you buy us coffee first then you can use it as you like..

# Have a problem?
please feel free to contact us for help and questions.. 
but please just be a php developer and do not bother us, look around and fix your issue, this portal was build to be very simple to use
the datbase already have some dummy data: you will need to shine your eyes and know the ones to remove before running a live production portal
trying to login to admin and you cannot find the password, you can easily change the password in the database oo
table = web_users, the password is just MD5 things -- git push origin master

# Are we awesome please donate?
BITCOINS :)

1DHHPQeggnDcr9NNm6uhhyEcA16GQPa8iJ

OR USDT (ERC20)

0x68c62c0c6e5d1e21c448133bccfc7fcb5d244f86


