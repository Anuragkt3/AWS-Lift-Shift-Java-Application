# Introduction
###
 JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# Technology Used 
- EC2
- ELB
- Autoscaling
- S3
- Route 53
# Database


Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


