# Isendu Connector #

This module allows to connect the Magento orders with Isendu to manage your couriers.

### Compatibility ###

* 2.3.x
* 2.4.x

### Install from zip file [*](https://bitbucket.org/) ###

* Link to download the module: [IsenduConnectorModule](https://bitbucket.org/)

* Extract the content of the zip file on your hard disk.

* In your Magento root directory, find the folder app/code. If code is missing, create it.

* Now, inside code, create the directories Isendu.

* Inside Isendu, copy the content of the zip file: you should see ConnectorModule, README.md, ...

(img)

Then, launch this command (on mac and linux):

``` 
php bin/magento module:enable Isendu_ConnectorModule

php bin/magento setup:upgrade

php bin/magento cache:flush

```

### Configuration ###

* Once logged in in Magento, select Stores > Configuration > Isendu > Connector. 

* Set Enable Isendu Module to "Yes"

(img)

* Refresh cache

(img)


