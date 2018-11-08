# SFDX  App

## To create a Scratch Org use

`sfdx force:org:create -f config/project-scratch-def.json -s -v [DEVHUB-USER] -d 1`


## Sample commands

```
sfdx force:data:soql:query --query "SELECT Title, UrlName, Body__c FROM Knowledge__kav WHERE PublishStatus='Draft'"

sfdx force:data:soql:query --query "SELECT Title, UrlName, Body__c FROM Knowledge__kav WHERE PublishStatus='Online'"

---------------------------------------

sfdx force:data:tree:export --query "SELECT Title, UrlName, Body__c FROM Knowledge__kav WHERE PublishStatus='Draft'" -d data

---------------------------------------

sfdx force:data:tree:import -f data/Knowledge__kav.json

```

