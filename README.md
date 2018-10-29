# SFDX  App

```
sfdx force:data:soql:query --query "SELECT Title, UrlName, IsVisibleInApp, IsVisibleInPkb, IsVisibleInCsp, IsVisibleInPrm, Body__c, PublishStatus FROM Knowledge__kav WHERE PublishStatus='Draft'"

sfdx force:data:soql:query --query "SELECT Title, UrlName, IsVisibleInApp, IsVisibleInPkb, IsVisibleInCsp, IsVisibleInPrm, Body__c, PublishStatus FROM Knowledge__kav WHERE PublishStatus='Online'"

---------------------------------------

sfdx force:data:tree:export --query "SELECT Title, UrlName, IsVisibleInApp, IsVisibleInPkb, IsVisibleInCsp, IsVisibleInPrm, Body__c, PublishStatus FROM Knowledge__kav WHERE PublishStatus='Draft'" -d data

---------------------------------------

sfdx force:data:tree:import -f data/Knowledge__kav.json

```

