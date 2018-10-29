# SFDX  App

```
sfdx force:data:soql:query --query "SELECT Title, UrlName, Body__c FROM Knowledge__kav WHERE PublishStatus='Draft'"

sfdx force:data:soql:query --query "SELECT Title, UrlName, Body__c FROM Knowledge__kav WHERE PublishStatus='Online'"

---------------------------------------

sfdx force:data:tree:export --query "SELECT Title, UrlName, Body__c FROM Knowledge__kav WHERE PublishStatus='Draft'" -d data

---------------------------------------

sfdx force:data:tree:import -f data/Knowledge__kav.json

```

