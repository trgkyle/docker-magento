# Read first

# docker-magento
Support magento for 2.3.2 or lower

# Before Install

- Require:
    - magento data. Yes we need use magento data, you can dowload it at 
      https://magento.com/tech-resources/download and extract it to src directory
      
      explant: all file in magento will paste to src/magento directory


    - version support magento in this repo  2.3.2 or before ( any issue about update code please help)

# How run

I'm using docker-compose to set all environment needed


cmd:
    cd env/local 
    docker-compose up -d
phpmyadmin at : db.magento231.locahost
    useraccess: magento
    password: magento
to install with nornal way setup try magento231.localhost:
    Database Server Host: db
    Database Server Username: magento
    Database Server Password: magento
    Database Name: magento
# Finnaly Happy hacking !
